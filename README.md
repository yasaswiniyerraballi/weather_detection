# weather_detection
I developed the website using HTML ,CSS,JAVASCRIPT to see website https://codepen.io/02-yashu15/pen/PoBbBGp
Weather Detection App
This is a simple Weather Detection application that allows users to search for current weather conditions of any city by utilizing the OpenWeather API. The app displays the city name, temperature, sky conditions, and wind speed.

Features
Search weather information by entering the name of any city.
Display the temperature in Celsius, weather description, and wind speed.
Handles errors in case of incorrect or non-existent city names.
Technologies Used
HTML
CSS
JavaScript
OpenWeather API
How It Works
The user enters the name of the city in the input field.
Upon clicking the "Submit" button, the application fetches the weather data from the OpenWeather API.
The retrieved data includes the city name, temperature (in Kelvin, which is converted to Celsius), sky conditions, and wind speed.
The weather information is then displayed dynamically on the page.
API Integration
The app uses the OpenWeather API to retrieve weather data. You need an API key to access the service. For this project, the API key is:

makefile
Copy code
API_KEY = "3045dd712ffe6e702e3245525ac7fa38"
Make sure you replace it with your own API key if necessary.

Installation and Setup
To set up the project locally, follow these steps:

Clone the repository or download the files.

Open the project directory and include the following files:

index.html: HTML file containing the structure of the web page.
styles.css: CSS file for styling the page.
app.js: JavaScript file for handling the API calls and updating the DOM.
Add the required API key in the app.js file.

Open the index.html file in a web browser to view and use the application.

Project Structure
Copy code
.
├── index.html
├── styles.css
└── app.js
index.html: Contains the layout of the weather app, including input fields for the city name and display sections for weather details.
styles.css: Contains the styles for the weather app, ensuring the page is visually appealing.
app.js: Handles user interactions, API calls, and updating the page with weather data.
Example Usage
Enter a city name like "New York" in the input box.
Click the "Submit" button.
The app will display the current temperature, weather description, and wind speed for that city.
Error Handling
If the user submits an invalid or empty city name, an alert will be shown to notify the user about the incorrect input.
License
This project is open-source and available for use under the MIT License.

![Screenshot (53)](https://github.com/user-attachments/assets/b3a27aa2-951a-4d4a-8826-047cf8f1cded)

