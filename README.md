Basic Quiz Game

Project Overview

The Basic Quiz Game is a simple interactive quiz application that asks users a series of questions. It includes a scoring system to evaluate the user's performance and provides feedback on each question. The game is built using Python and Tkinter for the graphical user interface.

Project Objectives

- Build a simple quiz game that asks users a series of questions.
- Implement a scoring system to evaluate the user's performance.
- Enhance user interaction by allowing them to input their answers.
- Reinforce Python fundamentals, including data structures, control flow, and user input handling.
- Gain practical experience in structuring a small Python project.

Requirements and Features

Questions and Options
- The quiz includes at least three questions.
- Each question has multiple-choice options.

Scoring System
- Tracks the user's correct answers.
- Provides feedback on each question, indicating whether the user's answer was correct or incorrect.
- Displays the correct answer if the user is wrong.
- Displays the user's final score at the end of the quiz.

User Input
- Allows users to input their answers using radio buttons.
- Uses appropriate validation to handle user input.

Customization
- The quiz can be easily customized by modifying the questions, options, and correct answers.

Code Structure
- The code is organized into functions and classes for better readability and maintainability.



1. **Install the required dependencies**:
    Ensure you have Python installed. Tkinter is part of the standard Python library, so no additional installations are necessary.

![Screenshot (34)](https://github.com/user-attachments/assets/82ccfb77-3a9f-43c0-8f9c-e9700766bd50)
![Screenshot (35)](https://github.com/user-attachments/assets/a7d94028-804a-48cc-a530-1e0fc4288c0f)
![Screenshot (36)](https://github.com/user-attachments/assets/d0676559-751e-46ea-aa9a-5a1cfce32505)
![Screenshot (37)](https://github.com/user-attachments/assets/49a94f3c-ad80-4065-82a5-90ff05cdfa60)

3. **Run the application**:
    ```sh
    python quiz_game.py
    ```

Customization

To customize the quiz questions, options, and answers, modify the `questions` list in the `QuizGame` class:

```python
self.questions = [
    {
        "question": "What is the capital of France?",
        "options": ["Paris", "London", "Rome", "Berlin"],
        "answer": "Paris"
    },
    {
        "question": "What is 2 + 2?",
        "options": ["3", "4", "5", "6"],
        "answer": "4"
    },
    {
        "question": "What is the capital of Japan?",
        "options": ["Beijing", "Seoul", "Tokyo", "Bangkok"],
        "answer": "Tokyo"
    }
]




