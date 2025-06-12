# Workout Timer

A customizable workout timer built with React. Easily calculate workout durations based on exercise type, sets, speed, and break length. Includes sound feedback and a toggle for sound effects.

## Features

- Select workout type and number of exercises
- Adjust number of sets, speed (seconds per exercise), and break duration
- Real-time calculation of total workout time
- Sound feedback with toggle option
- Responsive and modern UI

## Getting Started

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/workout-timer.git
   cd workout-timer
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

### Running the App

Start the development server:
```sh
npm start
```
The app will open at [http://localhost:3000](http://localhost:3000).

### Building for Production

To build the app for production:
```sh
npm run build
```

## Project Structure

- `src/App.js` – Main app component, manages state and renders UI
- [`src/Calculator.js`](src/Calculator.js) – Workout duration calculator component
- [`src/ToggleSounds.js`](src/ToggleSounds.js) – Button to toggle sound effects
- `src/index.js` – Entry point
- `src/index.css` – Styles

## Customization

You can add or modify workout types in the `workouts` array in [`src/App.js`](src/App.js).

