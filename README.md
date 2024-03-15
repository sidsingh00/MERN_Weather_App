# MERN Stack Weather App

This is a simple weather application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to search for the current weather conditions of a specific location.

## Features

- **Current Weather:** View the current weather conditions including temperature, humidity, wind speed, and weather description.
- **Search Functionality:** Users can search for weather information of any location.
- **Responsive Design:** The application is designed to be responsive and works well on various devices and screen sizes.

## Technologies Used

- MongoDB: Database for storing user data.
- Express.js: Backend framework for handling HTTP requests and routing.
- React.js: Frontend library for building user interfaces.
- Node.js: JavaScript runtime environment for running server-side code.
- OpenWeatherMap API: API for fetching weather data.
- HTML/CSS: Markup and styling for the frontend.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB Atlas account (or local MongoDB installation).

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/mern-weather-app.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd mern-weather-app
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Set up environment variables:**

   Create a `.env` file in the root directory and add the following:

   ```plaintext
   REACT_APP_API_KEY=your_openweathermap_api_key
   ```

   Replace `your_openweathermap_api_key` with your OpenWeatherMap API key.

5. **Start the development server:**

   ```bash
   npm start
   ```

6. **Visit `http://localhost:3000` in your browser to view the application.**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing weather data API.

Feel free to customize it further to fit your project's specific details and requirements.
