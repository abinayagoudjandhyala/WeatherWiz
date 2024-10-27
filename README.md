
# WeatherWiz

**WeatherWiz** is a Java-based weather application featuring a user-friendly GUI created with Swing. It retrieves real-time weather data from the OpenWeatherMap API, displaying essential details such as temperature, humidity, wind speed, and UV index for a specified city.

## Features

- **City Search**: Retrieve weather information by entering a city name.
- **Language Selection**: Choose a language for weather descriptions.
- **Weather Details**: View temperature, wind speed, humidity, and UV index.
- **Notifications**: Enable notifications for successful weather data retrieval.
- **Attractive GUI**: Custom rounded text fields and an appealing user interface.

## Installation and Setup

1. **Clone the Repository**: Clone this repository or copy the source code.

   ```bash
   git clone https://github.com/yourusername/WeatherWiz.git
   ```

2. **Replace API Key**: Open the `WeatherWiz` class and replace the `apiKey` variable in the `fetchWeatherData` method with your OpenWeatherMap API key:

   ```java
   String apiKey = "YOUR_API_KEY"; // Replace with your OpenWeatherMap API key
   ```

3. **Compile and Run**: Compile and run the `WeatherWiz` class:

   ```bash
   javac WeatherWiz.java
   java WeatherWiz
   ```

## Usage

1. **Enter City**: Type the city name in the input field.
2. **Select Language**: Choose a language from the dropdown menu (e.g., "en" for English, "es" for Spanish).
3. **Click Search**: Press the **Search** button to fetch and display the weather data.
4. **Enable Notifications**: Check the **Enable Notifications** box to receive a pop-up notification upon successful data retrieval.

## Code Overview

The application is structured as follows:

- **WeatherWiz Class**: Main class extending `JFrame`, responsible for the GUI layout and user interactions.
- **RoundedTextField Class**: Custom JTextField with rounded corners for better aesthetics.
- **API Integration**: Uses OpenWeatherMap API to fetch weather data based on the city name.

### Main Components:

- **Imports**: The necessary Java libraries are imported to create the GUI and handle HTTP connections.
  
- **Constructor**: Initializes the GUI components, sets up layout, and defines the action listeners.

- **Fetch Weather Data**: Retrieves weather data based on user input and updates the UI accordingly.

- **Notification**: Displays notifications based on user preference for data fetching success.

## Requirements

- **Java Development Kit (JDK)**: Version 8 or later.
- **Internet Connection**: Required to fetch data from the OpenWeatherMap API.

## License

This project is licensed under the MIT License.
