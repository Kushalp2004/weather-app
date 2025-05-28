☀️ Modern Weather App

This is a sleek and responsive web-based weather application that provides real-time weather conditions for any city worldwide. Built using pure HTML, CSS, and JavaScript, it offers essential information like temperature, humidity, wind speed, and a descriptive weather summary in a clean, intuitive, and visually appealing interface.

✨ Features

Real-time Weather Data: Fetches and displays current weather conditions by integrating with the OpenWeatherMap API.
Comprehensive Metrics: Provides detailed weather information at a glance:

Temperature (°C)
"Feels Like" Temperature (°C)

Humidity (%)

Wind Speed (KPH)

Concise weather condition description (e.g., "Clear Sky," "Partly Cloudy")

4-Day Forecast: Includes a horizontally scrollable section displaying future daily temperatures and conditions.

Dynamic Visuals: Displays appropriate weather icons based on current conditions, and a custom background image with a captivating glassmorphism effect on the main container enhances the user experience.

Responsive Design: The app's layout is designed to adapt to various screen sizes, ensuring a seamless experience on desktop, tablet, and mobile devices.

Intuitive Interface: A clean design with an easy-to-use search bar allows for quick city lookups.

💻 Technologies Used

HTML5: Structures the core content of the web page.

CSS3: Styles the application, implements responsive design, and creates the unique glassmorphism visual effects.

JavaScript (ES6+): Handles all dynamic functionality, including API calls, data processing, and updating the DOM.

OpenWeatherMap API: Provides the real-time weather and forecast data.

Google Material Symbols: Used for various icons within the app (e.g., search, location, water drop, air).

🚀 Getting Started

Follow these steps to set up and run the Weather App on your local machine.

Prerequisites
A modern web browser (e.g., Chrome, Firefox, Edge).
A text editor or IDE (e.g., VS Code).
An OpenWeatherMap API Key: You'll need to sign up for a free account and obtain an API key.

Installation

Clone the repository:

Bash
git clone https://github.com/<your-username>/weather-discord-bot.git
(Remember to replace <your-username> with your actual GitHub username and weather-discord-bot with your chosen repository name.)

Navigate to the project directory:

Bash
cd weather-discord-bot
API Key Configuration
Open the script.js file in your text editor.
Locate the line defining apiKey:
JavaScript

const apiKey = '123456789'; // Paste here your API key
Replace '123456789' with your actual OpenWeatherMap API key. Security Note: For client-side applications, API keys are exposed. For production environments, consider using a backend proxy to protect your key. For this demo, direct insertion is common practice.

Running the Application

Simply open the index.html file in your web browser. You can typically do this by double-clicking the file in your file explorer.
The application will load, displaying the "Search City" message.

💡 How to Use

Open the index.html file in your web browser.
Type the name of any city into the "Search City" input bar.
Press Enter or click the search icon button.
The app will display the current weather conditions and a 4-day forecast for the entered city. If the city is not found, an appropriate message will appear.

🛠️ Future Enhancements

Geolocation: Implement automatic detection of the user's current location.
Unit Toggle: Add a button to switch between Celsius/Fahrenheit and KPH/MPH.
Advanced Error Handling: Provide more specific error messages for different API issues (e.g., rate limits).
Search History: Store recent city searches for quick access.
More Detailed Forecast: Expand the forecast to include hourly data or more days.
