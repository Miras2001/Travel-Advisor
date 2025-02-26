# Travel Advisor - Hotel, Restaurant, and Attraction Finder

## 📌 Project Overview
This is a **React-based Travel Advisor** application that helps users find **hotels, restaurants, and attractions** near a selected location. The app uses **Google Maps API** for location display and **RapidAPI (or Google Places API)** to fetch data.

---

## 🚀 Features
- 🌍 **Interactive Google Map** with dynamic location updates.
- 🏨 **Fetch and display hotels, restaurants, and attractions** based on user selection.
- 🔍 **Real-time filtering** based on rating and type.
- 📍 **User location detection** using the browser’s geolocation.
- 🔄 **Updates dynamically when the map moves.**

---

## 🛠️ Technologies Used
- **React.js** (Frontend framework)
- **Material-UI** (UI components)
- **Google Maps API** (Maps & Autocomplete)
- **RapidAPI / Google Places API** (Fetching travel data)
- **Axios** (API requests)

---

## 📂 Project Structure
```
📦 travel-advisor-app
├── 📂 public
│   ├── index.html
│   └── favicon.ico
├── 📂 src
│   ├── 📂 components
│   │   ├── Header.jsx
│   │   ├── List.jsx
│   │   ├── Map.jsx
│   │   ├── PlaceDetails.jsx
│   ├── 📂 api
│   │   ├── index.js (API requests)
│   ├── App.js (Main App Component)
│   ├── index.js (Entry Point)
│   ├── styles.js (Global Styles)
│   ├── .env (Environment Variables)
│   ├── README.md (Project Documentation)
└── package.json
```

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/travel-advisor.git
cd travel-advisor
```

### 2️⃣ Install Dependencies
```sh
npm install
# or
yarn install
```

### 3️⃣ Setup API Keys
Create a `.env` file in the root folder and add the following:
```env
REACT_APP_GOOGLE_MAPS_API_KEY=your_google_maps_api_key
REACT_APP_RAPIDAPI_TRAVEL_API_KEY=your_rapidapi_key
```

### 4️⃣ Start the Application
```sh
npm start
# or
yarn start
```

---

## 🌍 API Integration
### Google Maps API (For Map & Autocomplete)
- Enable **Google Maps JavaScript API** & **Places API** from [Google Cloud Console](https://console.cloud.google.com/).
- Add your API key to `.env`.

### RapidAPI - Travel Advisor (For Places Data)
- Sign up on [RapidAPI](https://rapidapi.com/).
- Subscribe to the **Travel Advisor API**.
- Add your API key to `.env`.

---

## 🖥️ Usage
1️⃣ Enter a location in the **search bar**.
2️⃣ Use the **dropdown** to select **hotels, restaurants, or attractions**.
3️⃣ **Pan or zoom** the map to see new places.
4️⃣ Click a place **to view details** like address, reviews, and website.

---

## 🛠️ Troubleshooting
**1. Hotels are not showing?**
- Check if your **RapidAPI or Google API key** is valid.
- Try **a different location** (New York, London, Paris).

**2. API key is not working?**
- Make sure `.env` variables are loaded.
- Restart the app (`npm start`).
- Check console logs for errors (`F12 > Console`).


