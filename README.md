# Live Cricket Scores Application

This is a live cricket scores web application built with **React** that fetches and displays real-time cricket match scores. The app showcases live scores, match status, and other relevant details such as teams playing, current score, and match status

![Uploading Screenshot (64).png…]()




## Features
- Display live cricket match scores.
- Show team logos for both teams.
- Display match status (e.g., match in progress, match ended).
- Interactive and responsive UI using React.
- Mock data for demonstration (can be replaced with real API integration).

## Tech Stack
- **Frontend**: React.js, CSS
- **UI Framework**: Bootstrap (for responsiveness)
- **State Management**: React's `useState` and `useEffect`

## Project Structure

The project structure follows a modular design for maintainability and scalability:


/live-cricket-scores-app │ ├── /public │ ├── index.html # Main HTML file │ └── /assets # Folder for static assets (images, icons) │ ├── /src │ ├── /components # Reusable components like ScoreCard, Header, etc. │ ├── /pages # Pages of the application (LiveScores, Home) │ ├── App.js # Main React component that includes routing and state management │ ├── index.js # Entry point for React app │ └── /styles # Folder for CSS or SCSS files │ ├── package.json # Project dependencies and scripts └── README.md # This README file

markdown
Copy
Edit

### Key Folders and Files:
- **/public**: Contains static files like images, icons, and the `index.html` file where the React app is rendered.
- **/src**:
  - **/components**: Reusable React components that encapsulate UI elements, such as `ScoreCard` and `TeamCard`.
  - **/pages**: React components that represent entire pages or views of the app, such as `LiveScores` and `Home`.
  - **App.js**: The root component that renders all other components and handles application-level logic (e.g., fetching data).
  - **index.js**: The entry point where React renders the `App` component into the DOM.
  - **/styles**: CSS or SCSS files for styling the application.

## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/live-cricket-scores-app.git
   cd live-cricket-scores-app
Install Dependencies: Make sure you have Node.js and npm installed. Then, run the following command to install all necessary dependencies:

bash
Copy
Edit
npm install
Start the Application: After installing the dependencies, start the application with:

bash
Copy
Edit
npm start
The app will now be running on http://localhost:3000 in your browser.
