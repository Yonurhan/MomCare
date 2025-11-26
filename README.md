# 🤰 MomCare — Maternal Health Companion App

MomCare is a full-stack mobile health app that helps pregnant women eat well, keep track of their symptoms, and spot early signs of stunting.  
The system combines **image-based food recognition**, **nutrition analytics**, and **risk assessment models** to give people personalized health advice that they can act on.

🏆 **Won Second Runner-Up (certificate)** at the **HOLOGY 2025 National Software Development Competition**  

---

## 🎯 Why MomCare?

- Stunting is still a big problem in Indonesia. One of the biggest risk factors is how much food a woman eats while she is pregnant. Data-driven decision support can help moms take action to stop problems before they start.  

- MomCare turns **daily food intake and health symptoms into insights** that help women have healthier pregnancies.

---

## 🧠 Key Features

✔ **Image-Based Food Recognition**  
Detect food and estimate calories + macronutrients from photos

✔ **Weekly Health Assessment**  
Users log symptoms → system analyzes risk indicators

✔ **Personalized Nutrition Dashboard**  
Track daily progress vs recommended nutritional targets

✔ **Health Risk Alerts**  
Flags patterns that may indicate need for medical attention

✔ **Educational Resources & Chatbot**  
Guidance for safe nutrition and pregnancy support

✔ **Community Space** 
Forum for discussion and shared experiences

---

## 🧩 Tech Stack

**Mobile Development**
- Flutter (Dart)

**Backend**
- Flask (Python)
- REST API (HTTP/JSON)

**Database**
- MySQL

**API Integration**
- External Nutrition Analysis API (food calories & macronutrients)
- FoodLogAPI

**Developer Tools**
- Git, GitHub
- Postman (API testing)

### 🚀 How to Run MomCare (Prototype)

1. Clone the repository
git clone https://github.com/yonurhan/MomCare_Final.git

cd MomCare/backend

2. Install Python dependencies
pip install -r requirements.txt && python nltk_setup.py

3. Set up and run the MySQL database
flask db upgrade

4. Enter the frontend directory
cd MomCare/frontend

5. Configure the IP Address in .env
In the .env file, replace the IP with your device’s IP.
To check your IP, open Command Prompt and type ipconfig.
Copy the IPv4 Address and paste it into the BaseURL field in .env

6. Run Flutter dependencies
flutter pub get
flutter run


