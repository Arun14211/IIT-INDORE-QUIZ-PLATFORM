
# QuizLab - Interactive Quiz Platform

An interactive, responsive quiz platform developed using HTML, CSS, and JavaScript.

Created as a project for the IIT Indore Programming Club.

## Live Demo

[Click here to try QuizLab](https://arun14211.github.io/IIT-INDORE-QUIZ-PLATFORM/)

## Features

- Two quiz categories: Programming Basics and General Knowledge
- Three difficulty levels: Easy, Medium, and Hard
- 10 multiple-choice questions per quiz
- 20-second countdown timer for each question
- Automatic progression when a question's timer expires
- Automatic submission when the final question's timer expires
- Randomized question order
- Randomized answer options
- Negative marking system
- Previous and Next navigation
- Question progress indicator
- Final score and accuracy calculation
- Detailed answer review
- Restart quiz functionality
- Local leaderboard using browser localStorage
- Responsive design for desktop and mobile devices

## Marking Scheme

| Answer | Marks |
|--------|-------|
| Correct | +4 |
| Incorrect | -1 |
| Unanswered | 0 |

Maximum score: 40 marks per quiz.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Browser Local Storage

## How to Use

1. Open the live website.
2. Select Programming Basics or General Knowledge.
3. Enter your name.
4. Select a difficulty level.
5. Click Start Now.
6. Answer each question within 20 seconds.
7. Submit the quiz or wait for automatic submission.
8. View your score and review your answers.
9. Open the leaderboard to see saved scores.

## Project Structure

```text
IIT-INDORE-QUIZ-PLATFORM/
|
|-- index.html
|-- README.md
```

## How to Run Locally

1. Download or clone this repository.
2. Open index.html in a modern web browser.
3. Start taking quizzes.

No additional installation is required.

## Leaderboard Storage

The leaderboard uses browser localStorage.

Scores persist across page refreshes in the same browser but are not shared between different users or devices.

## Future Improvements

- Shared online leaderboard using a backend
- User authentication
- Admin dashboard for adding questions
- More quiz categories
- Customizable quiz duration

## Author

IIT Indore Student

## Purpose

This project demonstrates frontend web development concepts, including DOM manipulation, event handling, timers, scoring logic, randomized questions, and browser storage.
