# Weather App

A Flutter-based weather application that provides real-time weather information and forecasts for cities worldwide. The app features a clean, modern UI and utilizes the WeatherAPI.com service for accurate weather data.

## Features

- **Real-time Weather Data**: Get current weather conditions for any city
- **Hourly Forecasts**: View weather forecasts hour by hour
- **7-Day Forecast**: Detailed weather predictions for the next 7 days
- **Key Weather Metrics**:
  - Temperature (Celsius)
  - Wind Speed (km/h)
  - Humidity (%)
  - Cloud Coverage (%)
  - Chance of Rain
- **Search Functionality**: Easy city search with automatic updates
- **Responsive UI**: Beautiful and intuitive user interface

## Screenshots

<img src="https://user-images.githubusercontent.com/92157668/192311777-d9115d1b-000b-49bc-a713-7ece84cdde57.jpg" width="300" height="600"> <img src="https://user-images.githubusercontent.com/92157668/192311886-fde8576e-5eb5-49e5-b097-86246b58274f.jpg" width="300" height="600">

## Getting Started

### Prerequisites

- Flutter SDK (>=2.16.1 <3.0.0)
- Dart SDK
- WeatherAPI.com API key

### API Setup

1. Create an account on [WeatherAPI.com](https://www.weatherapi.com/)
2. Generate your API key
3. Replace the `apiKey` variable in `lib/screens/home_page.dart` with your API key

### Installation

1. Clone the repository
```bash
git clone [repository-url]
cd weather_app
```

2. Install dependencies
```bash
flutter pub get
```

3. Run the app
```bash
flutter run
```

## Dependencies

- `http`: For making API calls
- `intl`: For date formatting
- `modal_bottom_sheet`: For bottom sheet UI components
- `flutter_weather_app_v2`: Core app package

## Project Structure

- `lib/screens/`
  - `home_page.dart`: Main screen with current weather and hourly forecast
  - `detail_page.dart`: Detailed forecast view
- `lib/components/`
  - `weather_item.dart`: Reusable weather information widget
- `lib/constants.dart`: App-wide constants and configurations

## Features in Detail

### Home Page
- Current weather conditions
- Hourly forecast
- City search functionality
- Key weather metrics display

### Forecast Page
- 7-day weather forecast
- Detailed weather metrics for each day
- Min/Max temperature
- Wind speed and humidity levels

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

