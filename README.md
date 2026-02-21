# 🌍 TravelGuideAI

TravelGuideAI is an intelligent web application that creates personalized travel itineraries based on user preferences.  
Users enter their destination, trip duration, and interests to receive a structured day-wise travel plan.  
It simplifies trip planning by providing attractions, food suggestions, cultural insights, and travel tips in one place.


🌍 Live Application: [Click Here to View the App](https://ai-travel-itinerary.streamlit.app/)

---

## About the Project

---

## ✨ Features

- Personalized travel itinerary generation
- Day-wise structured travel plan
- Attraction & food recommendations
- Travel tips and cultural insights
- Quick and simple user interface

---

## 🚀 Tech Stack

- Python 3.11  
- Streamlit  
- Google Generative AI  

---

## 📂 Project Structure

travelguideai/

│

├── app.py

├── requirements.txt

└── pages/ itinerary.py

   


---

## 💻 How to Run This Project Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/santhija-01/santhija-01-Explore-with-AI-Custom-itineraries-for-your-next-journey.git
cd TravelGuideAI
```

###  2️⃣ Install Dependencies

Make sure Python 3.10+ is installed.

```bash
pip install -r requirements.txt
```

### 3️⃣ Add Your Gemini API Key

On Windows (PowerShell):
```bash
setx GEMINI_API_KEY "your_api_key_here"
```

On Mac/Linux:
```bash
export GEMINI_API_KEY="your_api_key_here"
```

Restart your terminal after setting the key.

### 4️⃣ Run the App
```bash
streamlit run app.py
```

Open the local URL shown in the terminal.
