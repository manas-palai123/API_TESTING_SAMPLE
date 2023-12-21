# API Testing Example: OpenWeatherMap

This example demonstrates API testing using the OpenWeatherMap API and Postman.

## Overview

This example involves testing the OpenWeatherMap API to retrieve weather information for a specific city.

## Prerequisites

- Postman installed ([Download Postman](https://www.postman.com/downloads/))
- OpenWeatherMap API Key ([Sign up](https://openweathermap.org/) to obtain an API key)

## Steps

1. **Obtain API Key:**
   - Sign up on the [OpenWeatherMap website](https://openweathermap.org/) to get an API key.

2. **Create Postman Request:**
   - Open Postman and create a new request.
   - Set the request type to `GET`.

3. **Set API Endpoint:**
   - Set the request URL to the OpenWeatherMap API endpoint:
     ```
     https://api.openweathermap.org/data/2.5/weather
     ```

4. **Add Query Parameters:**
   - Add query parameters, including the city name and your API key. For example:
     ```
     ?lat={put_yur_lattitude}&lon={put_your_longitude}&appid={YOUR_API_KEY}
     ```
     Replace `YOUR_API_KEY` with the obtained API key.
     Do not add curly braces while adding the required input

5. **Send Request:**
   - Click on the "Send" button to execute the request.

6. **Inspect Response:**
   - Examine the response for HTTP status code, headers, and response body.

## Example Request

- **Method:** GET
- **Endpoint:**
