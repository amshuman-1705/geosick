# GeoSick: AI-Powered Environmental Health Intelligence

**Translating complex environmental and health data into clear, actionable insights to help users understand potential health risks around them.**

---

## 🌍 Overview

GeoSick is an AI-powered web application designed to explore the relationship between environmental conditions and public health.

The application combines interactive geographic visualization, generative AI, environmental analysis, health utilities, and location-based information to provide users with a unified platform for exploring potential health risks and wellness information.

GeoSick uses a client-side architecture with browser storage for demonstration purposes, allowing the application to run without a traditional backend database.

---

## 🚀 Key Features

### 1. Interactive 3D Globe Explorer

* **3D Globe:** Explore locations around the world using an interactive globe powered by `react-globe.gl`.
* **Location Exploration:** Select locations on the globe to view environmental and health-related information.
* **City Health Insights:** Generate location-specific health information using AI-powered analysis.
* **Location Search:** Search for locations and navigate directly to them on the globe.
* **Geographic Visualization:** Visualize environmental and health information through an interactive geographic interface.

### 2. AI Analysis Suite

* **📸 Area Scan:** Upload an image of an environment and use AI to identify potential environmental health concerns.
* **📜 Prescription Reader:** Analyze prescription images and extract relevant medication information.
* **🩺 Symptom Checker:** Describe symptoms using text or voice and receive AI-generated informational guidance.
* **🧠 Mental Wellness Check-in:** Complete a wellness questionnaire and receive supportive AI-generated feedback.

### 3. Health Intelligence

* **HealthCast:** Provides location-based health information using factors such as air quality, UV exposure, pollen, and vector activity.
* **Health Alerts:** Displays relevant environmental and health-related alerts.
* **Facility Finder:** Helps users locate nearby hospitals, clinics, and pharmacies.

### 4. Personal Health Utilities

* **💧 Water Log:** Track daily water consumption and set personal hydration goals.
* **Activity History:** Maintain a local history of previous AI analyses.
* **Profile Management:** Manage user information and application settings.
* **Browser Notifications:** Support for browser-based reminders and notifications.

### 5. Advanced UI/UX

* **AI Assistant:** An interactive AI assistant capable of answering health-related questions and helping users navigate the application.
* **Voice Interaction:** Support for voice input and output using browser APIs.
* **Multilingual Interface:** Support for multiple languages.
* **Responsive Design:** Designed to work across desktop and mobile screen sizes.

---

## 🛠 Technical Architecture

GeoSick is built using a modern frontend technology stack.

### Frontend

* **React 19**
* **TypeScript**
* **Vite**
* **Tailwind CSS**

### Artificial Intelligence

* **Google Gemini API**
* **`@google/genai` SDK**
* Gemini models for text and multimodal analysis
* AI-powered image and environmental analysis
* Search-grounded AI capabilities where supported

### Visualization

* **react-globe.gl**
* **Three.js**

### Data & Browser APIs

* **localStorage** for client-side persistence
* **Web Speech API** for voice interaction
* **Geolocation API** for location-based features
* **Notification API** for browser notifications

---

## 📦 Installation & Setup

### Prerequisites

Make sure you have the following installed:

* Node.js v18 or higher
* npm
* A Google Gemini API key

### 1. Clone the Repository

```bash
git clone https://github.com/amshuman-1705/geosick.git
cd geosick
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory:

```env
API_KEY=your_actual_google_gemini_api_key
```

> **Important:** Never commit your `.env` file or expose your API key publicly.

### 4. Start the Development Server

```bash
npm run dev
```

The application will normally be available at:

```text
http://localhost:5173
```

---

## 🔐 Demo Mode

GeoSick currently uses browser-based storage for demonstration purposes.

User information, application settings, and activity history may be stored locally in the browser.

For security reasons, authentication credentials and API keys should not be stored directly in the public README or source repository.

---

## ⚠️ Medical Disclaimer

**GeoSick is an informational application powered by Artificial Intelligence.**

The information provided by the application is not a substitute for professional medical advice, diagnosis, or treatment.

* Always consult a qualified healthcare professional regarding medical conditions.
* Do not delay or avoid professional medical care based on information provided by this application.
* AI-generated information may be incomplete or inaccurate.
* In an emergency, contact your local emergency services immediately.

---

## 📄 License

This project is available under the **MIT License**.

---

## 👨‍💻 Project

**GeoSick — AI-Powered Environmental Health Intelligence**

Built using React, TypeScript, Vite, Tailwind CSS, Google Gemini, and modern web technologies.
