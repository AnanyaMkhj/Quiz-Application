# Java-Quiz-Application
This is a Java-based Quiz Application that allows users to take a quiz on various topics. The application presents questions to the user, provides multiple-choice answers, and calculates the final score at the end of the quiz.

## Features
10 multiple-choice questions.
15 seconds timer for each question.
"50-50 Lifeline" to eliminate two incorrect options.
Displays the final score at the end of the quiz.
GUI created using Swing.

## Prerequisites
Java Development Kit (JDK) installed (version 8 or higher).

## Code Overview
### Main Components
QUIZ CLASS:
1. Initializes the quiz interface.
2. Contains the main logic for displaying questions, handling user input, and managing the timer.
3. Contains the question and answer data.

SCORE CLASS:
1. Displays the user's final score after the quiz is completed.

### UI Components
JFrame: Main window frame.
JLabel: Used for displaying questions and options.
JRadioButton: Used for multiple-choice options.
ButtonGroup: Groups radio buttons to ensure only one can be selected.
JButton: Used for "Next", "50-50 Lifeline", and "Submit" actions.

### Key Methods
initQuestionsAnswers(): Initializes the questions and answers.
actionPerformed(ActionEvent ae): Handles button click events.
paint(Graphics g): Custom paint method to handle the timer display.
start(int count): Displays the current question and options.

### How to Play
#### Start the Quiz:
Run the application. The first question will be displayed with four options.

#### Select an Answer:
Choose one of the four options by clicking on the radio button.

#### Next Question:
Click "Next" to move to the next question.

#### Use Lifeline:
Click "50-50 Lifeline" to eliminate two incorrect options (can be used only once).

#### Submit Quiz:
After the 9th question, the "Next" button will be disabled and the "Submit" button will be enabled. Click "Submit" to finish the quiz and see your score.

## Customization
#### Adding/Changing Questions:
Modify the questions and answers arrays in the initQuestionsAnswers() method.

#### Adjust Timer:
Change the timer variable value to adjust the time limit for each question.

## License
This project is licensed under the MIT License.

## Acknowledgments
Thanks to the open-source community for the resources and inspiration.
Special thanks to the creators of Java and Swing for providing the tools to build this application.

