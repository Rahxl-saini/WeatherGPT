# ⛅ WeatherGPT

WeatherGPT is an AI-powered weather assistant designed to provide intelligent weather insights, climate information, and disaster alerts through a modern, interactive interface. Powered by Google's Gemini API and real-time weather services, it helps users explore weather conditions, understand meteorological patterns, and stay informed about potential weather hazards.

## ✨ Features

- **🧠 AI Weather Assistant:** Ask questions about weather conditions, forecasts, climate patterns, and meteorological phenomena.
- **🗺️ Interactive Weather Map:** Explore locations worldwide using an interactive map built with React Leaflet.
- **🌦️ Real-Time Weather Data:** Retrieve weather information, including temperature, humidity, wind speed, and atmospheric pressure.
- **🚨 Disaster Alerts:** Display public safety and severe weather alerts through the configured disaster-alert integration.
- **🌪️ Interactive 3D Animations:** Experience dynamic Three.js particle effects representing clouds, rain, and tornadoes.
- **🌗 Light & Dark Mode:** Switch between elegant themes with a responsive glassmorphism-inspired interface.
- **📍 Location-Based Weather:** Select map coordinates to explore weather conditions for different locations.
- **📱 Responsive Design:** Enjoy a smooth experience across desktops, tablets, and mobile devices.
- **⚡ Modern Performance:** Built with React 19, Tailwind CSS v4, and Vite for a fast and responsive user experience.

## 🛠️ Tech Stack

- **Frontend:** React 19
- **Build Tool:** Vite
- **Styling:** Tailwind CSS v4
- **AI Integration:** Google Gemini API
- **Interactive Maps:** React Leaflet
- **3D Graphics:** Three.js
- **Weather Data:** Open-Meteo API
- **Reverse Geocoding:** BigDataCloud API
- **Disaster Alerts:** NDMA/SACHET integration
- **HTTP Requests:** Fetch API
- **Package Manager:** pnpm

## 🌐 External API Integrations

### 1. Google Gemini API

- **Purpose:** Powers the conversational AI assistant.
- **Features:** Weather-related question answering, climate explanations, and meteorological insights.
- **Integration:** Uses Google's Generative AI SDK to communicate with the configured Gemini model.

### 2. Open-Meteo API

- **Purpose:** Retrieves weather information for selected geographic coordinates.
- **Data Provided:** Temperature, relative humidity, wind speed, atmospheric pressure, and other supported weather variables.
- **Integration:** Uses HTTP GET requests through the browser's Fetch API.

### 3. BigDataCloud Reverse Geocoding API

- **Purpose:** Converts latitude and longitude into readable location information.
- **Features:** Helps identify cities and localities selected on the interactive weather map.
- **Integration:** Uses HTTP GET requests to retrieve location details.

### 4. NDMA/SACHET Disaster Alerts

- **Purpose:** Integrates public disaster-alert information into the application.
- **Features:** Displays relevant alerts when supported by the configured service.
- **Integration:** Uses the application's configured API proxy to communicate with the alert service.

## 🚀 Getting Started

### Prerequisites

Install the following tools before running the application:

- Node.js
- pnpm
- A Google Gemini API key

### Installation

**1. Navigate to the project directory**

```bash
cd WeatherGPT
```

**2. Install dependencies**

```bash
pnpm install
```

If your project has separate frontend and backend directories, install dependencies in the appropriate directories.

**3. Configure environment variables**

Create a `.env.local` file in the frontend directory:

```env
VITE_GEMINI_API_KEY=your_gemini_api_key_here
```

Use a valid API key and follow Google's current API configuration requirements.

**4. Start the development server**

```bash
pnpm run dev
```

**5. Open the application**

Visit the local URL displayed in your terminal. If your Vite configuration uses port 8443, the application will be available at:

`http://localhost:8443`

## 📁 Key Components

- **AI Chat Interface:** Provides conversational access to weather-related information.
- **Interactive Weather Map:** Allows users to explore geographic locations and weather conditions.
- **Weather Data Integration:** Retrieves supported weather measurements from external services.
- **Disaster Alert Interface:** Presents information returned by the configured alert service.
- **3D Particle System:** Creates animated atmospheric effects using Three.js.
- **Theme Management:** Supports light and dark visual modes.

## 🔮 Future Enhancements

- Extended weather forecasts and historical weather analysis.
- Weather notifications and customizable alert preferences.
- Additional weather map layers and visualization options.
- Saved locations and personalized weather dashboards.
- AI-generated summaries of severe weather conditions.
- Improved accessibility and multilingual support.

## 🤝 Contributing

Contributions, bug reports, and feature requests are welcome. Developers can contribute by improving existing functionality, enhancing the user interface, or adding new weather-related features.

## 📝 License

WeatherGPT can be distributed under the MIT License if the project repository includes the appropriate license file.