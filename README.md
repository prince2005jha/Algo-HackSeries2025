# Algo-HackSeries2025

🚨 Women Safety & Empowerment Platform

A decentralized emergency alert and support system built on Algorand using AlgoKit SDK, enabling women to send tamper-proof SOS alerts and empowering NGOs & volunteers with blockchain-backed transparency.

<h2>📖 Overview</h2>

This open-source project aims to:

Provide women with a fast and reliable SOS mechanism (via mobile app).

Store emergency reports immutably on Algorand blockchain.

Enable NGOs, volunteers, and authorities to view & respond to alerts.

Reward responders with Algorand-based token incentives.

<h3>🔹 Features</h3>
<h5><br>👩‍🦰 Women Users (Mobile App – React Native)</h5>

One-tap / double-tap SOS button or shake gesture.

Captures location, timestamp, optional voice/video.

Blockchain confirmation: “Alert stored on Algorand.”

Notifies guardians, NGOs, and volunteers in real-time.

<h5>👐 Volunteers / NGOs (Web Dashboard – React.js)</h5>

View real-time map of active SOS alerts.

Accept/respond to cases (recorded on-chain).

Earn token incentives for verified responses.

<h5>🛡️ Authorities / Admins</h5>

Access all alerts in system.

Escalate to police/emergency services.

Download blockchain-verified reports.

View analytics (hotspots, repeat incidents).

<h4>⚙️ Tech Stack</h4>

<h5>Frontend:</h5>

📱 React Native (mobile app)

🌐 React.js (dashboard)

UI: TailwindCSS, React Native Paper

<h5>Backend:</h5>

Node.js / FastAPI (APIs & logic)

Firebase (push notifications)

Google Maps / Mapbox API (location services)

<h5>Blockchain:</h5>

Algorand + AlgoKit SDK

Smart Contracts (for SOS logging + token incentives)

<h5>🚀 System Workflow</h5>

User triggers SOS via app (button / double tap / shake).

App captures location + data → sends to backend.

Backend pushes alert → stores on Algorand blockchain.

Guardians, NGOs, and volunteers get real-time notification.

Volunteers/NGOs respond → action stored on-chain.

Rewards distributed via Algorand tokens.

<h4>✅ Functional Requirements</h4>

User registration/login (with wallet integration).

Send SOS alert within <2 sec.

Immutable storage on Algorand.

Real-time notifications.

Map visualization of alerts.

Volunteer/NGO response system.

Token reward mechanism.

Multilingual support (English/Hindi).

Offline-first (cache & sync).

<h4>🔒 Non-Functional Requirements</h4>

Performance: <2 sec alert send time.

Reliability: 99.9% uptime.

Security: Encrypted communication.

Scalability: 100k+ active users.

Usability: Large, simple SOS UI.

<h4>🛠️ Installation & Setup</h4>
<h5><br>Prerequisites</h5>

Node.js (v18+)

Python (3.8+)

AlgoKit (pipx install algokit)

Firebase / Maps API keys

<h5>Steps</h5>
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

<h4>📊 Future Enhancements</h4>

AI-based threat hotspot prediction.

Integration with IoT wearables.

Voice-based SOS triggers.

DAO-based community governance.

<h4>🤝 Contributing</h4>

We welcome contributions from developers, NGOs, and blockchain enthusiasts!

Fork the repo 🍴

Create a feature branch 🌱

Submit a PR 🔥

<h4>📜 License</h4>

This project is released under the MIT License.
