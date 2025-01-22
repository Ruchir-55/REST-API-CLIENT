# REST-API-CLIENT

*COMPANY* : CODTECH IT SOLUTIONS 

*NAME* : RUCHIR SUKHATANKAR

*INTERN ID* : CT08KKY

*DOMAIN NAME* : JAVA PROGRAMMING

*BATCH DURATION* : JANUARY 10th, 2024 to FEBRUARY 10th, 2024

*MENTOR NAME* : NEELA SANTOSH KUMAR

*DESCRIPTION OF TASK PERFORMED* :

The Weather App is a Java-based application that provides users with real-time weather information for a specified location. It fetches weather data from an external API and displays it in a graphical user interface (GUI). Users can enter a location, and the app retrieves and presents weather details, including temperature, weather condition, humidity, and wind speed. This documentation outlines the project's architecture, technologies used, and the functionality of each class within the application.

HttpGet Request: We create an HttpGet request to send a GET request to the OpenWeatherMap API using the city name and API key.

HTTP Client Setup: We configure the HTTP client with timeouts and execute the request.

JSON Parsing: The response is in JSON format. We use the Jackson library to parse the JSON and extract the relevant weather information (temperature, humidity, wind speed, etc.).

Structured Output: After parsing the response, the program outputs the weather details in a readable format.

