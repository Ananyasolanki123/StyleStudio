# 👗 Style Studio

**Style Studio** is an interactive fashion platform built using **FlutterFlow**, combining creative design tools with powerful AI models. From designing themed outfits to trying them on virtually, Style Studio makes fashion fun, personalized, and smart.

---

## 🌟 Features

### 🎮 Game Zone – Create & Compete

Design outfits based on themes:

* Scores for **theme match** and **creativity** are generated using **OpenAI CLIP** + trend analysis.
* **Color coherence** is evaluated using a **hybrid model** of **FashionBERT + CLIP**.

### 🎨 Design Zone – Free Styling

Modify existing dresses to match your unique taste and imagination.

### 🪞 Virtual Try-On

* Upload a photo and virtually try on different outfits.
* Dress recommendations powered by a **custom-built CNN** (developed from scratch in **NumPy**) via backend API.

### 🛍️ Home & Closet

* Browse **trending outfits**
* Maintain a **wishlist** and manage your **owned dresses** in your personal closet.

---

## 🛠️ Tech Stack

### 🎯 Frontend (FlutterFlow)

* UI built with **FlutterFlow**
* Integrates with APIs for AI-based processing and recommendation
* Firebase : Auth, Firestore, Storage
* HTML

### 🧠 Backend (AI + APIs)

* **Python** for backend logic
* **Flask** for backend logic
* REST APIs for:

  * CLIP + FashionBERT scoring
  * Virtual Try-On processing
  * CNN-based dress recommendation
  *  DALL·E API for image generation
* Hosted on: *local server and Railway site *
* Used api calls in flutter For backened logic

---

## 📱 Screenshots / Demo

SIGN IN Page
![Screenshot (583)](https://github.com/user-attachments/assets/21700db6-5e1e-4717-ac20-f153a5be083d)

HomePage 
![Screenshot (584)](https://github.com/user-attachments/assets/28940091-ab69-4177-a235-95cdc88aedde)

 Trending Page
 ![Screenshot (586)](https://github.com/user-attachments/assets/9798d784-aeb7-4124-b1a6-01ed9f2c4c74)

 Closet Page
 ![Screenshot (587)](https://github.com/user-attachments/assets/67554fc2-b0ab-4464-b495-b7500d7e3d24)

Profile Page
![Screenshot (588)](https://github.com/user-attachments/assets/5e6de8f9-1f6b-4a3f-8e1f-c46b43cc6cd7)

Game Zone
![Screenshot (590)](https://github.com/user-attachments/assets/dab75a9a-b599-4e1d-add5-7e009706ce21)
![Screenshot (591)](https://github.com/user-attachments/assets/93350048-470b-4a34-bc24-9b0347baea45)

Design Zone
![Screenshot (593)](https://github.com/user-attachments/assets/a1aeef0c-0a6c-4cb9-b873-49fb7cd9267d)

Trail Room
![Screenshot (594)](https://github.com/user-attachments/assets/30e58d57-e0e9-4fc1-b95f-d8b5851a7b20)
![Screenshot (595)](https://github.com/user-attachments/assets/2753b7e5-9571-42f0-9b43-5c92b908ce8e)
![Screenshot (597)](https://github.com/user-attachments/assets/c8a6a887-6e84-49c1-ac88-bf3c6d887a15)
![Screenshot (596)](https://github.com/user-attachments/assets/a700fd8e-9cd6-4684-ad68-c1c65eda4de0)

---

## 🚀 How to Run

### Option 1: Run via FlutterFlow

1. Open [FlutterFlow](https://flutterflow.io)
2. Import project using the `.ff` file or clone it from GitHub (if public)
3. Link your Firebase project (if applicable)
4. Configure API endpoints under **API Calls** section
5. Import virtual try on api file (https://github.com/Ananyasolanki123/virtual-tryon-api)
6. Import CLIP file (https://github.com/Ananyasolanki123/CLIP-file)
7. Import Hybrid Model File (https://github.com/Ananyasolanki123/Hybrid-model)
8. Run the app on emulator or deploy to web/iOS/Android
9. pip install scikit-learn
10.pip install flask torch torchvision transformers scikit-learn pillow
11.pip install torch torchvision transformers fastapi pillow
12.pip install flask pillow requests


### Option 2: Clone from GitHub (optional Flutter code export)

```bash
git clone https://github.com/Ananyasolanki123/StyleStudio
cd stylestudio
flutter pub get
flutter run
```

---

## 🔗 API Integration

| Feature                        | API Endpoint           | Method | Tech Used          |
| ------------------------------ | ---------------------- | ------ | ------------------ |
| Theme Scoring                  | `/api/score-design`    | POST   | CLIP, trend match  |
| Trend Match ,Color Coherence   | `/api/color-coherence` | POST   | FashionBERT + CLIP |
| Virtual Try-On                 | `/api/tryon`           | POST   | OpenCV, PIL        |
| Dress Recommender              | `/api/recommend`       | POST   | NumPy CNN          |

---



## 💡 Why I Built This

I love styling my outfits, but it often takes time and ends in a messy room. Style Studio brings outfit planning into the digital age – creative, efficient, and fun, all thanks to AI.

---

## 📬 Contact

Made by Ananya Solanki
📎 [LinkedIn](https://www.linkedin.com/in/ananya-solanki-6a319026a/) | 🧑‍💻 [GitHub](https://github.com/Ananyasolanki123) 

