# 🏙️ CivicLens AI

> AI-Powered Civic Issue Reporting & Prioritization Platform

## 📌 Overview

CivicLens AI is a smart web application that enables citizens to report civic issues such as potholes, garbage overflow, broken streetlights, drainage problems, and water leakages. The platform uses **Google AI Studio (Gemini API)** as its core intelligence engine to analyze reported issues, estimate their severity, and help authorities prioritize them based on community impact.

This project was developed as a prototype for a Web Development Hackathon, where Google AI Studio/Gemini serves as the central intelligence layer rather than just an additional feature.

LinkedIn Post Link :-                                                                                                                                              
https://www.linkedin.com/posts/hania-khan-2ba44140b_googledevelopergroup-gdg-hackathon-ugcPost-7479604953460953089-77rx/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAGiJrG4BKnIuZMDT99lv4-VIGoX6hedBJcA 

---

# 🚀 Features

* 🔐 User Signup & Login (Prototype Authentication)
* 📷 Upload Civic Issue Images
* 🤖 AI-Powered Issue Classification using Google Gemini
* 📊 Severity Detection
* ⭐ Priority Score Generation
* 📍 Location-Based Issue Reporting
* 👍 Community Voting & Verification
* 📈 Community Impact Score Calculation
* 📋 Authority Dashboard
* 🖼️ Before & After Resolution Gallery
* 📱 Fully Responsive User Interface

---

# 💡 Problem Statement

Citizens frequently report public infrastructure issues, but authorities often struggle to identify which problems require immediate attention.

Without proper prioritization:

* Important complaints remain unresolved.
* Dangerous locations are ignored.
* Government resources are inefficiently allocated.

---

# ✅ Solution

CivicLens AI combines Artificial Intelligence with community participation to automatically analyze and prioritize civic issues.

The application allows users to:

* Upload an image of a civic issue.
* Describe the problem.
* Receive AI-generated analysis.
* Allow community members to verify and vote.
* Automatically calculate an Impact Score.
* Display priority rankings for authorities.

---

# 🤖 Google AI Integration

Google AI Studio (Gemini API) is the core intelligence engine of this project.

Gemini AI performs the following tasks:

* Detects the type of civic issue
* Estimates issue severity
* Generates a priority score
* Suggests recommended authority actions
* Assists in issue prioritization

Example AI Output:

Issue Type: Road Damage

Severity: High

Priority Score: 9/10

Suggested Action:
Immediate road repair recommended due to safety hazards.

This makes Google AI the central decision-making component of the application.

---

# 🧠 Community Impact Score

The platform calculates a Community Impact Score using:

Impact Score =

(Severity × 5)

*

(Community Votes × 2)

*

(Nearby Confirmations × 3)

Higher scores indicate higher priority for authorities.

---

# 🛠️ Technologies Used

## Frontend

* HTML5
* CSS3
* JavaScript

## Artificial Intelligence

* Google AI Studio
* Gemini API

## Storage

* Browser LocalStorage (Prototype Database)

## Development Environment

* Visual Studio Code

---

# 📁 Project Structure

CivicLens-AI/

├── index.html

├── signup.html

├── login.html

├── report.html

├── community.html

├── dashboard.html

├── gallery.html

├── style.css

├── script.js

├── auth.js

├── gemini.js

├── data.js

├── images/

└── README.md

---

# ⚙️ Installation

1. Clone the repository

git clone https://github.com/yourusername/CivicLens-AI.git

2. Open the project folder in Visual Studio Code.

3. Replace the placeholder Gemini API Key inside `gemini.js` with your own API key from Google AI Studio.

4. Open `index.html` in your browser.

No database or server installation is required for the prototype version.

---

# 📷 Application Workflow

1. User creates an account.
2. User logs into the application.
3. User uploads a civic issue image.
4. Gemini AI analyzes the issue.
5. AI generates:

   * Issue Type
   * Severity
   * Priority Score
   * Suggested Action
6. Community members verify and vote.
7. The system calculates the Community Impact Score.
8. Authorities monitor issues through the dashboard.
9. Resolved issues appear in the Before & After Gallery.

---

# 🎯 Objectives

* Improve civic issue reporting.
* Help authorities prioritize public complaints.
* Increase community participation.
* Demonstrate practical use of Google AI.
* Promote smarter city management.

---

# 🌍 Real-World Impact

CivicLens AI enables:

* Faster response to urgent civic issues.
* Better resource allocation.
* Transparent issue tracking.
* Community-driven verification.
* AI-assisted decision making.

---

# 📌 Future Improvements

* Real-time notifications
* GPS-based location detection
* Live database integration
* Government portal integration
* Mobile application
* Admin role management
* AI-based duplicate report detection
* Interactive city heatmaps

---

# 👨‍💻 Developed For

Web Development Hackathon

Track: Web Development

Theme: AI-Powered Civic Issue Reporting

---

# 📄 License

This project is developed for educational and hackathon purposes.

---

# 🙏 Acknowledgements

* Google AI Studio (Gemini API)
* Google Antigravity
* Visual Studio Code
* HTML, CSS & JavaScript Community
