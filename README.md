# MediChat – AI-Powered Healthcare Assistant

MediChat is an AI-powered healthcare assistant built with **Next.js**, designed to provide personalized health support.  
It combines **secure authentication, intelligent chatbot interactions, and health data tracking** to act as a reliable digital healthcare companion.

---

## Key Features

- **Secure Authentication**  
  Login with Google/GitHub using **NextAuth** and JWT-based session management.

- **AI-Powered Chatbot**  
  Integrated with **Gemini AI** for context-aware health guidance and real-time responses.

- **Symptom Checker**  
  Enter symptoms → get probable conditions + recommended next steps (self-care or doctor visit).

- **Health Metrics Dashboard**  
  Track vitals like **Blood Pressure, Blood Sugar, Weight, and Medication History**.  
  Interactive charts powered by **Chart.js** and **Recharts**.

- **Medication Reminders** *(beta)*  
  Receive reminders and notifications for scheduled medications.

- **Data Security & Privacy**  
  TLS/SSL encryption, MongoDB (with Mongoose) for secure data storage, and role-based access control.

---

## Tech Stack

**Frontend:** Typescript, Next.js, Tailwind CSS  
**Backend:** Node.js, NextAuth, MongoDB + Mongoose  
**AI:** Gemini AI  
**Visualization:** Chart.js, Recharts  
**Security:** TLS/SSL, JWT  

---

## Screenshots

- **Login Page**  
  <img width="1462" height="833" alt="image" src="https://github.com/user-attachments/assets/fef4af19-58c8-4fd2-883c-ff6fa74e7aef" />
  <img width="1470" height="770" alt="image" src="https://github.com/user-attachments/assets/539d6b49-8989-49bd-8f23-a58308820939" />



- **Chatbot in Action**  
  <img width="1470" height="827" alt="image" src="https://github.com/user-attachments/assets/395a89b6-0d5a-443f-bd31-701c72778735" />
  <img width="1462" height="832" alt="image" src="https://github.com/user-attachments/assets/e19c1f88-0155-4e0c-801d-d6a7a3168a8a" />



- **Health Dashboard**  
  <img width="1470" height="834" alt="image" src="https://github.com/user-attachments/assets/055b173b-0158-40a4-9552-38dd1dcbf1d7" />


---

## Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/hit123esh/medichat.git
cd medichat
npm install
