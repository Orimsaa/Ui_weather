# WeatherAQI Sense — Modern Web Dashboard

> Real-time Thailand weather and air quality monitoring web dashboard featuring high-precision GIS 77-province interactive mapping and live Doppler rain radar overlay.

## ✨ Features
- 🗺️ **High-Precision 77-Province GIS Mapping**:
  - Official boundary polygon outlines for all 77 Thai provinces.
  - Mathematically calculated geometric centroids (Green's theorem) ensuring 100% accurate pin placement inside each province.
  - Inverted national boundary mask dimming neighboring countries to emphasize Thailand.
  - Bidirectional hover and click linking between map polygons and province markers.
- 🌧️ **Live Doppler Weather Radar Overlay**:
  - Real-time precipitation radar powered by RainViewer API (Thai Meteorological Department & satellite composite).
  - Floating radar controller with Play/Pause animation looping through past 2-hour rain movement.
  - Timeline scrubber and precipitation intensity color scale (light green ➔ yellow ➔ orange ➔ red/purple thunderstorm).
- 🌡️ **Comprehensive Weather & Air Quality Metrics**:
  - Current temperature, feels-like, humidity, wind direction & gusts, UV index, and dew point.
  - Color-coded US AQI scale with PM2.5, PM10, O3, NO2, SO2, and CO pollutant breakdowns.
  - 24-hour hourly weather forecast and 7-day extended outlook.
  - Smart lifestyle indices (running, laundry, car wash, sunscreen recommendations).
- 🌐 **Bilingual & Responsive Design**:
  - Full Thai and English language support.
  - Clean Material 3 / Google Weather glassmorphism aesthetics.
  - Fully responsive across desktop, tablet, and mobile browsers.

## 🛠️ Tech Stack
- **Framework**: Next.js 16 (App Router + Turbopack) + React 19 + TypeScript
- **Styling**: Tailwind CSS + Lucide React Icons
- **GIS / Mapping**: Leaflet.js, GeoJSON (77 Provinces Boundary & Thailand National Boundary), Esri Light Gray Canvas & OpenStreetMap tiles
- **APIs**: OpenWeatherMap API, IQAir AirVisual API, RainViewer Doppler Radar

## 🚀 Getting Started

### 1. Install Dependencies
```bash
npm install
# or
pnpm install
```

### 2. Run Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### 3. Production Build
```bash
npm run build
npm run start
```

## 📄 License
MIT License
