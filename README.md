# 🌤️ Weather Dashboard

A weather tracking & forecasting application built with React, TypeScript, and Tailwind CSS.

## 1. Features
- **City Search** - Look up the weather for any city in the world
- **Geolocation** - Automatically detect your current location
- **Current Weather** - Temperature, feels like, humidity, wind speed, pressure
- **24-Hour Chart** - Visualize hourly temperature with Recharts
- **7-Day Forecast** - Preview the weather for the entire week
- **Dark Mode** - Switch between light/dark mode
- **Remember City** - Automatically load the last city when reopening
- **Fully Responsive** - Works smoothly on mobile, tablet, and desktop
- **Beautiful Effects** - Gradient backgrounds and smooth transitions


## 2. Used Technologies 

- **React 19** - UI library
- **TypeScript** - Ensures type safety
- **Tailwind CSS 3** - Utility-first CSS framework
- **Recharts** - Responsive charting library
- **Axios** - HTTP client
- **Lucide React** - Beautiful and lightweight icon set
- **WeatherAPI.com** - Weather data API
- **Vite** - Fast build tool

## 3. Getting Started

### Requirements

- Node.js 18+
- npm or yarn
- API key from WeatherAPI.com (free)

### Installation

```bash
# Clone repository
git clone https://github.com/nbv9704/weather-dashboard.git
cd weather-dashboard

# Install dependencies
npm install

# Create .env file from template
cp .env.example .env

# Open .env and add API key
# VITE_WEATHER_API_KEY=your_api_key_here

# Run development server
npm run dev

# Build for production
npm run build
```

### Get API Key

1. Visit [WeatherAPI.com](https://www.weatherapi.com/signup.aspx)
2. Sign up for a free account
3. Copy the API key from the dashboard
4. Paste it into the `.env` file

## 📸 Screenshots

### Light Mode
![Light Mode](screenshots/light-mode.png)

### Dark Mode
![Dark Mode](screenshots/dark-mode.png)

### Current Weather
![Current Weather](screenshots/current-weather.png)

### 24-Hour Temperature
![24-Hour Temperature](screenshots/24-hour-temperature.png)

### 7-Day Forecast
![7-Day Forecast](screenshots/7-day-forecast.png)

### City Search
![City Search](screenshots/city-search.gif)

### Current Location
![Current Location](screenshots/current-location.gif)

## 4. Knowledge 

### a. API Integration

- Integrate RESTful API with Axios
- Handle async/await and error handling
- Environment variables with Vite
- Rate limiting and caching strategies

### b. TypeScript Best Practices

- Strict typing with interfaces
- Generic custom hooks
- Type-safe API responses
- Union types and optional properties

### c. React Patterns

- Custom hooks for reusable logic
- Component composition
- Props drilling management
- State management with useState and useEffect

### d. Data Visualization

- Recharts integration
- Responsive charts
- Custom tooltips and styling
- Real-time data updates

### e. User Experience

- Geolocation API
- LocalStorage persistence
- Dark mode implementation
- Loading states and error handling
- Responsive design with Tailwind

## API Usage

The application uses **WeatherAPI.com** with the following endpoints:

- **Forecast API** - Current weather + 7 days
- **Search API** - City search
- **Free tier**: 1,000,000 calls/month