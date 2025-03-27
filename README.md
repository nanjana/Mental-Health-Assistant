# 🧘 Mental Health Assistant

An AI-powered mental health assistant built with **ReactJS** and **Hugging Face NLP models**.  
It detects emotions, sentiment, or toxicity in text input and replies with caring, realistic responses.

> 🧠 Try typing things like:
> - "I feel anxious about tomorrow"
> - "You're useless and dumb"
> - "I'm really proud of myself today"

Demo Link: https://drive.google.com/file/d/1R64GHml7JIBZq4j5YNYMxbhNlYaPxgti/view?usp=drive_link
---

## 🌟 Features

- 💬 Chat-style user interface
- 🧠 Emotion, Sentiment & Toxicity Detection (via Hugging Face)
- 🔄 Dropdown to switch models on the fly
- ❤️ Custom supportive responses based on prediction
- 📱 Responsive, minimal, clean UI

---

## 🛠️ Built With

- **React.js** (Frontend)
- **Hugging Face Inference API**
- CSS for styling
- Axios for API calls

---

## 🤖 Supported Models

| Model                | Hugging Face ID                                      | Purpose               |
|---------------------|-------------------------------------------------------|------------------------|
| Emotion Detection   | `bhadresh-savani/distilbert-base-uncased-emotion`     | Understand emotions    |
| Sentiment Analysis  | `distilbert-base-uncased-finetuned-sst-2-english`     | Detect sentiment       |
| Toxicity Detection  | `unitary/toxic-bert`                                   | Flag toxic language    |

---

## 🚀 Getting Started

### 1. Clone the repo

``` bash
git clone https://github.com/YOUR_USERNAME/mental-health-assistant.git
cd mental-health-assistant
``` 
### 2. Install dependencies
```bash
Copy
Edit
npm install
```
### 3. Add your Hugging Face API key
Open App.js, and replace the placeholder key:

js
Copy
Edit
Authorization: 'Bearer YOUR_HUGGINGFACE_API_KEY',
Get your token here: https://huggingface.co/settings/tokens

### 4. Run the app
```bash
Copy
Edit
npm start
```
