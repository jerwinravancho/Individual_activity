# Individual_activity
Weather App, Calculator App, Stopwatch, Currency_App

🌦️ Weather App

A modern and user-friendly weather application that displays real-time atmospheric information using the OpenWeatherMap API. This project showcases the use of asynchronous JavaScript, dynamic DOM manipulation, and responsive CSS design.

✨ Features

Real-Time Weather Data: Displays current temperature, humidity, and weather conditions.

Dynamic Visual Feedback: Weather-based emojis and gradient backgrounds that adapt to current conditions.

Error Handling: Handles invalid or empty city inputs gracefully with visual feedback and animations.

Responsive Interface: Utilizes Flexbox and clamp() for optimal viewing on both mobile and desktop devices.

🛠️ Technical Overview
📡 API Integration

The application fetches live weather data from the OpenWeatherMap API using the fetch method with async/await, ensuring smooth and non-blocking user interactions.

🧠 Core Logic

Data Destructuring: Extracts required values from the API’s nested JSON response efficiently.

🔢 Calculator App

A modern web-based calculator featuring a glassmorphism interface with soft pastel gradients and smooth interactions. This project demonstrates clean JavaScript logic combined with responsive and visually appealing CSS design.

✨ Features

Glassmorphism UI: Semi-transparent calculator body with blur effects for a modern look.

Instant Calculations: Performs real-time arithmetic operations.

Responsive Grid Layout: A 4-column button layout built with CSS Grid that adapts well to different screen sizes.

Interactive Buttons: Smooth hover and click animations for improved user experience.

Keyboard Accessibility: Visible focus states for better accessibility.

🎨 Interface Design

The calculator follows a minimal and modern design approach:

Background: Soft pastel gradient (#dbeafe → #ede9fe) for a clean appearance.

Calculator Body: Translucent white with blur effects to create a glass-like feel.

Buttons: Rounded-square buttons with subtle shadows for depth.

Accent Colors:

Purple–blue gradient for operators

Green gradient for the plus (+) button

Typography: Uses the Poppins font for a clean and modern look.

🛠️ Technical Overview
🧠 JavaScript Logic

The calculator uses simple and effective functions:

appendToDisplay(value) – Appends numbers and operators to the display.

calculate() – Evaluates the mathematical expression and displays the result.

clearDisplay() – Resets the display for a new calculation.

💄 CSS Techniques Used

Glassmorphism: Achieved using backdrop-filter: blur() and transparency.

CSS Grid: Creates a consistent and responsive button layout.

clamp() Function: Ensures responsive text sizing on the display.

Transitions & Transforms: Provides smooth hover and active animations.

⏱️ Stopwatch

A modern, high-accuracy stopwatch built with Vanilla JavaScript, featuring a glassmorphism interface and a soft blue–purple color theme. The application delivers precise time tracking with a smooth, responsive user experience across devices.

✨ Features

Millisecond Precision: Tracks time accurately down to the hundredth of a second.

Accurate Timekeeping: Uses Date.now() to minimize timing drift and maintain consistency even during performance fluctuations.

Modern UI: Glass-style container with smooth hover animations and subtle depth effects.

Responsive Design: Uses Flexbox and clamp()-based typography for optimal display on mobile, tablet, and desktop screens.

Clear Visual Controls: Color-coded buttons for Start (purple), Stop (red), and Reset (green) actions.

🛠️ Technical Overview
🧠 Timing Logic

The stopwatch uses a reliable, non-drifting time calculation approach:

Start Time: Captures the timestamp when the Start button is pressed.

Elapsed Time: Continuously calculates the difference between Date.now() and the stored start time.

Time Formatting:

Hours, minutes, seconds, and milliseconds are calculated using Math.floor and the modulo (%) operator.

Values are formatted using .padStart(2, "0") to maintain a consistent 00:00:00:00 display.

🎨 Styling & User Experience

Glassmorphism Design: Achieved through transparency, blur effects, and soft shadows.

Gradient Background: A subtle blue–purple gradient enhances visual depth.

Interactive Feedback: Buttons feature hover scaling and shadow effects for a responsive feel.

Modern Typography: Uses the Poppins font for improved readability and a clean, contemporary look.

💱 Currency Converter Web App
📌 Project Description

This project is a simple Currency Converter Web Application built using HTML, CSS, and JavaScript. It allows users to convert an amount from one currency to another using real-time exchange rates fetched from a public API.

⚙️ Features

Converts currencies in real time

Automatically loads available currencies into dropdown lists

Uses live exchange rates from open.er-api.com

Simple and user-friendly interface

🛠️ Technologies Used

HTML

CSS

JavaScript (Fetch API)

Exchange Rate API (open.er-api.com)

🚀 How It Works

When the page loads, the app fetches currency data using USD as the base currency.

All available currencies are added to the From and To dropdown menus.

The user enters an amount and selects currencies.

When the Convert button is clicked, the app fetches the latest exchange rate and displays the converted amount.

Weather Condition Mapping: Uses a custom getWeatherEmoji() function to map weather condition IDs (e.g., 200 for Thunderstorm, 800 for Clear) to appropriate icons.

Dynamic DOM Updates: Weather details are generated and updated dynamically within the main card container.
