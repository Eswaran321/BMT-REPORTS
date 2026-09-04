# 🩸 BMT REPORTS — Bone Marrow Transplant Clinical Suite & Intimation

Production-grade, high-performance **Clinical Monitoring Suite & Doctor Intimation System** specifically designed for **Bone Marrow Transplant (BMT) / Hematology-Oncology** units.

---

## 🌟 Key Features

1. 👤 **Patient Details**:
   - Captures Patient Name, Age, Weight (kg), Date & Time.

2. 🩺 **Vital Signs & Early Warning Score (EWS)**:
   - Temperature (°F), Pulse Rate (bpm), Resp. Rate, Blood Pressure (mmHg), MAP (auto-calculated), $\text{SpO}_2$ (%).
   - **Auto-Risk Alert System**: Flags Neutropenic Fever ($\ge 100.4^\circ\text{F}$) and Hypoxia ($\text{SpO}_2 < 95\%$).

3. 💧 **24-Hour Fluid Balance**:
   - Auto-summation of IV Fluid Intake + Oral Intake.
   - Summation of Urine + Diarrhea + Vomit/Drains.
   - Calculates Net 24h Fluid Balance (mL).

4. 📤 **Multi-Format Export & Doctor Intimation**:
   - 💬 **WhatsApp Intimation**: Formatted with markdown emojis for direct messaging to attending consultants.
   - 📋 **Copy to Clipboard**: Quick copy for EMR/EHR clinical notes.
   - 🖨️ **Print / PDF Export**: Styled printable layout for physical patient charts.
   - 💾 **Local Storage Log History**: Save daily entries in-browser to review past clinical trends.
   - 🌓 **Dark / Light Mode**: High-contrast theme toggle for night-shift clinical staff.

---

## 🚀 Open the App

**App links:** [Local server](http://localhost:8080) (when running locally) | [Public website](https://eswaran321.github.io/BMT-REPORTS/)

The repository is deployed on branches `main` and `gh-pages`:
- GitHub Repository: [Eswaran321/BMT-REPORTS](https://github.com/Eswaran321/BMT-REPORTS)
- GitHub Pages Settings: [Pages Configuration](https://github.com/Eswaran321/BMT-REPORTS/settings/pages)