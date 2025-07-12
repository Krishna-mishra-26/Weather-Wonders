
# Weather Wonders ☀️🌦️

A modern, responsive weather application that provides real-time weather information, forecasts, and air quality data for any location worldwide. Built with vanilla JavaScript and powered by the OpenWeatherMap API.

![Weather Wonders](https://img.shields.io/badge/Weather-App-blue?style=for-the-badge&logo=weather&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## ✨ Features

- 🌍 **Current Weather Display** - Real-time weather data for any city
- 📍 **Geolocation Support** - Automatic location detection
- 🔍 **City Search** - Search and select cities worldwide
- 📊 **5-Day Forecast** - Extended weather predictions
- ⏰ **Hourly Forecast** - 24-hour weather timeline
- 🌬️ **Air Quality Index** - Real-time AQI data with health recommendations
- 🌅 **Sunrise/Sunset Times** - Solar event tracking
- 🗺️ **Google Maps Integration** - Interactive map view
- 📱 **Responsive Design** - Works on all devices
- 🌙 **Dark Theme** - Eye-friendly dark interface
- ⚡ **Fast Performance** - Optimized loading and caching

## 🛠️ Tech Stack

**Frontend:**
- HTML5 - Semantic markup
- CSS3 - Modern styling with custom properties
- Vanilla JavaScript (ES6+) - No frameworks, pure JS
- Google Fonts - Nunito Sans typography

**APIs:**
- OpenWeatherMap API - Weather data
- OpenWeatherMap Geocoding API - Location services
- Google Maps API - Map integration

**Tools:**
- VS Code - Development environment
- Live Server - Local development server

## 🚀 Quick Start

### Prerequisites

- A modern web browser
- Internet connection
- Optional: Live Server extension for VS Code

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Krishna-mishra-26/Weather-Wonders.git
   ```

2. **Navigate to project directory**
   ```bash
   cd Weather-Wonders
   ```

3. **Open with VS Code**
   ```bash
   code .
   ```

4. **Start Live Server**
   - Right-click on `index.html`
   - Select "Open with Live Server"
   - Or use the command: `Live Server: Open with Live Server`

5. **View in browser**
   - Application will open at `http://localhost:5500`

### API Setup

The app uses OpenWeatherMap API. The current API key is included for demo purposes, but for production use:

1. Get your free API key from [OpenWeatherMap](https://openweathermap.org/api)
2. Replace the API key in `assets/js/api.js`:
   ```javascript
   const api_key = "your-api-key-here";
   ```

## 📁 Project Structure

```
Weather_Wonders/
├── index.html              # Main HTML file
├── favicon.svg             # App icon
├── README.md               # Documentation
├── style-guide.md          # Design system
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   ├── js/
│   │   ├── api.js          # API configuration
│   │   ├── app.js          # Main application logic
│   │   ├── module.js       # Utility functions
│   │   └── route.js        # Routing system
│   ├── images/
│   │   ├── logo.png        # App logo
│   │   ├── openweather.png # API attribution
│   │   └── weather_icons/  # Weather condition icons
│   └── font/
│       └── material-symbol-rounded.woff2
```

## 🎨 Design Features

- **Modern UI/UX** - Clean, intuitive interface
- **Custom Color Scheme** - Carefully crafted dark theme
- **Material Icons** - Google Material Design icons
- **Responsive Layout** - Mobile-first design approach
- **Smooth Animations** - CSS transitions and effects
- **Typography** - Nunito Sans font family

## 🌐 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Internet Explorer (limited support)

## 📱 Mobile Compatibility

Weather Wonders is fully responsive and optimized for:
- 📱 Mobile phones (320px+)
- 📺 Tablets (768px+)
- 💻 Desktop (1024px+)
- 🖥️ Large screens (1440px+)

## 🔧 Key Components

### Weather Data
- Current temperature and conditions
- "Feels like" temperature
- Humidity and pressure
- Visibility and wind data
- Weather icons for all conditions

### Air Quality
- PM2.5 concentration levels
- Air Quality Index (AQI) ratings
- Health recommendations
- Color-coded quality indicators

### Location Services
- GPS-based current location
- City search with autocomplete
- Reverse geocoding for coordinates
- International location support

## 🚀 Performance Optimizations

- **Lazy Loading** - Images loaded as needed
- **API Caching** - Reduced redundant requests
- **Optimized Assets** - Compressed images and fonts
- **Efficient DOM Manipulation** - Minimal reflows
- **Async Operations** - Non-blocking API calls

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Krishna**
- Created Weather Wonders with ❤️
- Built using modern web technologies

## 🙏 Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) - Weather data API
- [Google Fonts](https://fonts.google.com/) - Nunito Sans typography
- [Material Icons](https://fonts.google.com/icons) - Icon library
- Weather icons from OpenWeatherMap

## 📞 Support

If you encounter any issues or have questions:
- 🐛 [Report a bug](https://github.com/Krishna-mishra-26/Weather-Wonders/issues)
- 💡 [Request a feature](https://github.com/Krishna-mishra-26/Weather-Wonders/issues)
- 📧 Contact: Krishnamis8634@gmail.com

---

⭐ **Star this repository if you found it helpful!** ⭐
