 🚀 Smart City Management System

A web-based Smart City Management System developed using **React + Vite**, designed to simulate and monitor key urban operations including public transport, smart parking, emergency response, event management, and traffic control.

---

## 📁 Project Structure

smart-city-management/
├── public/ # Static assets
├── src/
│ ├── Dashboard/ # Overview dashboard and city control panels
│ ├── Emergency 1/ # Emergency transport and response system
│ ├── event_manage/ # City event management and scheduling
│ ├── public_transit/ # Real-time cab/train tracking and alerts
│ ├── smart_parking/ # Smart parking availability and tracking
│ ├── traffic_manage/ # Traffic congestion and rerouting
│ ├── Button.jsx # Reusable button component
│ ├── Heading.jsx # Page heading component
│ ├── Leftbar.jsx # Sidebar navigation
│ ├── index.css # Global styles
│ ├── main.jsx # Entry point
├── index.html # Base HTML file
├── package.json # Project metadata and dependencies
├── vite.config.js # Vite configuration
├── .gitignore # Git ignored files
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🌟 Features

- **📍 Public Transit Monitoring**  
  Real-time cab and train tracking using Leaflet.js, with predictive arrival times and service alerts.

- **🅿️ Smart Parking System**  
  Visualizes available parking slots with JSON-based data.

- **🚑 Emergency Management**  
  Simulates emergency vehicle response and hospital/incident mapping.

- **🎪 Event Management**  
  Shows upcoming city events, their venues, and schedules.

- **🚦 Traffic Management**  
  Displays traffic density, rerouting suggestions, and congestion zones.

- **📱 Responsive Design**  
  Optimized for both desktop and mobile browsers using pure CSS and React components.

---

## 🛠️ Tech Stack

- **Frontend:** React (with Vite)
- **Routing/State:** React state hooks
- **Styling:** Vanilla CSS
- **Mapping:** Leaflet.js
- **Data Source:** Local JSON files (no backend)

---

## 🧪 Getting Started

To run the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/CraftsmanSJ/smart-city-management.git

# 2. Navigate into the project directory
cd smart-city-management

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
