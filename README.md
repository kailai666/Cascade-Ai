# Cascade-Ai
CascadeAI India is a zero-build, single-file web application that transforms live weather data into actionable decision-support intelligence across 57 national city nodes. Designed for rapid deployment and high availability, it provides localized climate-risk monitoring without requiring complex backend infrastructure.


# 🌍 CascadeAI India
### 🌦️ A National Climate-Risk Intelligence Network

**Turning live weather data into connected climate intelligence.**

CascadeAI India is a web-based climate intelligence platform designed to make weather conditions and regional climate risks easier to explore, understand, and compare across India.

By combining live weather data, a calculated Weather Risk Index (WRI), interactive visualisations, city-level analysis, route information, and an AI-powered conversational assistant named **Mitra**, CascadeAI transforms weather information into an interactive national intelligence experience.

---


## 🔴 Live Demo

🚀 **Explore CascadeAI India live!**

Experience the interactive climate-risk intelligence dashboard, explore weather conditions across 57 Indian city nodes, view risk visualisations, discover national rankings, and interact with Mitra AI.

🌐 **[Launch CascadeAI India — Live Website](https://kailai666.github.io/Cascade-Ai/)**

---

## 🌱 About the Project

Climate conditions can vary significantly across cities and regions. Understanding these changes requires more than checking individual weather forecasts.

**CascadeAI India** brings multiple layers of weather and risk information together in one platform.

The current prototype monitors **57 city nodes across India**, connecting live weather observations with a calculated risk index and modelled regional relationships.

Our goal is to make climate-related information more accessible, interactive, and easier to interpret.

---

## 🚀 Key Features

### 🗺️ 1. Live India Risk Map
Explore monitored cities across India through an interactive national map.

- 📍 View 57 monitored city nodes.
- 🌡️ Explore city-level weather and risk information.
- 🎨 Identify risk levels through colour-coded markers.
- 🔄 Select a city to update the context across the platform.

### 🌦️ 2. Weather & Risk Intelligence
Get a detailed view of the selected city's weather conditions and calculated risk.

- 🌡️ Temperature and apparent temperature.
- 💧 Relative humidity.
- 💨 Wind conditions.
- ☁️ Current weather conditions.
- 📊 Calculated Weather Risk Index.
- 🔎 Dominant contributing risk factor.

### 📈 3. City Risk Graph
Understand how a city's calculated risk changes over time.

- 🕒 Ten-hour risk trend.
- 📊 Hourly risk visualisation.
- 🌦️ Uses available hourly forecast information.
- 🔄 Updates according to the selected city.

### 🕸️ 4. National Cascade Network
Explore the relationships between monitored city nodes through a national network visualisation.

- 🌐 Visual representation of 57 city nodes.
- 📍 Geographic and regional relationships.
- 🎯 City-level risk states.
- 🔗 Modelled connections between locations.

### 🏆 5. National Risk Ranking
Compare monitored cities using their current calculated WRI.

- 📊 National city ranking.
- 🚨 Identify comparatively elevated risk levels.
- 🔍 Explore city-wise risk information.
- 🔄 Select a city directly from the ranking.

### 🤖 6. Mitra — AI Copilot
Meet **Mitra**, the conversational assistant powering the CascadeAI experience.

Mitra helps users explore weather and risk information using natural-language questions.

Ask Mitra things like:

- 💬 "What is the weather in Delhi?"
- 🌡️ "What is Mumbai's current risk?"
- ⚖️ "Compare Delhi and Mumbai."
- 🚨 "Which city has the highest risk?"
- 🔎 "What is causing Delhi's risk?"
- 🛣️ "Route from Delhi to Jaipur."
- 🕸️ "What does the cascade network show?"

🎙️ The interface also supports browser-based speech input where available and optional speech output.

### 🛣️ 7. City-to-City Route Engine
Explore road routes between supported city nodes.

- 📍 Select starting and destination cities.
- 🗺️ Display routes on an interactive map.
- 🚗 Retrieve road-route information using OSRM.
- 🌦️ View calculated risk context for route endpoints.

---

## ⚙️ How CascadeAI Works

CascadeAI follows a connected data-processing workflow:

1. 🌍 **City Registry:** Maintains geographic information for 57 monitored city nodes.
2. 🌦️ **Weather Retrieval:** Fetches weather information from configured external providers.
3. 🔄 **Data Processing:** Associates retrieved weather information with the corresponding city.
4. 📊 **Risk Calculation:** Calculates the Weather Risk Index using available weather inputs.
5. 🗺️ **Visualisation:** Displays the resulting information through maps, graphs, rankings, and network views.
6. 🤖 **AI Interaction:** Mitra interprets the available application state and communicates relevant information in natural language.

The implementation also includes batched weather retrieval, persistent weather caching, and rate-limit-aware request handling to improve reliability.

---

## 📊 CascadeAI Weather Risk Index (WRI)

The **Weather Risk Index (WRI)** is CascadeAI's calculated risk score, represented on a scale of **0–100**.

It provides a consistent way to compare the weather-related risk state of monitored cities.

WRI supports:

- 📍 City-level risk interpretation.
- 🎨 Risk-band visualisation.
- 🏆 National risk ranking.
- 📈 Hourly risk trends.
- 🗺️ Map-based risk indicators.
- 🤖 Mitra's risk explanations.

The WRI is a CascadeAI-calculated metric, not an official government warning or meteorological classification.

---

## 🤖 Mitra — Intelligence Behind the Interface

Mitra is the conversational copilot integrated into CascadeAI India.

Instead of manually navigating every dashboard module, users can ask questions and explore the available national weather and risk information through natural language.

Mitra is designed to make climate intelligence more accessible, understandable, and interactive.

**One platform. Multiple perspectives. One intelligent assistant.**

---

## 🧰 Technology Stack

| Technology | Purpose |
|---|---|
| 🧱 HTML5 | Application structure |
| 🎨 CSS3 | Interface design and responsive styling |
| ⚡ JavaScript | Application logic and interactions |
| 🌦️ Open-Meteo | Primary weather data integration |
| ☁️ wttr.in | Alternate weather data provider |
| 🗺️ Leaflet | Interactive maps |
| 🌍 Basemap providers | Geographic map rendering |
| 🛣️ OSRM | Road-route retrieval |
| 🎙️ Browser Speech APIs | Speech input and output |
| 🔤 Google Fonts | Typography |

---

## 🔌 Data Sources & Integrations

CascadeAI brings together external services to power its features:

- 🌦️ **Open-Meteo** — Weather data retrieval.
- ☁️ **wttr.in** — Alternate weather provider.
- 🗺️ **Leaflet** — Interactive map rendering.
- 🌍 **OpenStreetMap and applicable basemap providers** — Geographic map data.
- 🛣️ **OSRM** — Road-route retrieval.
- 🎙️ **Browser Speech APIs** — Voice interaction where supported.
- 🔤 **Google Fonts** — Typography.

---

## 🔭 Future Scope

CascadeAI is designed with opportunities for further development and expansion.

Potential future improvements include:

- 🛰️ Integration of satellite-derived environmental information.
- 🌱 Agricultural and soil-data integration.
- 🌧️ More detailed rainfall and climate analysis.
- 📍 Expansion of geographic coverage.
- 📊 Historical weather and risk analysis.
- 🌐 More detailed regional climate-risk modelling.
- 🚨 Integration of verified emergency information feeds.
- 🗣️ Expanded multilingual interaction through Mitra.
- ⚡ Improved backend infrastructure for shared data caching and scheduled updates.

---

## 👥 Contributors

### 🏛️ Team FSNotAi — IIT Dharwad

Built with dedication by our team:

| Contributor | Role |
|---|---|
| 👨‍💻 **Kailai** | Project Contributor |
| 👨‍💻 **Saptarshi** | Project Contributor |
| 👨‍💻 **Sushrut** | Project Contributor |

**Team FSNotAi | IIT Dharwad**

---

## 📄 License

This project is licensed under the **MIT License**.

You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the conditions of the MIT License.

See the [`LICENSE`](LICENSE) file for the complete license text.

---

## 🙏 Acknowledgements

Special thanks to the developers and maintainers of the open-source libraries and external services that support this project:

- 🌦️ Open-Meteo
- ☁️ wttr.in
- 🗺️ Leaflet
- 🌍 OpenStreetMap
- 🛣️ OSRM
- 🔤 Google Fonts
- 💻 The open-source developer community

---

### 🌏 CascadeAI India
**From live weather to connected climate intelligence.**

🚀 *Built by Team FSNotAi | IIT Dharwad*


