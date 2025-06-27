# June27_Assignment_2
 June27_Assignment_2


# 🏍️ RideRadar

## 📖 Description

**RideRadar** is a mobile and web application built for motorcycle enthusiasts who want to ride together. Whether you're planning a group trip, looking for new riding buddies nearby, or just want to chat with your club, RideRadar helps you connect. With AI-driven ride recommendations, real-time group tracking, and chat features, RideRadar brings riders together like never before.

---

## 📚 Table of Contents

- [Description](#-description)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Known Bugs](#-known-bugs)
- [Contributors](#-contributors)
- [Screenshots](#-screenshots)
- [Links](#-links)

---

## ✨ Features

- 🧠 **AI-based Ride Suggestions** – Recommends scenic or rider-preferred routes using user behavior and environmental data.
- 📍 **Location-Based Rider Discovery** – Find and connect with other bikers near you.
- 🗺️ **Smart Route Planner** – Optimize multi-stop rides and receive live traffic/weather updates.
- 💬 **Group Messaging & Voice Chat** – Communicate in real time while riding or planning.
- 🏆 **Ride History & Stats** – Tracks past rides, average speeds, distance, etc.
- 📢 **Event & Meetup Planning** – Create or join local ride events.
- 🔐 **Privacy Controls** – Decide who can see your rides or contact you.

---

## 🛠️ Technologies Used

- **Frontend**: React Native (Expo), React.js
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Machine Learning**: Python, TensorFlow, scikit-learn (ride suggestion engine)
- **Maps & Geo**: Google Maps API, OpenStreetMap, Mapbox
- **Authentication**: Firebase Auth
- **Real-Time Comms**: Socket.IO, WebRTC
- **Cloud**: Firebase Functions, AWS S3 (media storage)
- **CI/CD**: GitHub Actions, Expo EAS

---

## 📦 Installation

### 1. Clone the repo

```bash
git clone https://github.com/rnajdesign/rideradar.git
cd rideradar
````

### 2. Frontend (Mobile & Web)

```bash
cd client
npm install
npm start
```

To run on mobile:

* Install Expo Go on your phone.
* Scan the QR code from `npm start`.

### 3. Backend

```bash
cd server
npm install
npm run dev
```

### 4. Environment Variables

Create a `.env` file in both `client/` and `server/` directories.

**Example (`server/.env`):**

```
MONGODB_URI=mongodb+srv://user:pass@cluster.mongodb.net/rideradar
GOOGLE_MAPS_API_KEY=your_api_key
JWT_SECRET=your_jwt_secret
```

---

## 🖥️ Usage

1. **Sign up** via email or Google.
2. **Enable location** to discover riders nearby.
3. **Plan a ride** by selecting waypoints or choosing a smart-suggested route.
4. **Create a group** and invite friends via QR or username.
5. **Chat or voice call** with your group in real time.
6. **Log rides** and check your ride stats later.

---

## 🐛 Known Bugs

* Group voice call sometimes drops on weak networks
* Chat occasionally duplicates messages
* Event notifications delay on Android
* Route planner doesn't re-calculate after detour
* Rider discovery map fails to load in low-GPS areas

---

## 👥 Contributors

* [@speedster88](https://github.com/speedster88)
* [@rideordie](https://github.com/rideordie)
* [@codetorque](https://github.com/codetorque)
* [@drivencode](https://github.com/drivencode)

---

## 📸 Screenshots

![Home Screen](https://yourcdn.com/screenshots/home.png)
![Route Planning](https://yourcdn.com/screenshots/planning.png)
![Group Ride Map](https://yourcdn.com/screenshots/groupmap.png)

---

## 🔗 Links

* 🌐 [Live Demo](https://rideradar.app)
* 📱 [Download for iOS](https://apps.apple.com/app/id123456789)
* 📱 [Download for Android](https://play.google.com/store/apps/details?id=rideradar)
* 📘 [API Docs](https://rideradar.app/docs)
* 🐛 [Issues](https://github.com/yourusername/rideradar/issues)

---

## 📄 License

MIT License. See the [LICENSE](./LICENSE) file for details.