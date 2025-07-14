#  RailBhoomi - AI-powered Railway Complaint Management System

RailBhoomi is a smart and user-friendly complaint management platform designed for the Indian railway system. It bridges the communication gap between passengers and authorities by providing **multilingual**, **accessible**, and **AI-powered** solutions to register, track, and resolve complaints efficiently.

---

##  Features

###  Speech-to-Text Functionality
- Users who are unable to type can simply **speak their complaint**, which is automatically transcribed using the **Web Speech API** and submitted.

###  Multi-language Support
- Breaks the **language barrier** by offering support for **multiple Indian languages**, ensuring accessibility for all users.

###  User-Friendly Interface
- Intuitive and clean design makes the platform easy to understand and navigate, even for first-time users.

###  Image Upload as Proof
- Users can attach **images** to support their complaints, adding credibility and clarity to the issue.

###  AI-Based Complaint Prioritization
- An integrated **AI model** assigns a **priority level (High, Medium, Low)** to each complaint based on its severity and keywords.
- Ensures **urgent issues are addressed first** by the administration.

###  Admin Panel
- Dedicated dashboard for admins to:
  - View complaints
  - Approve or reject submissions
  - Sort and filter complaints by **priority**

###  Complaint Tracker
- Users can **track the status** of their complaints in real-time:
  - Pending
  - Approved
  - In Progress
  - Resolved

---

##  Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Speech-to-Text**: Web Speech API
- **AI**: Custom Machine Learning Model for complaint prioritization
- **Multi-language Support**: Google Translate API / i18next
- **Authentication**: JWT or custom login system

---

##  How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Krish-Dhonde/RailBhoomi
