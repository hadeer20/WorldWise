# 🌍 WorldWise

**WorldWise** is a travel tracking application that helps you keep track of the cities you've visited around the world.

Explore an interactive map, mark the places you've visited, and save your travel memories with visit dates and personal notes.

## ✨ Features

- **Interactive Map:** Explore the world using an interactive map powered by React Leaflet.
- **Add Cities:** Click anywhere on the map to select a location and add it to your visited cities.
- **Geolocation:** Use your current location to navigate the map.
- **Reverse Geocoding:** Automatically retrieve city and country information from selected coordinates using the BigDataCloud API.
- **Travel Journal:** Save the date of each visit and add personal notes about your trips.
- **Cities List:** View all your visited cities, open their details, and delete them from your list.
- **Countries List:** View the countries represented in your travel history.
- **City Details:** View city information, visit dates, personal notes, and a link to learn more on Wikipedia.
- **Protected Routes:** Access the travel dashboard after logging in with the demo account.
- **Lazy Loading:** Load application pages on demand using React Lazy and Suspense.

## 🛠️ Built With

- React 18
- TypeScript
- React Router
- Context API
- useReducer
- React Leaflet
- Leaflet
- CSS Modules
- React DatePicker
- Flag Icons
- JSON Server
- BigDataCloud Reverse Geocoding API
- Vite

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites

- Node.js
- npm

### 1. Clone the repository

```bash
git clone https://github.com/hadeer20/WorldWise.git
```

### 2. Navigate to the project directory

```bash
cd WorldWise
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the JSON Server

Open a terminal and run:

```bash
npm run server
```

The JSON Server will run at:

```text
http://localhost:9000
```

### 5. Start the development server

Open another terminal and run:

```bash
npm run dev
```

Open the local URL displayed in your terminal to use the application.

## 🔑 Demo Account

Use the following credentials to log in:

| Field    | Value            |
| -------- | ---------------- |
| Email    | jack@example.com |
| Password | qwerty           |

**Note:** WorldWise currently uses a demo authentication system and a local JSON Server API. It does not have a real backend or production authentication system.

## 📂 Project Structure

```text
WorldWise/
├── data/
│   └── cities.json
├── public/
│   ├── bg.jpg
│   ├── icon.png
│   ├── img-1.jpg
│   ├── img-2.jpg
│   └── logo.png
├── src/
│   ├── components/
│   ├── Contexts/
│   │   ├── CitiesContext.jsx
│   │   └── FakeAuthContext.jsx
│   ├── hooks/
│   │   ├── useGeolocation.js
│   │   └── useUrlPosition.jsx
│   ├── pages/
│   │   ├── AppLayout.jsx
│   │   ├── Homepage.jsx
│   │   ├── Login.jsx
│   │   ├── Pricing.jsx
│   │   ├── Product.jsx
│   │   └── ProtectedRoute.jsx
│   ├── App.tsx
│   ├── index.css
│   └── main.tsx
├── package.json
└── vite.config.ts
```

## 📜 Available Scripts

| Command           | Description                       |
| ----------------- | --------------------------------- |
| `npm run dev`     | Start the Vite development server |
| `npm run server`  | Start the local JSON Server       |
| `npm run build`   | Build the project for production  |
| `npm run lint`    | Run ESLint                        |
| `npm run preview` | Preview the production build      |

## 👩‍💻 Author

**Hadeer Mahmoud**

[GitHub Profile](https://github.com/hadeer20)
