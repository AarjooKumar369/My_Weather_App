# My Weather App
***
Welcome! This is a weather dashboard app built with Next.js and React that helps users track weather info for multiple cities. It connects to the OpenWeatherMap API to show real-time weather details in a simple, responsive interface.

***
## **Demo**

[![View Demo](https://img.shields.io/badge/View-Demo-blue)](https://www.youtube.com/watch?v=Ks_8CHJqJqo)

***
## **Features**
### **Main Features**
- Current Weather Conditions: Get detailed reports of the current weather, including temperature, weather conditions, and more.
- Local Time Display: Shows the exact local time at the searched location.
- Air Quality Index (AQI): Stay informed about the air quality of your chosen location with the AQI feature.
- Humidity and Rain Forecast: Understand the chance of precipitation and humidity levels with just a click.
- Dynamic Backgrounds: The UI changes to reflect the current weather conditions, enhancing the user experience.
- Favorites: Save and remove your favorite locations for quick weather checks.
- Responsive Design: My Weather App looks great on any device, whether it's your phone, tablet, or desktop.

### **Extra Features**
- Weather animations and icons to make the data visually appealing.
- Smooth transitions and effects for better user experience.
- 5-day forecast for a longer view of upcoming weather.
- Temperature toggle between Celsius and Fahrenheit.
- Auto-refresh for up-to-date weather without needing a manual refresh.
- Autocomplete when searching for cities.

***
## Technical Choices
- HTML/CSS: Used for structuring and styling the application.
- JavaScript: Powers the dynamic interactions and handles API integration.
- Vue.js: Provides reactive components to make the UI more interactive.
- Font Awesome: Supplies icons for a clean, modern look.
- Moment.js: Manages time display, making it easier to format timestamps.
- jQuery: Simplifies DOM manipulation.
- Bootstrap: Ensures the app is responsive and easy to style.
- Git: Tracks version history for better collaboration and version control.
- GitHub Pages: Deploys the application, making it accessible online.
- Webpack: Bundles the code, optimizing it for production.
- Babel: Transpiles JavaScript for better browser compatibility.
- Figma: Assists in design and prototyping to plan the UI effectively.

***
## Getting Started



### Prerequisites
To get started, ensure you have the following installed:

- **Node.js** (latest stable version)
- **NPM** or **Yarn**

### Setup
Follow these steps to set up and run the app:

1. **Clone the repository**:

   ```bash
   git clone [repository URL]

2. **Go to the project folder**:

   ```bash
   cd weather-dashboard

3. **Install the necessary packages**:

   ```bash
   npm install

4. **Run the app**:
   ```bash
   npm run dev

***
## Assumptions
- We assume city names are unique for this app.
- Celsius is the default temperature unit.
- Free tier of OpenWeatherMap is enough for regular use.

***
## Trade Offs
- Limited the forecast to 5 days due to API limitations.
- Focused on core error handling to meet time constraints.

***
## Improvements

