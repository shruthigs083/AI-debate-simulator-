# 🤖🔥 AI Debate Club

An interactive AI-powered debate application where users can challenge an AI opponent on different topics. Choose your side, present your arguments, and let Google Gemini argue the opposite side with creative and engaging responses.

## 📌 Project Overview

AI Debate Club is a conversational debate platform developed using Python and Streamlit, integrated with Google's Gemini API.

Users can enter any debate topic, select whether they want to argue **For (Pro)** or **Against (Con)**, and compete against an AI debater that automatically takes the opposing position.

The application maintains a debate transcript so users can follow the conversation as it progresses.

## ✨ Features

- **Custom Debate Topics:** Enter any topic to start a debate.
- **Choose Your Side:** Select Pro or Con before beginning.
- **AI-Powered Arguments:** Google Gemini generates arguments opposing the user's selected position.
- **Interactive Conversations:** Exchange multiple arguments with the AI.
- **Debate History:** Maintains the conversation transcript using Streamlit session state.
- **Simple User Interface:** Clean and interactive interface built with Streamlit.
- **Dynamic AI Responses:** Generates responses based on the debate topic and conversation history.

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Frontend / UI:** Streamlit
- **AI Integration:** Google Gemini API
- **AI Model:** Gemini 2.5 Flash
- **Environment Management:** python-dotenv
- **API Integration:** Google Gen AI SDK
- **Session Management:** Streamlit Session State

## ⚙️ How It Works

1. The user enters a debate topic.
2. The user selects a side: Pro or Con.
3. The application generates instructions for the AI to argue the opposite side.
4. The user submits an argument.
5. The argument and debate instructions are sent to the Gemini API.
6. Gemini generates a counterargument.
7. The conversation is stored in session state.
8. The debate transcript displays both user and AI arguments.

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or later
- Google Gemini API key
- pip package manager

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

```bash
cd AI-Debate-Club
```

### 3. Install Dependencies

```bash
pip install streamlit python-dotenv google-genai
```

### 4. Configure Environment Variables

Create a `.env` file in the project root directory:

```env
GOOGLE_API_KEY=your_gemini_api_key
```

Replace `your_gemini_api_key` with your actual Google Gemini API key.

**Important:** Never upload your `.env` file or expose your API key on GitHub. Add `.env` to `.gitignore`.

### 5. Run the Application

```bash
streamlit run app.py
```

Open the local URL displayed in your terminal to start debating!

## 📂 Project Structure

```text
AI-Debate-Club/
│
├── app.py
├── .env
├── .gitignore
└── README.md
```

## 💡 Example

**Debate Topic:** Should artificial intelligence replace human teachers?

**Your Side:** Pro

**Your Argument:** AI can provide personalized learning experiences to every student.

**AI Side:** Con

**AI Response:** Human teachers offer emotional intelligence, mentorship, and real-world understanding that AI cannot fully replace!

## 🎯 Learning Outcomes

Through this project, I explored:

- Integrating Google's Gemini API into a Python application.
- Building interactive applications using Streamlit.
- Managing conversation history using session state.
- Working with environment variables to protect API credentials.
- Creating dynamic AI-powered conversational experiences.
- Designing prompt instructions for role-based AI responses.

## 🔮 Future Enhancements

- Add multiple AI debaters with different debating styles.
- Introduce debate scoring and argument evaluation.
- Add speech-to-text and text-to-speech functionality.
- Implement topic suggestions and debate categories.
- Add a winner prediction system.
- Improve conversation memory and structured chat history.

## 👩‍💻 Author

**Shruthi G S**

- GitHub: [shruthigs083](https://github.com/shruthigs083)
- LinkedIn: [Shruthi G S](https://www.linkedin.com/in/shruthigs083/)
- LeetCode: [Shruthigs](https://leetcode.com/u/Shruthigs/)

---

⭐ If you find this project interesting, feel free to explore the repository!
