
## 🎥 Demo & Screenshots

### 📹 Video Demo
[▶️ Watch the demo on YouTube](https://www.youtube.com/watch?v=OJxk7302Srs)

### 🖼️ Screenshots
| Dashboard | Patient QR | AI Summary |
|------------|-------------|-------------|
| ![Dashboard](https://drive.google.com/uc?export=view&id=18X_l748B-0C4dcbajlqFOlye1Y5uTygz) | ![QR](https://drive.google.com/uc?export=view&id=1JMUc9geWBb0Nxh9f48-0aeU80tR9xEmn) | ![AI Summary](https://drive.google.com/uc?export=view&id=1VDud_p8u68POSMhYHg9dv4iNrfqLBAl1) |

---

## 🚀 Overview

In many rural or low-connectivity areas, doctors struggle to access patients’ previous medical history during emergencies. **ResQ** bridges this gap through a **low-latency QR-based architecture** — doctors simply scan a QR code to retrieve medical records offline, with synchronization happening automatically once connectivity is restored.  

AI tools handle **summarization** and **verification**, ensuring records are concise and authentic, reducing the burden of paperwork and fraud.

---

## ✨ Key Features

✅ **AI-Powered Summarization**  
Uses OpenAI API to generate quick and context-aware medical summaries for doctors.  

✅ **QR-Based Patient Data Management**  
Each patient’s records are securely linked to a dynamically generated QR code.  

✅ **Doctor’s Dashboard**  
Scan QR codes to instantly retrieve patient history offline and update records when reconnected.  

✅ **Smart Appointment Scheduling**  
Manage bookings, set reminders, and get real-time scheduling updates.  

✅ **AI-Powered Prescription Verification**  
Verifies uploaded medical documents to detect tampering or fakes.  

✅ **Low-Internet Dependency**  
QR-based caching allows healthcare access even in low-connectivity regions.  

✅ **Secure & Private**  
Token-based QR authentication prevents unauthorized access.

---

## 🧠 How It Works

1. **Patients Upload Reports** – Users submit their medical reports securely.  
2. **AI Summarization** – OpenAI API condenses the uploaded data into a doctor-friendly summary.  
3. **QR Code Generation** – A unique QR code is generated and linked to each patient’s profile.  
4. **Doctor Scans QR** – Patient history and AI summaries are instantly accessible.  
5. **Offline Updates & Syncing** – Doctors can add prescriptions or notes that auto-sync once online.  
6. **Appointment Management** – Integrated scheduling and reminders ensure seamless follow-ups.

---

## 🧰 Tech Stack

| Component | Technology |
|------------|-------------|
| **Frontend** | React.js (Vite + TypeScript + Tailwind CSS) |
| **Backend** | Node.js + Express + MySQL |
| **AI Integration** | OpenAI API (for summarization & verification) |
| **Machine Learning** | Document classification and authenticity verification |
| **QR System** | Secure QR generation API |
| **Deployment** | Cloud-hosted (for accessibility and offline sync support) |

---

## 🏗️ Architecture & Design

- **Architecture Diagram:**  
  [🔗 View on Google Drive](https://drive.google.com/file/d/11FAvMs4PAV1Vd3oO4rsdzn0p9TOsCFQO/view?usp=sharing)

- **Flow Chart:**  
  [🔗 View on Google Drive](https://drive.google.com/file/d/1lqxAvkSGiFTOXGou9hrRS2LFsoLzGgBf/view?usp=sharing)

- **Wireframes:**  
  [🔗 View on Google Drive](https://drive.google.com/file/d/1Zs0DVtF9rMOMTWF68ZgAZ-Y_6SDQSrFs/view?usp=sharing)

---

## 💻 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/rohx24/resq-ai-healthcare.git
   cd resq-ai-healthcare
