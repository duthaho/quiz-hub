# Quiz Hub

Quiz Hub is a fun and interactive single-page web application designed to help users test and improve their knowledge on various topics, with an initial focus on MySQL Indexing. Built with HTML, Tailwind CSS, and vanilla JavaScript, it offers a clean, dark-themed interface and engaging features.

**Live Demo:** [https://duthaho.github.io/quiz-hub/](https://duthaho.github.io/quiz-hub/)

## Features

* **Interactive Quizzes:** Engage with multiple-choice questions on different subjects.
* **Progress Tracking:** Your quiz scores and completion status are saved in `localStorage`, so you can pick up where you left off.
* **Favorite Quizzes:** Mark quizzes as favorites to prioritize them on the main screen.
* **Sorted Quiz List:** Quizzes are displayed with favorites first, then completed quizzes, and finally uncompleted ones.
* **Question Shuffling:** Questions are randomized each time you start or retake a quiz for a varied experience.
* **Instant Feedback:** See your score immediately after completing a quiz.
* **Confetti Celebration:** Enjoy a fun confetti animation upon quiz completion!
* **Detailed Explanations:** Review questions with correct answers and explanations to learn from your attempts.
* **Sound Effects:** Subtle sound effects for user actions (can be muted).
* **Responsive Design:** Optimized for various screen sizes, from mobile to desktop.
* **SEO Friendly:** Includes basic meta tags for better search engine visibility.

## Current Quiz Topics

* MySQL Indexing (Comprehensive)

## How to Use / Run

1.  **Clone the repository (optional):**
    ```bash
    git clone [https://github.com/duthaho/quiz-hub.git](https://github.com/duthaho/quiz-hub.git)
    cd quiz-hub
    ```
2.  **Open `index.html`:** Simply open the `index.html` file in your web browser to run the application locally.
    * No build steps or complex setup required!

## Technologies Used

* **HTML5:** For the basic structure of the application.
* **Tailwind CSS:** For styling the user interface, loaded via CDN.
* **Vanilla JavaScript:** For all application logic and interactivity.
* **Tone.js:** For sound effects, loaded via CDN.
* **canvas-confetti:** For the quiz completion celebration animation, loaded via CDN.
* **localStorage:** For persisting user progress and preferences.

## Main Screen Features

* **Quiz Cards:** Displays available quizzes.
    * **Unattempted Quizzes:** Show the quiz title and a preview of the first question with its options. A "Start Quiz" button initiates the quiz.
    * **Attempted/Completed Quizzes:** Show the quiz title, the user's score (percentage, correct/incorrect count), and buttons to "See Explanations" or "Retake Quiz".
* **Favorite Icon (Heart):** Allows users to mark/unmark quizzes as favorites.
* **Mute/Unmute Icon:** Controls sound effects for user actions.
* **GitHub Link Icon:** Links to this repository.

## Quiz Flow

1.  **Select a Quiz:** From the main screen, click "Start Quiz" on an unattempted quiz card or "Retake Quiz" on a completed one.
2.  **Answer Questions:**
    * Questions are presented one by one.
    * Select an answer for the current question.
    * The "Next" button (or "Finish Quiz" on the last question) is enabled only after an answer is selected.
    * Navigate with "Previous" and "Next" buttons.
3.  **View Results:**
    * Upon finishing, your score, a feedback message, and a summary of correct/incorrect answers are displayed.
    * A confetti animation celebrates your completion.
    * Options to "Try Again", "See Explanations", or go "Back to Quiz List" are available.
4.  **Review Explanations:**
    * If "See Explanations" is chosen, you can navigate through each question.
    * Your selected answer and the correct answer are highlighted (green for correct, red for your incorrect choice).
    * A detailed explanation for each question is provided.

## Author

* **duthaho**
* GitHub: [https://github.com/duthaho](https://github.com/duthaho)
* Project Homepage: [https://duthaho.github.io/quiz-hub/](https://duthaho.github.io/quiz-hub/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details (if you add one).
