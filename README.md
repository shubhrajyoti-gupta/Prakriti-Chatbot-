# 🌿 Prakriti-Chatbot

An **AI-powered Ayurvedic chatbot** that determines a user’s **Prakriti** (body constitution) through an interactive, step-by-step questionnaire.  
The bot processes user inputs, analyzes Ayurvedic keywords, and delivers **personalized Prakriti assessment** results along with a **visual pie chart**.

---

## ✨ Key Features
- **Interactive Conversation Flow** – Engages the user with a set of predefined Ayurvedic questions.
- **Natural Language Processing (NLP)** – Splits and analyzes user responses for Ayurvedic keywords.
- **Dynamic Question Navigation** – Proceeds to the next question until the questionnaire is complete.
- **Automated Scoring System** – Calculates **Vata**, **Pitta**, and **Kapha** percentages based on responses.
- **Data Visualization** – Displays results in a **pie chart** for easy interpretation.
- **Accurate & Personalized** – Uses a curated Ayurvedic dataset for precise classification.

---

## 🛠 Tech Stack
- **Language**: Python
- **Libraries**: `matplotlib`, `nltk`/`re` (for keyword processing), `tkinter`/CLI for interaction
- **Paradigm**: Modular, Object-Oriented Structure
- **Dataset**: Ayurvedic keyword-based classification

---

## 🧠 How It Works
1. **Start the Chatbot**  
   The bot greets the user and begins the Ayurvedic questionnaire.
   
2. **Collect Responses**  
   User inputs are captured and split into keywords for analysis.
   
3. **Keyword Matching**  
   The bot matches words against a **predefined Ayurvedic dataset**.
   
4. **Score Calculation**  
   A management module calculates the **Vata**, **Pitta**, and **Kapha** percentages.
   
5. **Result Display**  
   At the end of the questionnaire, the chatbot displays:
   - Percentage breakdown of Prakriti types
   - A visual **pie chart** of results

---

## 📂 Project Structure
    Prakriti-Chatbot/
    ├── dataset/ # Ayurvedic keywords and mappings
    ├── chatbot.py # Main chatbot logic
    ├── management.py # Percentage calculation logic
    ├── visualization.py # Pie chart display
    ├── requirements.txt # Dependencies
    └── README.md


---

## 🚀 Getting Started
1. **Clone the Repository**
   ```bash
   git clone <repo-link>
   cd Prakriti-Chatbot
Install Dependencies

```bash
pip install -r requirements.txt
Run the Chatbot
```
```bash

python chatbot.py
```
📈 **Future Enhancements**
Integration with speech recognition for voice-based interaction.

Enhanced NLP model for more accurate keyword detection.

Web and mobile app versions with modern UI.

Expanded dataset for more detailed Ayurvedic profiling.

🎯 **Skills Demonstrated**
Natural Language Processing

Python Programming

Data Visualization

Modular & OOP Design

Domain Knowledge in Ayurveda
