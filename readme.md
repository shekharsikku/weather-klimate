## **🌤 Klimate - Weather App**

A modern, responsive weather application built with **React**, **Tailwind CSS**, **ShadCN UI**, and **React Query**.
It fetches real-time weather data using the **OpenWeather API**.

### 🚀 Features

- **Real-time weather data** using OpenWeather API.
- **Search by city** to get current conditions.
- **Responsive design** powered by Tailwind CSS.
- **Beautiful UI components** from ShadCN.
- **Data fetching & caching** with React Query.
- **Loading & error states** for smooth UX.

### 🛠 Tech Stack

- **React** – Frontend framework
- **Tailwind CSS** – Styling
- **ShadCN UI** – UI components
- **React Query** – Server state management
- **OpenWeather API** – Weather data source

### 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/shekharsikku/weather-klimate.git
cd weather-app
```

2. **Install dependencies**

```bash
npm install
```

3. **Set up environment variables**

- Create a `.env` file in the root directory.
- Add your OpenWeather API key:

```env
VITE_OPENWEATHER_API_KEY=<your_api_key_here>
```

4. **Run the development server**

```bash
npm run dev
```

### 🌍 API Usage

This project uses the **[OpenWeather API](https://openweathermap.org/api)**.
Sign up to get your free API key and place it in `.env`.

Example request:

```
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY
```

### 📄 License

This project is licensed under the **MIT License**.

---
