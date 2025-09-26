# Algo-HackSeries2025

🚨 Women Safety & Empowerment Platform

A decentralized emergency alert and support system built on Algorand using AlgoKit SDK, enabling women to send tamper-proof SOS alerts and empowering NGOs & volunteers with blockchain-backed transparency.

📖 Overview

This open-source project aims to:

Provide women with a fast and reliable SOS mechanism (via mobile app).

Store emergency reports immutably on Algorand blockchain.

Enable NGOs, volunteers, and authorities to view & respond to alerts.

Reward responders with Algorand-based token incentives.

🔹 Features
👩‍🦰 Women Users (Mobile App – React Native)

One-tap / double-tap SOS button or shake gesture.

Captures location, timestamp, optional voice/video.

Blockchain confirmation: “Alert stored on Algorand.”

Notifies guardians, NGOs, and volunteers in real-time.

👐 Volunteers / NGOs (Web Dashboard – React.js)

View real-time map of active SOS alerts.

Accept/respond to cases (recorded on-chain).

Earn token incentives for verified responses.

🛡️ Authorities / Admins

Access all alerts in system.

Escalate to police/emergency services.

Download blockchain-verified reports.

View analytics (hotspots, repeat incidents).

⚙️ Tech Stack

Frontend:

📱 React Native (mobile app)

🌐 React.js (dashboard)

UI: TailwindCSS, React Native Paper

Backend:

Node.js / FastAPI (APIs & logic)

Firebase (push notifications)

Google Maps / Mapbox API (location services)

Blockchain:

Algorand + AlgoKit SDK

Smart Contracts (for SOS logging + token incentives)

🚀 System Workflow

User triggers SOS via app (button / double tap / shake).

App captures location + data → sends to backend.

Backend pushes alert → stores on Algorand blockchain.

Guardians, NGOs, and volunteers get real-time notification.

Volunteers/NGOs respond → action stored on-chain.

Rewards distributed via Algorand tokens.

✅ Functional Requirements

User registration/login (with wallet integration).

Send SOS alert within <2 sec.

Immutable storage on Algorand.

Real-time notifications.

Map visualization of alerts.

Volunteer/NGO response system.

Token reward mechanism.

Multilingual support (English/Hindi).

Offline-first (cache & sync).

🔒 Non-Functional Requirements

Performance: <2 sec alert send time.

Reliability: 99.9% uptime.

Security: Encrypted communication.

Scalability: 100k+ active users.

Usability: Large, simple SOS UI.

🛠️ Installation & Setup
Prerequisites

Node.js (v18+)

Python (3.8+)

AlgoKit (pipx install algokit)

Firebase / Maps API keys

Steps
# Clone repo
git clone https://github.com/your-username/women-safety-dapp.git
cd women-safety-dapp

# Install dependencies
npm install   # or yarn install

# Start mobile app (Expo)
npm start

# Start web dashboard
cd dashboard && npm install && npm start

# Start backend
cd backend && pip install -r requirements.txt && uvicorn main:app --reload

📊 Future Enhancements

AI-based threat hotspot prediction.

Integration with IoT wearables.

Voice-based SOS triggers.

DAO-based community governance.

🤝 Contributing

We welcome contributions from developers, NGOs, and blockchain enthusiasts!

Fork the repo 🍴

Create a feature branch 🌱

Submit a PR 🔥

📜 License

This project is released under the MIT License.
