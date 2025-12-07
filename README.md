🚀 ZeroScan – Frontend

A modern, cyber-themed frontend for ZeroScan, a vulnerability-scanning platform designed for students, developers, and cybersecurity beginners.
This frontend provides a futuristic UI where users can upload codebases, scan GitHub repos, and view detected vulnerabilities in a clean, interactive dashboard.

🌐 About ZeroScan

ZeroScan is a web-based tool that helps users identify vulnerabilities in:

Python

PHP

JavaScript

The frontend is designed to deliver a smooth, hacker-themed experience with neon cyber aesthetics, terminal-style animations, and a clean scanning workflow.

This repository contains only the frontend.
Backend will be added later.

🎯 Features
🔥 Modern Cyber UI

Dark theme

Neon green highlights

Hacker terminal feel

Smooth animations

📤 Code Upload & GitHub Scan UI

Drag & drop upload

GitHub URL input

File preview interface

⌨️ Terminal Scanning Animation

Animated typing

Loading indicators

Glitch effects

📊 Dashboard

Summary cards (High, Medium, Low vulns)

Data tables

Slide-in vulnerability details panel

💬 Vulnerability Detail Viewer

Syntax-highlighted code snippet

Explanation

Mitigation steps

Secure example code

📄 Report Preview Page

Simple visual summary

PDF export button placeholder

🧪 Tech Stack

This frontend is built using:

React / Next.js

TailwindCSS

Framer Motion (animations)

Prism.js / Monaco Editor (code highlighting)

Zustand or Redux (state management)

Axios (API calls placeholder)

The project is structured so backend APIs can be integrated easily later.

📁 Folder Structure
/components
    Navbar.jsx
    UploadBox.jsx
    GithubInput.jsx
    TerminalScan.jsx
    StatsCard.jsx
    VulnTable.jsx
    VulnDetailsDrawer.jsx
    Footer.jsx

/pages
    index.jsx
    upload.jsx
    scan.jsx
    dashboard.jsx
    report.jsx

/styles
    globals.css
    theme.css

⚙️ Setup Instructions
1. Clone the Repository
git clone https://github.com/<your-username>/ZeroScan-Frontend.git
cd ZeroScan-Frontend

2. Install Dependencies
npm install
# or
yarn install

3. Start Development Server
npm run dev
# or
yarn dev

4. Open in Browser
http://localhost:3000

🔌 API Integration (Coming Soon)

All API calls are currently linked to placeholder functions.
Once the backend is ready, simply update:

/services/api.js


This design makes the frontend ready for immediate integration.

🎨 Design Philosophy

ZeroScan’s UI aims to be:

Student-friendly

Beginner-safe

Cyber-themed

Clean and modern

Intuitive for non-technical users

The visual identity is based on:

Neon cyber green

Terminal black

Futuristic card design

Smooth animated transitions

🧠 Roadmap
✔ Completed (Frontend)

Landing page

Upload & GitHub scan UI

Terminal scanning animation

Dashboard UI

Vulnerability detail panel

Report preview page

🚧 Upcoming

Backend integration

Full scanning engine

AI explanation mode

Auto-fix suggestions

User authentication

🤝 Contributing

Contributions are welcome!
You can fork the repo, create a new branch, and submit a pull request.

🛡️ License

MIT License – free to use, modify, and distribute.

👤 Author

Ali Reza Mohammad Naziul Haque Siam
Founder & President – LSBU ZeroDay Cybersecurity Society
Passionate Cybersecurity Learner
