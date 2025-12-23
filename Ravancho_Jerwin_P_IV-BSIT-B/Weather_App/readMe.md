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

Weather Condition Mapping: Uses a custom getWeatherEmoji() function to map weather condition IDs (e.g., 200 for Thunderstorm, 800 for Clear) to appropriate icons.

Dynamic DOM Updates: Weather details are generated and updated dynamically within the main card container.