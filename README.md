# INTERACTIVE-QUIZ-APPLICATION

*Company*: CODTECH IT SOLUTIONS

*Name*: G Sai Jaswanth

*Intern ID*:CT06DY237

*Domain*: Java Programming

*Duration*:6 weeks

*Mentor*:NEELA SANTOSH

##Description:

*Platform*: Eclipse

Task 2: REST API Client - Weather Data Fetcher Application**

This Java application serves as a REST API client that consumes weather data from a public API and presents it in a structured, user-friendly format. The program demonstrates core concepts of web service consumption, HTTP request handling, JSON response parsing, and data presentation - all essential skills for modern Java developers working with web services and APIs.

**Technical Implementation:**
The application utilizes Java's built-in `HttpURLConnection` class to establish HTTP connections with the Open-Meteo weather API, a free public service that provides comprehensive meteorological data without requiring API key authentication. The implementation follows RESTful principles by making a GET request to the API endpoint configured with specific parameters for London's geographical coordinates (latitude: 51.5074, longitude: -0.1278).

The program requests current weather metrics including temperature in Celsius, apparent temperature (feels-like), relative humidity percentage, precipitation levels, weather condition codes, and wind speed measurements. The API response is received in JSON format, which the application then parses using custom string manipulation techniques to extract specific data points without relying on external JSON parsing libraries.

**Key Features and Functionality:**
The application features robust error handling mechanisms that manage potential network issues, HTTP errors, and data parsing exceptions. It includes configurable timeout settings (10 seconds for both connection and read operations) to prevent indefinite hanging when the API service is unresponsive. The data extraction method intelligently locates JSON key-value pairs and retrieves the corresponding values using substring operations and pattern matching.

The user interface presents the weather information in a clean, structured format with appropriate emojis for visual enhancement and clear section separators. The output includes location information, temperature readings (actual and feels-like), humidity percentage, wind speed, and acknowledges the data source. The application runs as a standalone Java program with a main method entry point, making it easily executable in any Java environment.

**Educational Value:**
This implementation provides hands-on experience with several important Java concepts including network programming, exception handling, string manipulation, and API integration. It demonstrates how to work with RESTful services, process JSON responses, and create presentable output formats. The code maintains good programming practices with proper commenting, method separation, and error management, serving as an excellent learning resource for understanding web API consumption in Java applications.

The solution effectively meets all task requirements by successfully consuming a public REST API, handling HTTP requests, parsing JSON responses, and displaying the data in a structured format suitable for end-users seeking current weather information.

#OUTPUT:
<img width="867" height="323" alt="Image" src="https://github.com/user-attachments/assets/6be40621-bd4f-4938-93e0-b780269f953d" />
