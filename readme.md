 
Online Quiz System – README

Project Description
The Online Quiz System is a Java-based application that allows multiple users to take quizzes simultaneously. The quiz includes a variety of question types, such as multiple-choice and true/false questions. The project uses Java Swing for the GUI, inheritance for managing different types of questions, exception handling, and file handling.

Key Features:
•	Multiple-choice and true/false questions.
•	Score tracking and display.
•	Navigation through questions with "Next" and "Back" buttons.
•	Simple, user-friendly GUI with automatic question display.
•	Final score display upon quiz completion.

Prerequisites
•	Java JDK 8 or higher
•	Swing library (included in the Java Development Kit)
•	Java compiler (Javac)

How to Run the Project
1.	Download/Clone the Repository: Download the code or clone the repository into your local machine.
2.	Compile the Java Files: Navigate to the directory where the Mini.java file is located. Run the following command to compile the program:
bash
Copy code
javac Mini.java
3.	Run the Application: After successful compilation, run the program using the command:
bash
Copy code
java Mini
4.	Using the Application:
o	Upon launching, the home page will appear with options to start the quiz.
o	During the quiz, select answers and navigate between questions using the Next and Back buttons.
o	The score will be updated as you progress, and the final score will be shown when the quiz ends.



Project Structure
•	Question Class (Abstract): The base class for all types of questions.
o	MultipleChoiceQuestion: Extends Question to handle multiple-choice questions.
o	TrueFalseQuestion: Extends Question to handle true/false questions.
•	QuizManager Class: Manages quiz operations like adding questions, scoring, and handling navigation.
•	HomePageGUI Class: Creates the home page with options to start the quiz or exit the application.
•	QuizGUI Class: Displays the quiz questions and manages user interaction during the quiz.

Classes and Methods Overview:
•	Question (abstract class):
o	getQuestionText(): Retrieves the question text.
o	checkAnswer(String answer): Checks if the provided answer is correct.
•	MultipleChoiceQuestion (inherits Question):
o	Handles multiple-choice questions with multiple options.
•	TrueFalseQuestion (inherits Question):
o	Handles true/false questions.
•	QuizManager:
o	addSampleQuestions(): Loads predefined sample questions into the quiz.
o	getCurrentQuestionIndex(): Returns the index of the current question.
o	getScore(): Returns the current score.
o	nextQuestion(), previousQuestion(): Navigates through questions.
•	HomePageGUI:
o	Provides the home page with a start quiz button.
•	QuizGUI:
o	Displays quiz questions and handles user interaction during the quiz.

Sample Questions:
1.	What is the capital of France?
2.	Which planet is known as the Red Planet?
3.	The earth is the third planet from the Sun (True/False).
4.	Water boils at 100 degrees Celsius (True/False).

Future Enhancements
•	Add support for custom quizzes.
•	Add user authentication for tracking individual scores.
•	Improve question navigation and include time-based scoring.

Author
This project was developed as part of a learning exercise to implement Java concepts such as inheritance, inner classes, exception handling, packages, threading, Collection API, and file handling.
Enjoy the quiz!



 

 

 
 
