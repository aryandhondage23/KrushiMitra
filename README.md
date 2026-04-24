# 🌾 KrushiMitra – Smart Farming Assistant

## Project Structure

```
krushimitra/
├── index.html    ← Main app file (all HTML + CSS)
├── data.js       ← All 36 districts data + translations
├── app.js        ← Application logic
└── README.md     ← This file
```

---

## 🚀 VSCode Setup & Run

### Step 1 — Install VSCode
Download from: https://code.visualstudio.com/

### Step 2 — Install the Live Server Extension
1. Open VSCode
2. Press `Ctrl+Shift+X` (Extensions)
3. Search: **Live Server**
4. Install by **Ritwick Dey**

### Step 3 — Open the Project
1. `File → Open Folder → krushimitra/`
2. All 3 files appear in the sidebar

### Step 4 — Run
1. Right-click `index.html` in the sidebar
2. Select **"Open with Live Server"**
3. Browser opens at `http://127.0.0.1:5500/index.html`
4. Any file change auto-reloads the browser ✅

---

## 🔑 API Key Setup

The app calls the Anthropic API for enhanced analysis.

1. Open `app.js`
2. Find line: `const API_KEY = ''`
3. Paste your API key there
4. Save — the browser reloads automatically

> Get your key at: https://console.anthropic.com/

**Without API key** — app still works fully using built-in district data.

---

## ✅ Features

| Feature | Details |
|---------|---------|
| 🌍 Districts | All 36 Maharashtra districts |
| 🌐 Languages | English / हिंदी / मराठी — full app translation |
| 🌾 Sections updated on district change | Climate, Crop, Risk, Calendar, Pest, Dashboard |
| 📊 Real data | IMD rainfall, MRSAC soil, ICAR crop, MSP 2024–25 |
| 🗓️ Farm Calendar | Crop-specific sowing to harvest schedule |
| 🐛 Pest Guide | District zone-specific pests & pesticides |
| 📱 Responsive | Works on mobile and desktop |

---

## 🗺️ All 36 Districts Supported

Ahmednagar, Akola, Amravati, Aurangabad (CSNM), Beed, Bhandara,
Buldhana, Chandrapur, Dhule, Gadchiroli, Gondia, Hingoli,
Jalgaon, Jalna, Kolhapur, Latur, Mumbai City, Mumbai Suburban,
Nagpur, Nanded, Nandurbar, Nashik, Osmanabad (Dharashiv), Palghar,
Parbhani, Pune, Raigad, Ratnagiri, Sangli, Satara, Sindhudurg,
Solapur, Thane, Wardha, Washim, Yavatmal

---

## 📞 Helplines

- Kisan Call Centre: **1800-180-1551** (Toll Free)
- MRSAC Agri: mahapocra.gov.in
- IMD Pune: imdpune.gov.in
