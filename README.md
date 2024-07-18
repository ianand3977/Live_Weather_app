# Live Weather App

This is a simple live weather app that allows users to check the current weather conditions for any city. The app uses the OpenWeatherMap API to fetch and display weather data.

![image](https://github.com/user-attachments/assets/d494fbd4-7f33-4bc9-9dc4-2304614d8446)

## Features

- Search for a city's weather
- Display temperature, humidity, and wind speed
- Show appropriate weather icon based on current conditions
- Handle errors when the city is not found

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## How to Use

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/weather-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd weather-app
    ```

3. Open `index.html` in your preferred browser.

4. Enter the name of the city you want to check the weather for in the search box and click the search button.

## Project Structure

weather-app/
│
├── images/
│ ├── clouds.png
│ ├── clear.png
│ ├── rain.png
│ ├── drizzle.png
│ ├── mist.png
│ ├── snow.png
│ ├── humidity.png
│ ├── wind.png
│ └── search.png
│
├── style.css
└── index.html

## API Key

The app uses the OpenWeatherMap API to fetch weather data. You need to get an API key from [OpenWeatherMap](https://openweathermap.org/api) and replace the `apiKey` variable in the `index.html` file with your own API key.

```javascript
const apiKey = "YOUR_API_KEY";

Contributing
If you'd like to contribute to this project, please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License.

Make sure to update the repository URL and any other specific information as needed. You can place this `README.md` file in the root of your project directory.
