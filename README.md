# 🩺 BMT REPORTS — Clinical Monitoring & Doctor Intimation System

Production-grade, lightweight Web Application for **Clinical Monitoring, Vital Signs Tracking, Fluid Balance Calculations, and Instant Doctor Intimation via WhatsApp**.

---

## 🌟 Key Features

- 📋 **Patient Details**: Record Patient Name, Age, Weight, Date, and Time stamp.
- 🩺 **Vital Signs Tracker**: Real-time logging of Temperature (°F), Pulse Rate, Respiratory Rate, Blood Pressure (mmHg), MAP, and $\text{SpO}_2$ (%).
- 💧 **Automatic Fluid Balance Calculations**:
  - **Intake**: IV Fluid Intake + Oral Intake = Total Intake (mL).
  - **Output**: Urine + Motion Output, Motion episodes, Vomiting episodes = Total Output (mL).
  - **Net Fluid Balance**: Automatically calculates (Total Intake - Total Output).
- 📝 **Live Clinical Report Formatting**: Generates clean, formatted text summaries tailored for doctor sign-off.
- 💬 **One-Click WhatsApp Doctor Intimation**: Directly formats and transfers patient clinical reports into WhatsApp with pre-filled text.
- 📋 **Clipboard Copy & Clear Form**: Quick action controls for clinical staff.

---

## 🚀 Live Access & Deployment Options

### Option 1: Live GitHub Pages Deployment
1. Go to your GitHub Repository Settings: [Eswaran321/BMT-REPORTS Settings](https://github.com/Eswaran321/BMT-REPORTS/settings/pages)
2. Under **Build and deployment** -> **Source**, select `Deploy from a branch`.
3. Select branch `main` and folder `/ (root)`, then click **Save**.
4. Your application will be live instantly at:
   `https://eswaran321.github.io/BMT-REPORTS/`

### Option 2: Run Locally (Instant HTTP Server)
```bash
python -m http.server 8080 --directory "c:\Users\eswar\OneDrive\Documents\BMT-REPORTS"
```
Open your browser at: `http://localhost:8080`

---

## 📁 Repository Structure
```
BMT-REPORTS/
├── index.html               # Main Web App entrypoint (GitHub Pages compatible)
├── BMT REPORTS FINAL.html   # Standalone HTML application copy
└── README.md                # Documentation & Setup guide
```