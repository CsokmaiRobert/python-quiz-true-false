# 🤖 Quiz App with Python and Tkinter

This is an interactive quiz app built using Python, Tkinter, and external APIs. It pulls random quiz questions from an API and provides an engaging interface for users to answer. The app evaluates user responses in real time, keeping track of the score and providing feedback on whether the user's answer is correct or not. 

## Features:
- **Real-time Quiz Questions:** Questions are fetched dynamically using an external API (Open Trivia Database).
- **Interactive Interface:** Built with Tkinter for a visually appealing and user-friendly design.
- **Real-time Scoring:** Tracks and displays the user’s score throughout the quiz.
- **Instant Feedback:** Provides immediate feedback with color changes based on correct or incorrect answers.

## How It Works:
1. **Fetch Questions:** The quiz pulls questions using the Open Trivia Database API. 
2. **Display Questions:** Each question is displayed one by one with options to answer "True" or "False."
3. **Check Answer:** The app checks if the user's response is correct, and updates the score.
4. **Finish Quiz:** After all questions are answered, the final score is displayed, and the option to restart the quiz is given.

## 🚀 Tech Stack:
- **Python:** The primary language used to build the quiz.
- **Tkinter:** For creating the graphical user interface.
- **Open Trivia Database API:** Used to fetch questions for the quiz.
- **HTML:** For working with the quiz questions and answers in the backend.

## Installation:
To run the project locally, clone the repository and ensure the required libraries are installed:
```bash
git clone https://github.com/yourusername/quiz-app
cd quiz-app
pip install -r requirements.txt
python main.py
