# 🩸 BMT REPORTS — Bone Marrow Transplant Clinical Suite & Intimation

Production-grade, high-performance **Clinical Monitoring Suite & Doctor Intimation System** specifically designed for **Bone Marrow Transplant (BMT) / Hematology-Oncology** units.

---

## 🌟 Key Features

1. 👤 **Patient Details**:
   - Captures Patient Name, Age, Weight (kg), Date & Time.

2. 🩺 **Vital Signs & Early Warning Score (EWS)**:
   - Temperature (°F), Pulse Rate (bpm), Resp. Rate, Blood Pressure (mmHg), MAP (auto-calculated), $\text{SpO}_2$ (%).
   - **Auto-Risk Alert System**: Flags Neutropenic Fever ($\ge 100.4^\circ\text{F}$) and Hypoxia ($\text{SpO}_2 < 95\%$).

3. 🧪 **CBC & Engraftment Tracker**:
   - Tracks WBC, ANC (cells/µL), Hemoglobin (g/dL), Platelets ($\times 10^3/\mu\text{L}$).
   - **Auto-Engraftment Detector**: Detects criteria for neutrophil engraftment ($\text{ANC} \ge 500$) and platelet engraftment ($\text{Plt} \ge 20\text{k}$).

4. ⚠️ **Toxicity & GvHD Grading**:
   - WHO Oral Mucositis Grading (Grade 0–4).
   - Acute Skin GvHD Staging (Stage 0–4 BSA rash).
   - GI GvHD / Diarrhea output tracking.

5. 💧 **24-Hour Fluid Balance**:
   - Auto-summation of IV Fluid Intake + Oral Intake.
   - Summation of Urine + Diarrhea + Vomit/Drains.
   - Calculates Net 24h Fluid Balance (mL).

6. 📤 **Multi-Format Export & Doctor Intimation**:
   - 💬 **WhatsApp Intimation**: Formatted with markdown emojis for direct messaging to attending consultants.
   - 📋 **Copy to Clipboard**: Quick copy for EMR/EHR clinical notes.
   - 🖨️ **Print / PDF Export**: Styled printable layout for physical patient charts.
   - 💾 **Local Storage Log History**: Save daily entries in-browser to review past clinical trends.
   - 🌓 **Dark / Light Mode**: High-contrast theme toggle for night-shift clinical staff.

---

## 🚀 Live Access & Deployment Options

### 1. Live Web Access (Local Server Running)
Open in your browser right now:
👉 `http://localhost:8080`

### 2. GitHub Pages Deployment (Free Worldwide Access)
The repository is deployed on branch `main` and `gh-pages`:
- GitHub Repository: [Eswaran321/BMT-REPORTS](https://github.com/Eswaran321/BMT-REPORTS)
- GitHub Pages Settings: [Pages Configuration](https://github.com/Eswaran321/BMT-REPORTS/settings/pages)
- Live Site URL: **`https://eswaran321.github.io/BMT-REPORTS/`**