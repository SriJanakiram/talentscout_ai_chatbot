
# TalentScout AI – Interview Screening Chatbot

An AI-powered chatbot built with Gradio and Google Gemini API to automate candidate screening for technical roles.

## 💡 Features
- Collects candidate details: name, email, phone, experience, location, etc.
- Saves responses to a CSV file
- Uses Gemini API to generate 3 technical interview questions per technology in the tech stack
- Conversational chatbot interface built with Gradio

## 🧠 Technologies Used
- Python
- Gradio
- Google Generative AI (Gemini API)
- Pandas
- RegEx

## 🚀 How It Works
1. The chatbot collects candidate details step by step
2. Stores the data in `talentscout_candidates.csv`
3. Sends the tech stack to Gemini to generate questions
4. Displays the questions to the candidate

## 🛠️ Installation

```bash
pip install -r requirements.txt
