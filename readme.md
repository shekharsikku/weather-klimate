## **Klimate - Weather App**

A modern, responsive weather application built with **React**, **Tailwind CSS**, **ShadCN UI**, and **React Query**.
It fetches real-time weather data using the **OpenWeather API**.

### **Features**

- **Real-time weather data** using OpenWeather API.
- **Search by city** to get current conditions.
- **Responsive design** powered by Tailwind CSS.
- **Beautiful UI components** from ShadCN.
- **Data fetching & caching** with React Query.
- **Loading & error states** for smooth UX.

### **Tech Stack**

- **React** – Frontend framework
- **Tailwind CSS** – Styling
- **ShadCN UI** – UI components
- **React Query** – Server state management
- **OpenWeather API** – Weather data source

### **Quick Start**

Ensure you have `Git, Node.js and npm` installed on your machine.

### **Setup Instructions**

**Clone the Repository**

```bash
git clone https://github.com/shekharsikku/weather-klimate

cd weather-klimate
```

**Install Dependencies**

```bash
npm install
```

**Set up Environment Variables**

- Create a `.env` file in the root directory.
- Add your OpenWeather API key:

```env
VITE_OPENWEATHER_API_BASE_URL=<base_url>
VITE_OPENWEATHER_API_GEO_URL=<geo_url>
VITE_OPENWEATHER_API_KEY=<api_key>
```

**Run the Development Server**

```bash
npm run dev
```

### **API Usage**

#### This project uses the **[OpenWeather API](https://openweathermap.org/api)**.

Sign up to get your free API key and place it in `.env`.

Example request:

```
https://api.openweathermap.org/data/2.5/weather?q=London&appid=<api_key>
```

### **Developer License**

#### MIT License | Developed by [Shekhar Sharma](https://linkedin.com/in/shekharsikku)

---
