# Travel-Planner
An AI-powered Travel Planner built with Streamlit, Google Gemini API, and SerpAPI. It personalizes your trip by researching destinations, attractions, food, and stays, then generates a day-wise itinerary based on your budget, preferences, travel style, and interests.

# ✈️ AI Travel Planner

An **AI-powered personalized travel itinerary generator** built using **Streamlit**, **Google Gemini API**, and **SerpAPI**.  
Plan your **dream vacation** with smart suggestions for destinations, attractions, food, accommodations, and hidden gems based on your **budget, interests, and travel style**.

---

## 🚀 Features
- 🌍 **Personalized Trip Planning** – Get tailored recommendations based on your preferences.
- 🧠 **AI-Powered Research** – Uses **Gemini API** and **SerpAPI** for real-time data.
- 📌 **Day-wise Itinerary** – Generates a **detailed travel plan** for each day.
- 🏨 **Stay & Food Suggestions** – Recommends **hotels, Airbnbs, local food joints, and resorts**.
- 🎭 **Flexible Travel Styles** – Supports **solo, couple, family, and group** trips.
- ⚡ **Interactive & Simple UI** – Built using **Streamlit** for a clean and smooth experience.

---

## 🛠️ Tech Stack
- **Frontend / UI:** [Streamlit](https://streamlit.io/)
- **AI Model:** [Google Gemini API](https://ai.google.dev/)
- **Search Engine:** [SerpAPI](https://serpapi.com/)
- **Environment Management:** `python-dotenv`
- **Programming Language:** Python 3.10+

---

## 📌 How It Works
1. **User Inputs** – Provide details like:
   - Destination
   - Trip duration
   - Budget & travel style
   - Accommodation type
   - Interests & pace of travel

2. **AI Researcher Agent**
   - Creates **Google search queries** based on your preferences.
   - Uses **SerpAPI** to fetch the **top 10 travel recommendations**.

3. **AI Planner Agent**
   - Processes research insights.
   - Generates a **personalized, day-wise itinerary**.
   - Suggests **local tips, hidden gems, and cultural etiquette**.

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/ai-travel-planner.git
cd ai-travel-planner
2️⃣ Create a Virtual Environment
bash
Copy code
python -m venv venv
source venv/bin/activate   # For Linux / Mac
venv\Scripts\activate      # For Windows
3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Set Up Environment Variables
Create a .env file in the project root and add your keys:

ini
Copy code
GOOGLE_API_KEY=your_google_api_key
5️⃣ Run the App
bash
Copy code
streamlit run app.py
🔑 API Keys Required

🌟 Future Enhancements
🌐 Multi-language support

🗺️ Interactive map integration

💾 Save and share itineraries

📍 Real-time weather updates

🚌 Local transport suggestions

🤝 Contributing
Contributions are welcome!



