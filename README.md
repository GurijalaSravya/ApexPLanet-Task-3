Key Features of this Interactive Quiz:

Dark Theme: The CSS is styled with a dark background (#121212) and light text (#e0e0e0) for a modern dark theme. An accent color (#bb86fc) is used for headings and the next button.
Multiple Questions: The questions array in the JavaScript holds an array of question objects. Each object contains the question text, an array of options, and the correctAnswer. You can easily add more questions to this array.
Dynamic Question Loading: The loadQuestion() function dynamically creates the HTML for the current question and its options based on the questions array.
Interactive Option Buttons: Each option is presented as a clickable button.
Answer Checking: The checkAnswer() function is called when an option button is clicked. It:
Disables all option buttons after an answer is selected.
Highlights the correct answer in green.
Highlights the incorrectly selected answer in red.
Increments the score if the selected answer is correct.
Shows the "Next Question" button if there are more questions, or the results if it's the last question.
"Next Question" Button: This button appears after an answer is selected and loads the next question in the quiz.
Results Display: Once all questions are answered, the quiz container is hidden, and a results section is displayed, showing the user's final score.
"Restart Quiz" Button: This button allows the user to reset the quiz and start over from the first question.
Responsive Design: Media queries are included to ensure the quiz layout adapts well to different screen sizes.
How to Use:

Save this code as an HTML file (e.g., quiz.html).
Open the HTML file in your web browser.
You will see an interactive quiz with the specified questions. Click on the options to answer, and the quiz will guide you through the questions, provide feedback, and display your final score. You can customize the questions in the questions array in the JavaScript to create your own quiz.


Sources
