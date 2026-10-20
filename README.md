# 🌿 TenangMind Malaysia

**Mental Health & Fitness Assessment** — a bilingual (English / Bahasa Melayu) web app for anxiety self-screening, guided breathwork, and somatic grounding, with verified Malaysian support helplines built in.

> *Check in with your mind. Realign with your body.*

---

## ✨ Features

### 📝 Self-Assessment Screening
- 9-question check-in based on the **GAD-7** (Generalized Anxiety Disorder-7) scale, covering the past 2 weeks
- Extra **somatic tension** slider (0–10) for jaw, neck and shoulder strain
- Sleep disruption question to capture the effect of overthinking on rest
- Progress bar with back / next navigation

### 📊 Results Dashboard
- Anxiety level tiers based on standard GAD-7 cut-offs:

| GAD-7 Score | Result |
|:-----------:|--------|
| 0 – 4   | Minimal Anxiety |
| 5 – 9   | Mild Anxiety |
| 10 – 14 | Moderate Anxiety |
| 15 – 21 | Severe Anxiety |

- Category breakdown bars for anxiety level and physical tension
- Personalised action plan (for example, helpline suggestions for higher scores, somatic routines for high tension)
- **Print / Save as PDF** report with a print-optimised A4 layout

### 🌬️ Interactive Guided Breathwork
Animated breathing circle with three techniques:
- **Box Breathing** (4-4-4-4)
- **4-7-8 Relaxing**
- **Physiological Sigh**

### 🧘 Somatic Grounding Guides
- **Neck & Shoulder Tension Melt** (3 min)
- **5-4-3-2-1 Sensory Grounding** (5 min)
- **Spine & Hip Decompression** (5 min)

### 📞 Malaysian Support Resources
Quick-access emergency modal and results-page directory featuring:
- **Talian HEAL (KKM)** — 15555
- **Befrienders KL** — 03-7627 2929
- **MIASA Malaysia** — 1-800-180-066 (also on WhatsApp)
- **Talian Kasih** — 019-261 5999 (WhatsApp)

### 🌐 Bilingual Interface
One-click toggle between **English** and **Bahasa Melayu** for all assessment questions.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| [Tailwind CSS](https://tailwindcss.com/) (CDN) | Styling and responsive layout |
| Vanilla JavaScript | Quiz logic, scoring, breathwork engine, language toggle |
| [Font Awesome 6](https://fontawesome.com/) | Icons |
| [Google Fonts](https://fonts.google.com/) | *Plus Jakarta Sans* and *Playfair Display* |

No build step, framework, or backend required. Everything lives in a single `index.html` file.

---

## 🚀 Getting Started

### Run locally
```bash
# Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git

# Move into the project folder
cd <your-repo-name>

# Open in your browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or simply double-click `index.html`. An internet connection is needed for the CDN-hosted Tailwind, fonts, and icons.

### Deploy with GitHub Pages
1. Push the project to a GitHub repository
2. Go to **Settings → Pages**
3. Under **Source**, choose the `main` branch and `/ (root)` folder
4. Save, and your site will be live at `https://<your-username>.github.io/<your-repo-name>/`

---

## 📁 Project Structure

```
.
├── index.html    # Entire application (markup, styles, and scripts)
└── README.md
```

---

## ⚠️ Disclaimer

TenangMind is an **educational self-reflection tool**. It is **not** a substitute for professional medical advice, diagnosis, or clinical treatment. The GAD-7 is a screening instrument, not a diagnostic one.

If you are in distress or need immediate help, please contact a qualified professional or one of the Malaysian helplines listed above. If you are in immediate danger, call **999**.

Helpline details may change over time, so please verify them with the official sources before relying on them.

---

## 🔒 Privacy

All assessment answers are processed **entirely in your browser**. No data is sent to or stored on any server.

---

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome. Feel free to open an issue or submit a pull request.

Ideas for future improvements:
- Additional languages (Mandarin, Tamil)
- Depression screening (PHQ-9)
- Saved history of past assessments (local storage)
- Offline support (PWA)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). *(Add a `LICENSE` file to your repository, or change this section to match your preferred license.)*

---

<p align="center">Made with 🌿 for mental wellbeing in Malaysia</p>
