# 🌦️ Weather App Project -- Instructions

## 🎯 Objective

Build a **Weather App** using **HTML, CSS, and JavaScript** to practice your web development basics.

## 📝 Requirements

### 0. General Rules

- Use **vanilla HTML, CSS, and JavaScript** (no frameworks).
- All code files must include **comments** explaining key sections.
- Validate all user inputs (e.g., prevent empty city searches).
- Display a friendly error message if the weather cannot be loaded.
- Include a short **README** with setup instructions and features.

### 1. HTML (Structure)

- Create a search box where users can enter a **city name**.
- Add a button to fetch the weather.
- Display the following information for the searched city:
    - City name
    - Temperature
    - Weather condition (e.g., sunny, cloudy, rainy)
    - An icon/image representing the weather.

### 2. CSS (Styling)

- Style the app to make it visually appealing.
- Use proper layout (center the content, add spacing, colors, and background).
- Make sure the app looks good on both desktop and mobile (basic responsiveness).

### 3. JavaScript (Functionality)

- Use **JavaScript** to:
    - Capture the city name from the input.
    - **Fetch weather data using the [OpenWeatherMap API](https://openweathermap.org/api)** (required).
        - You must register for a free API key.
        - Use the [Current Weather Data API](https://openweathermap.org/current).
    - Display the weather information in your HTML.
- Add basic error handling (e.g., if the city is not found or there is a network error).

### 4. Bonus (Optional for extra marks)

- Show the current **date and time**.
- Change the background depending on the weather (e.g., sunny → bright, rainy → dark).
- Use **localStorage** to save the last searched city.

## 📂 Project Structure

    weather-app/
    │── index.html
    │── style.css
    │── script.js

## 📌 Submission Guidelines

- Submit your project as a zipped folder or upload it to GitHub.
- Make sure your code is well-indented and commented.
- Include a short **README** file explaining how your app works and how to run it.

# 🌦️ Weather App -- Marking Scheme (100%)

## 1. **HTML (Structure) -- 25 marks**

- [5] Proper HTML boilerplate (doctype, head, body, etc.)
- [5] Input field for city + search button included
- [10] Correct display sections for city, temperature, weather condition, and icon
- [5] Semantic HTML usage

## 2. **CSS (Styling) -- 25 marks**

- [10] General styling (colors, font, spacing, alignment)
- [5] Layout well-structured and visually clear
- [5] Responsiveness (desktop & mobile)
- [5] Creativity (backgrounds, hover effects, nice design choices)

## 3. **JavaScript (Functionality) -- 35 marks**

- [10] Captures user input and triggers search
- [10] **Fetches data from OpenWeatherMap API using your own API key**
- [10] Updates the DOM dynamically with weather details
- [5] Error handling (wrong city, empty input, API/network errors)

## 4. **Code Quality -- 5 marks**

- [3] Code indentation and readability
- [2] Meaningful variable/function names

## 5. **Extra Features (Bonus) -- up to 10 marks**

- [5] Shows date & time or saves last searched city
- [5] Dynamic backgrounds/icons based on weather condition

------------------------------------------------------------------------

# ✅ Total = 100 marks

- **Pass mark**: 50
- **Good score**: 70+
- **Excellent**: 85+
