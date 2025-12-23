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