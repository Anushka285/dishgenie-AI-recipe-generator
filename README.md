# 🍽️ Dish Genie

🚀 AI-Powered Recipe Generator using Flask + OpenRouter GPT

**Dish Genie** is an AI-powered recipe generation web application built with Flask and OpenRouter GPT models that transforms simple ingredients into personalized cuisine-based recipes in seconds.

🔗 Live Demo: https://recipe-genie-zqak.onrender.com

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Flask](https://img.shields.io/badge/Flask-WebApp-black)
![OpenRouter](https://img.shields.io/badge/OpenRouter-GPT-orange)
![Render](https://img.shields.io/badge/Deployment-Render-purple)
---

## ✨ Features

- 🤖 AI-powered recipe generation from custom ingredients
- 🍝 Cuisine-specific recipe personalization
- 📄 Dynamic prompt engineering using PDF recipe context
- 🎨 Interactive Flask-based web interface
- 🪄 Animated genie-themed loading experience
- 🌐 Cloud deployment using Render
- 🔁 Regenerate recipes instantly
- 📱 Clean and responsive user experience

---

## 🛠️ Tech Stack

- Python
- Flask
- HTML5
- CSS3
- OpenRouter API
- GPT-4o-mini
- PyPDF2
- Render
- Jinja2 Templates

---

## 🤖 How It Works

1. User enters ingredients and selects cuisine + difficulty.
2. Flask backend processes the request.
3. Recipe PDFs are parsed and used as contextual inspiration.
4. Prompt is sent to GPT-4o-mini through OpenRouter API.
5. AI generates a unique recipe in real time.
6. Result is displayed through an interactive UI.

---

## 📁 Project Structure

```bash
Dish-Genie/
│
├── static/                  # Static assets
│   ├── genie_loading.png
│   ├── ingredients_background.png
│   └── logo.png
│
├── templates/               # HTML templates
│   ├── index.html
│   ├── landing.html
│   └── result.html
│
├── indian_recipes.pdf       # Recipe PDFs
├── italian_recipes.pdf
├── mexican_recipes.pdf
│
├── app.py                   # Main Flask application
├── requirements.txt         # Python dependencies
├── .gitignore                 
├── .gitattributes
├── README.md
```

---

## 📸 Application Preview

### 🏠 Landing Page
<img width="1675" height="968" alt="image" src="https://github.com/user-attachments/assets/6d393e90-9a22-4c87-8553-cbbe96bb716f" />

### 🍳 Recipe Generator
<img width="1791" height="965" alt="image" src="https://github.com/user-attachments/assets/3f2a17ce-70bc-4c25-b295-6c35c2f98984" />

### ✨ Generated Recipe
<img width="1809" height="965" alt="image" src="https://github.com/user-attachments/assets/83585b0f-5466-4cb0-9420-d4532f0d36c5" />

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/dishgenie-AI-recipe-generator.git
cd dishgenie-AI-recipe-generator
```

---

### 2️⃣ Create Virtual Environment (Optional)

```bash
python -m venv venv
```

#### Activate Environment

##### Windows
```bash
venv\Scripts\activate
```

##### macOS/Linux
```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Add Environment Variables

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_openrouter_api_key
```

---

### 5️⃣ Run the Application

```bash
python app.py
```

Visit:

```bash
http://localhost:5000
```

---

## 🌐 Deployment on Render

### Steps

1. Push project to GitHub
2. Go to https://render.com
3. Click **New → Web Service**
4. Connect your GitHub repository
5. Configure:

```bash
Runtime: Python 3
Build Command: pip install -r requirements.txt
Start Command: gunicorn app:app
```

6. Add environment variables
7. Deploy 🚀

---

## 🧠 AI Workflow

Dish Genie uses:
- Prompt engineering
- Context injection using recipe PDFs
- GPT-4o-mini via OpenRouter API
- Session-based recipe regeneration
- Dynamic cuisine customization

The application combines static culinary knowledge with real-time AI generation to create unique recipes for users.

---

## 🚀 Future Enhancements

- Ingredient image recognition
- Voice-based cooking assistant
- User authentication and saved recipes
- Nutrition and calorie analysis
- Personalized meal planning
- Multi-language recipe generation
- Recipe rating and recommendation system

---

Enjoy cooking with **Dish Genie** 🍳✨
