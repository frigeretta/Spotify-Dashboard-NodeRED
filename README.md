# 🎧 Spotify Real-Time Dashboard — Node-RED + Spotify API

Millions of people around the world use music streaming platforms like **Spotify**, where they can enjoy their favorite tracks while their listening analytics are silently tracked in the background. To access this data, users typically wait until the end of the year for **Spotify Wrapped**, which summarizes their listening habits over the past 12 months.

### But what if you didn’t have to wait until the end of the year?

This project was born from the idea of transforming **passive listeners into active participants**. With this real-time dashboard, users can visualize and explore their music habits as they listen. Instead of relying solely on Spotify's annual summary, the dashboard provides **live insights** including:

- 🔝 Top artists
- 🎵 Song trends
- 🎼 Genre distribution
- ⏱ Listening timeline
- 📊 Popularity scores
- 📖 Live lyrics (where available)
- 💿 Album art carousel
- ⏳ Total listening time
- 📍 Interactive analytics UI

When users are actively engaged with their listening habits, they gain deeper awareness of their **mood**, **routines**, and even **personal identity**, helping them stay more connected to the music they love.

---

## 🛠 Built With

- [Node-RED](https://nodered.org/) – Visual programming for IoT and automation
- [Spotify Web API](https://developer.spotify.com/documentation/web-api) – Real-time song, artist, and playback data
- [Chart.js](https://www.chartjs.org/) – For dynamic graph visualizations
- [AngularJS](https://angularjs.org/) – Used within UI templates for custom interactive components
- Custom HTML/CSS – Styled visuals and carousel logic

---

## 🚀 Features

| Component                | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| 🎵 **Now Playing**        | View current song, artist, album, popularity, and duration                 |
| 🖼 **Album Carousel**      | Scrollable shelf of all previously played songs' album covers             |
| 📊 **Listening Timeline**  | Line chart showing when songs are played most (per hour)                  |
| 🧠 **Genre Display**       | Extracts and shows artist genres with stylish tag bubbles                 |
| 📈 **Popularity Gauge**    | Displays current song's popularity score using a color gauge              |
| ⌛ **Listening Time Card** | Aggregates total listening duration since app start                       |
| 🥇 **Top Artists Table**   | Lists most played artists based on historical data                        |
| 🗺️ **Lyrics Viewer**       | Fetches synced lyrics and displays them in real time (where available)    |
---

## 📦 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spotify-dashboard-nodered.git
   cd spotify-dashboard-nodered
