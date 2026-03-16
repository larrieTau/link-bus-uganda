# link-bus-uganda
A high-performance web suite for Link Bus Uganda. Features real-time booking, QR ticketing, and live fleet tracking. Includes native MTN/Airtel Money integration and a logistics module for couriers. Built for low-bandwidth reliability and scalability, modernizing the Kampala–Western Uganda travel experience with a mobile-first approach.
Link Bus Uganda: Digital Transformation Suite
A high-performance, full-stack solution designed to modernize the travel and logistics operations of Link Bus Services, Uganda’s leading long-distance carrier. This platform bridges the gap between traditional transport and 2026 digital standards.

🚀 Key Features
Smart Booking Engine: Real-time seat selection with dynamic pricing and route filtering for the Kampala–Western Uganda corridor.

Localized Payments: Native API integration for MTN Mobile Money and Airtel Money for instant, frictionless checkouts.

Live Fleet Tracker: Real-time GPS-based dashboard for passengers to monitor departures and ETAs from terminals like Namirembe Road and Fort Portal.

QR Ticketing: Encrypted digital boarding passes that work offline to streamline terminal check-ins.

Courier Logistics: A dedicated module for tracking parcels and commercial goods from dispatch to pickup.

🛠️ Technical Stack
Frontend: React / Next.js (Optimized for low-bandwidth 3G/4G environments).

Backend: Node.js with a Microservices architecture.

Database: PostgreSQL (Transactional data) & Redis (Real-time seat locking).

Payments: Integrated via Beyonic / Flutterwave (Uganda-specific gateways).

Maps: Leaflet.js / Google Maps API for route visualization.

📦 Installation & Setup
Clone the repo:

Bash
git clone https://github.com/larrietau/link-bus-uganda.git
Install dependencies:

Bash
npm install
Environment Variables:
Create a .env file and add your Mobile Money API keys and Database URI.

Run Development Server:

Bash
npm run dev
🌍 Impact
This project focuses on digital inclusion, ensuring that travelers in rural areas like Bundibugyo or Kagadi have the same booking convenience as those in the city.
