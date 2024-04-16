<h1>Weather App GUI</h1>
<h2>Introduction</h2>
<p>
    The Weather App is a Java-based application that provides users with real-time weather information for a specified location. It fetches weather data from an external API and displays it in a graphical user interface (GUI). Users can enter a location, and the app retrieves and 
    presents weather details, including temperature, weather condition, humidity, and wind speed.

<p>
  
</p>

<h2>Technologies Used</h2>
<p>
    The Weather App utilizes the following technologies and libraries:
</p>
<ul>
  <li>Java 18</li>
  <li><a href="https://code.google.com/archive/p/json-simple/downloads">JSON Simple</a> - Used to parse and read through JSON data</li>
  <li>HTTPURLConnection</a>: Java's built-in library for making HTTP requests to fetch data from external APIs.</li>
</ul>

<h2>Class Summaries</h2>

<h3>3.1. AppLauncher</h3>
<p>
    <strong>Description:</strong> The AppLauncher class acts as the entry point for the Weather App, initiating the graphical user interface (GUI) and rendering the main application window.
</p>

<h3>3.2. WeatherAppGui</h3>
<p>
    <strong>Description:</strong> The WeatherAppGui class serves as the graphical user interface (GUI) for the Weather App, responsible for visually presenting weather information tailored to a specified location.
</p>

<h3>3.3. WeatherApp</h3>
<p>
    <strong>Description:</strong> The WeatherApp class encompasses the backend logic responsible for fetching weather data from an external API. It facilitates the retrieval of geographic coordinates corresponding to a given location, fetches weather data pertinent to that location, and offers functionality to convert weather codes into human-readable descriptions.
</p>

