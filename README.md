# Quizlet Web Application

Welcome to Quizlet, a web application built using Next.js. This application allows users to take quizzes on various topics with different levels of difficulty.

## Live Demo

Check out the live version of the project [here](https://quizlet-dmicvizl5-selvabharathi-s-projects.vercel.app/).

## Project Description

Quizlet is a dynamic and engaging web application designed to provide users with an interactive quiz experience. The application offers various categories and difficulty levels, ensuring a personalized and challenging quiz for each user.

### Features

- **Home Page**: 
  - A welcoming interface with a brief introduction.
  - Allows users to configure quiz settings such as category, difficulty, and the number of questions.
  
- **Quiz Settings**:
  - A component where users can choose from a range of categories and difficulty levels.
  - Options for setting the number of questions, ensuring flexibility and customization.

- **Questions Page**:
  - Displays the quiz questions fetched from the Trivia API.
  - Validates user selections for category, difficulty, and question count to ensure a smooth quiz experience.
  - Includes a progress bar and a countdown timer for each question.
  - Provides options to shuffle answers, check selected answers, move to the next question, and show results.

### Design

- **Layout**:
  - The design follows a clean and modern aesthetic with a white background and prominent use of the primary color for headings and buttons.
  - Responsive design ensures the application looks great on both desktop and mobile devices.

- **Home Page**:
  - Features a bold and inviting heading.
  - An image that sets the theme for the quiz.
  - A clear and structured layout with easy navigation to the quiz settings.

- **Quiz Page**:
  - Displays questions in a user-friendly manner.
  - Ensures easy readability and interaction with the quiz content.
  - Uses a countdown timer to add an element of challenge.
  - Shows a progress bar to keep track of quiz progress.
  - Offers feedback on answer selection and updates the score in real-time.

### Technology Stack

- **Frontend**: Built with Next.js for server-side rendering and fast performance.
- **Styling**: Utilizes Tailwind CSS for a consistent and responsive design.
- **API**: Fetches quiz questions from the Trivia API to provide a diverse range of questions.

### Components Overview

- **app/page.tsx**: 
  - The main entry point for the home page.
  - Renders the `QuizSettings` component and an introductory image.

- **app/questions/page.tsx**:
  - Handles fetching quiz questions based on user-selected settings.
  - Validates the settings to ensure they are within the accepted range.
  - Displays the `Questions` component with the fetched data.

- **components/quiz-settings.tsx**:
  - Provides the interface for selecting quiz category, difficulty, and number of questions.

- **components/questions.tsx**:
  - Displays the fetched quiz questions.
  - Includes features such as answer shuffling, progress tracking, score updating, and countdown timer.

- **components/ui/**:
  - Contains reusable UI components like `Button`, `Progress`, `Separator`, and `Toaster`.

- **hooks/useModalStore.ts**:
  - Manages the state for opening and closing modals used in the application.

## Conclusion

Quizlet is designed to be an enjoyable and flexible quiz application, offering users the ability to tailor their quiz experience to their preferences. The use of Next.js ensures high performance and a smooth user experience, while the modern design makes the application visually appealing and easy to use.

For any queries or contributions, feel free to contact the project maintainer or fork the repository and submit a pull request.

Enjoy the quiz!
