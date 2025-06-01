# 🥗 AI Powered Calorie Tracker and Nutrient Assistant

An interactive AI-based nutrition assistant that logs your meals and returns calorie and nutrient information using natural language queries. It uses OpenAI for language processing and APIs like **Nutritionix** and **USDA** for food data.

---

## 🔧 Features

- 🧠 Natural language meal logging (`"I ate 2 bananas and a coffee"`)
- 🔍 AI-powered food analysis using **LangChain + OpenAI**
- 🍽 Calorie & macronutrient breakdown from **Nutritionix** and **USDA**
- 🎨 Interactive UI via **Gradio**
- 📝 Supports real-time chatbot logging

---

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

### Sample `requirements.txt`

```
openai
langchain
gradio
python-dotenv
requests
```

---

## 🔑 Setup API Keys

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_openai_key
NUTRITIONIX_APP_ID=your_nutritionix_app_id
NUTRITIONIX_API_KEY=your_nutritionix_api_key
USDA_API_KEY=your_usda_api_key
USDA_API_URL=https://api.nal.usda.gov/fdc/v1/foods/search
```

🔗 Get your API keys from:
- [OpenAI](https://platform.openai.com/account/api-keys)
- [Nutritionix](https://developer.nutritionix.com/)
- [USDA](https://fdc.nal.usda.gov/api-key-signup.html)

---

## 🚀 How to Run

### Option 1: Jupyter Notebook

Open `AI Powered Calorie Tracker and Nutrient Assistant.ipynb` and run the cells step by step.

### Option 2: Script

Convert notebook to `.py` and run:

```bash
python app.py
```

---

## ⚠ Troubleshooting

### ❌ OpenAI Quota Error

```
openai.RateLimitError: Error code: 429 - 'You exceeded your current quota...'
```

✅ Fix by:
- Checking [OpenAI Usage](https://platform.openai.com/account/usage)
- Adding billing info: [OpenAI Billing](https://platform.openai.com/account/billing/overview)

---

### ⚠ LangChain Deprecation Warning

```
LangChainDeprecationWarning: LangChain agents will continue to be supported...
```

You can ignore this for now or optionally explore [LangGraph](https://langchain-ai.github.io/langgraph/).

---

## 📁 Project Structure

```
📦project-root
 ┣ 📜AI Powered Calorie Tracker and Nutrient Assistant.ipynb
 ┣ 📜README.md
 ┣ 📜.env
 ┣ 📜requirements.txt
```

---

## 🙋‍♂️ Author

**Bhuvan M**  
_Maharaja Institute of Technology, CSE-AI Dept._

---

