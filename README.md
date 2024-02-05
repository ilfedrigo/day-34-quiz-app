# QuizzApp

On my 34 day of coding in Python I make a QuizzApp!

It's a simple quiz application that allows you to test your knowledge with a set of true/false questions from opentdb.com. 

## Functionalities

### 1. Quiz Initialization
- The `main.py` file initializes the quiz by fetching a set of 10 true/false questions from the Open Trivia Database using the provided `data.py` file.
- Each question is loaded into the `question_bank` as a `Question` object.

### 2. Quiz Execution
- The `QuizBrain` class in `quiz_brain.py` manages the flow of the quiz.
- The user interface is created using `ui.py`, which utilizes the Tkinter library for a simple and intuitive design.

### 3. User Interface
- The user interface features a themed layout with a score label, question display area, and true/false buttons.
- The score label keeps track of the user's progress throughout the quiz.
- The question text is dynamically updated as the user progresses through the quiz.

### 4. Answer Validation
- User responses are checked for correctness using the `check_answer` method in `QuizBrain`.
- Feedback is provided to the user by changing the background color of the question display area to green for correct answers and red for incorrect ones.

### 5. Progress Tracking
- The user is informed of their final score upon completing the quiz.
- The application provides a visually appealing experience, with green and red backgrounds indicating correct and incorrect answers, respectively.

### 6. User Interaction
- The true/false buttons allow users to easily submit their answers, creating an interactive and engaging quiz-taking experience.

## Usage

1. Run `main.py` to start the quiz.
2. Answer each true/false question by clicking the corresponding button.
3. Receive immediate feedback on the correctness of your answers.
4. Complete the quiz and view your final score.
