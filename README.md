# 🌱 AgroSmart — Smart Agriculture Platform

<p align="center">
  **Smarter Farming. Healthier Crops. Better Decisions.**
</p>

<p align="center">
  An agriculture-focused web application that brings plant disease detection, weather information, and agricultural news together in one place.
</p>

<p align="center">
  🌐 **Live Demo:** https://agrosmart-liard.vercel.app/
</p>

---

## 📖 About the Project

**AgroSmart** is a full-stack web application designed to help users access useful agricultural information through a single platform. By integrating external APIs with a React-based interface and a Node.js backend, the application makes plant health information, weather data, and agricultural news more accessible.

The project demonstrates how modern web technologies and third-party APIs can be combined to develop practical solutions for agriculture.

## ✨ Key Features

- 🌿 **Plant Disease Detection** — Uses the Kindwise API to analyze plant images and identify potential plant diseases.
- 🌦️ **Weather Information** — Integrates the OpenWeatherMap API to retrieve weather data.
- 📰 **Agricultural News** — Uses the Newsdata.io API to access agricultural news and updates.
- ⚛️ **Interactive User Interface** — Built with React for a component-based user experience.
- 🧭 **Client-Side Navigation** — Uses React Router for navigation between application pages.
- 🔗 **API Integration** — Uses Axios to communicate with external services and the backend.
- 🖼️ **File Upload Support** — Uses Multer on the backend to handle uploaded files.
- 🔐 **Environment Configuration** — Uses dotenv to manage environment variables.

## 🛠️ Tech Stack

### Frontend

| Technology | Purpose |
|---|---|
| React | Component-based user interface |
| React Router | Client-side routing and navigation |
| Axios | HTTP requests and API communication |
| CSS | Styling and layout |

### Backend

| Technology | Purpose |
|---|---|
| Node.js | JavaScript runtime environment |
| Express.js | Backend server and API handling |
| CORS | Cross-origin resource sharing |
| dotenv | Environment variable management |
| Multer | File upload handling |

### External APIs & Services

| API / Service | Purpose |
|---|---|
| Kindwise API | Plant disease detection |
| Newsdata.io API | Agricultural news |
| OpenWeatherMap API | Weather information |
| Vercel | Frontend deployment |

## 🔄 How It Works

1. **User Interaction:** Users interact with the AgroSmart web interface.
2. **Request Handling:** The frontend uses Axios to send requests to the relevant backend endpoints or external APIs, depending on the functionality.
3. **Backend Processing:** The Express.js server handles configured API requests and uploaded files where required.
4. **External API Integration:** AgroSmart connects with the Kindwise, Newsdata.io, and OpenWeatherMap services to retrieve relevant information.
5. **Results Display:** The application presents the retrieved information through its React interface.

## 🏗️ Architecture

```text
                 ┌──────────────────────┐
                 │        User          │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │   React Frontend     │
                 │ React Router + CSS   │
                 └──────────┬───────────┘
                            │
                         Axios
                            │
                            ▼
                 ┌──────────────────────┐
                 │  Node.js + Express   │
                 │   Backend Server     │
                 └──────────┬───────────┘
                            │
             ┌──────────────┼──────────────┐
             ▼              ▼              ▼
       ┌───────────┐ ┌────────────┐ ┌──────────────┐
       │ Kindwise  │ │ Newsdata.io│ │ OpenWeather  │
       │    API    │ │     API    │ │     API      │
       └───────────┘ └────────────┘ └──────────────┘
```

*The diagram represents the application's high-level integration architecture.*

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- npm (included with Node.js)
- API credentials for the external services used by your application

## 🔑 Environment Variables

Create a `.env` file in the appropriate application directory and configure the credentials required by your implementation.

Example placeholders:

```env
PORT=5000

KINDWISE_API_KEY=your_kindwise_api_key
NEWSDATA_API_KEY=your_newsdata_api_key
OPENWEATHERMAP_API_KEY=your_openweathermap_api_key
```

Use the exact variable names expected by your code. If the frontend accesses an API directly, configure its variables according to your frontend setup.

**Security:** Never commit API keys, passwords, or other secrets to GitHub. Keep sensitive credentials in environment variables and configure production secrets through your hosting provider.

## 🎯 Project Objectives

- Apply full-stack web development concepts to an agriculture-focused use case.
- Integrate third-party APIs into a practical web application.
- Understand communication between frontend and backend components.
- Handle image uploads and API responses.
- Build a maintainable application using reusable React components and an Express.js backend.

## 🔮 Future Enhancements

- 📊 Crop health monitoring and disease history.
- 🌾 Personalized crop care recommendations.
- 🔔 Weather alerts and agricultural notifications.
- 📱 Improved mobile responsiveness.
- 🌍 Multilingual support for better accessibility.

## 🌐 Live Application

Explore AgroSmart here:

**[Open AgroSmart](https://agrosmart-liard.vercel.app/)**

## 👨‍💻 Built With

React • React Router • Axios • CSS • Node.js • Express.js • Kindwise API • Newsdata.io API • OpenWeatherMap API

---

<p align="center">
  🌱 <b>AgroSmart — Bringing Technology Closer to Agriculture.</b>
</p>
