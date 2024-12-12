# TuneClime - Weather Based Music Player

**TuneClime** is an interactive weather-based music player that curates songs based on the current weather conditions of your location. Whether it's a sunny afternoon, a rainy evening, or a snowy morning, TuneClime sets the perfect soundtrack for the mood.

## 🌟 Features

- **Real-Time Weather Integration**: Fetches live weather data using an API.
- **Dynamic Playlists**: Automatically plays songs that match the current weather conditions.
- **Location-Based**: Detects your location for weather updates or lets you search for other cities.
- **User-Friendly Interface**: Smooth and responsive UI built with ReactJS.
- **Customizable**: Add your own playlists or integrate music streaming platforms.

## 🚀 Tech Stack

- **Frontend**: ReactJS, HTML, CSS, JavaScript
- **Weather API**: OpenWeatherMap API (or any preferred weather API)
- **Music API**: Spotify API / YouTube Music API for dynamic playlists

## 🛠️ Installation and Setup

Follow these steps to set up and run TuneClime on your local machine:

### Prerequisites
- Node.js and npm installed on your system
- API keys for weather and music services (OpenWeatherMap, Spotify, etc.)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/TuneClime.git
   cd TuneClime
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env` file in the root directory and add your API keys:
   ```env
   REACT_APP_WEATHER_API_KEY=YOUR_OPENWEATHERMAP_API_KEY
   REACT_APP_MUSIC_API_KEY=YOUR_MUSIC_API_KEY
   ```

4. **Run the Application**
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## 🎵 How It Works

1. **Weather Detection**: The app fetches weather data based on your current location or searched city.
2. **Weather Mapping**: The weather data (e.g., sunny, rainy, cloudy) is mapped to a playlist category.
3. **Dynamic Music**: The app fetches and plays curated songs for that weather condition.

| Weather Condition | Music Playlist Category |
|--------------------|-------------------------|
| Sunny             | Happy, Upbeat           |
| Rainy             | Calm, Acoustic          |
| Cloudy            | Chill, Lo-Fi            |
| Snowy             | Soft, Melancholic       |
| Stormy            | Intense, Energetic      |

## 🌐 API References
- [OpenWeatherMap API](https://openweathermap.org/api)
- [Spotify Web API](https://developer.spotify.com/documentation/web-api/)
- [YouTube Data API](https://developers.google.com/youtube/v3)

## 📸 Screenshots
1. **Homepage**: Weather display and song recommendations.
2. **Search**: Search for weather and music by city.
3. **Now Playing**: Music player displaying the current track.

![TuneClime UI](https://via.placeholder.com/600x400.png?text=TuneClime+Screenshot)

## 🤝 Contributing
Contributions are welcome! If you'd like to enhance TuneClime:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeatureName`
3. Commit your changes: `git commit -m "Add some feature"`
4. Push to the branch: `git push origin feature/YourFeatureName`
5. Submit a pull request.

## 📝 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgments
- **OpenWeatherMap** for weather data
- **Spotify/YouTube API** for music recommendations
- ReactJS community for powerful frontend tools

---

**TuneClime - Music in Harmony with the Weather 🌤️🎶**
