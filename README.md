# cafe-portfolio
# ☕ aschauhan-dev cafe

> *Brewing clean code & community growth by the cup.*

[![Live Site](https://img.shields.io/badge/Live-aschauhan--dev--cafe-c48b52?style=for-the-badge&logo=coffeescript&logoColor=white)](https://mraschauhan.github.io/aschauhan-dev-cafe/)
[![License: MIT](https://img.shields.io/badge/License-MIT-345240?style=for-the-badge)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-26160c?style=for-the-badge)](#)

```text
    (  )   (   )  )
     ) (   )  (  (
     ( )  (    ) )
     _____________
    <_____________> ___
    |             |/ _ \
    |  ASCHAUHAN  | | | |
    |   - DEV -   |_| | |
    |    CAFE     |\___/
    \             /
     `-----------'
```

Welcome to **aschauhan-dev cafe**, an artisanal coffeehouse-themed developer portfolio crafted for **Adarsh Singh Chauhan** — Computer Science & Engineering undergraduate at **Barkatullah University Institute of Technology (BUIT), Bhopal** (Batch 2025–2029).

This project reimagines the traditional developer portfolio as an interactive cafe experience, complete with ambient sound synthesis, a working barista order pad with thermal receipts, and a community corkboard.

---

## ☕ Key Features

### 1. 📋 Functional Barista Order Slip & Live Receipt
- **AJAX Form Submissions:** Powered by [FormSubmit](https://formsubmit.co/) (`Accept: application/json`) to deliver inquiries directly to `mraschauhan1@gmail.com` without page refreshes or external backend dependencies.
- **Dynamic Quick-Pick Chips:** Pre-fills specifications for *Web Crafting*, *Campus Growth*, *Cloud Systems*, or *Custom Roasts*.
- **Sweetener & Scope Selectors:** Custom pricing and scope toggles (*Low Sugar / Quick MVP*, *Balanced Roast / Full Build*, *Double Shot / Enterprise*).
- **Live Thermal Receipt Preview:** Updates in real time with line items, dynamic timestamps, randomized ticket ID generation, and an authentic CSS sawtooth receipt edge.
- **Stamp & Audio Trigger:** Fires an in-browser Web Audio synthesized counter chime and stamps the receipt `[SERVED & DISPATCHED]` on completion.
- **Fallback Email & Print:** Built-in structured `mailto:` action and thermal slip print engine (`window.print()`).

### 2. 📌 Interactive Community Corkboard
- Real-time post-it notes with randomized tilt angles (`--rot`) and artisan color palettes.
- Submitting an order slip automatically pins a new ticket note to the bulletin board.
- Persistent across page reloads using browser `localStorage`.
- Includes pre-seeded greetings from peers and collaborators (e.g., Rohit, Devansh, Mansi).

### 3. 🎵 Pure Web Audio Ambient Lofi Engine
- Zero external MP3 or streaming bandwidth requirements.
- Generates procedural pink noise (gentle rain) through a biquad lowpass filter.
- Synthesizes vinyl record clicks and pops using random oscillator bursts and rapid gain ramps.

### 4. 🌗 Morning Latte & Midnight Espresso Themes
- Seamless light/dark mode switcher honoring system preference and saved `localStorage` state.
- Tailored color palette built on espresso browns (`#140a05`, `#26160c`), creamy lattes (`#fdfbf7`, `#ede1d2`), and sage accents (`#587e66`).

### 5. 🖼️ Barista Polaroid & Client-Side Image Swapper
- Polaroid-style portrait frame with CSS paperclip accents.
- Built-in file uploader that allows instant local image previewing and caching inside `localStorage`.

### 6. 📜 Academic & Experience Showcase
- **Classroom Roast Ledger:** Detailed academic merit records for BUIT Bhopal, School of Excellence Sidhi (90.6%), and Sarvodaya Vidya Mandir (94.8%).
- **Specialty Roasts:** Professional roles across **Gradientts** (Campus Growth Associate Intern), **Air India Limited** (Campus Ambassador), and **Internshala** (ISP).
- **Pantry Jars & Certifications:** Interactive skill jars showcasing competencies in HTML with AI, CSS3, Cloud Computing, Brand Management, Social Media Marketing, and Effective Leadership.

---

## 🛠️ Tech Stack

- **Markup & Semantics:** HTML5
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (CDN) with custom extended palette
- **Typography:** Fraunces (Headings), Plus Jakarta Sans (Body), Caveat (Script/Chalkboard), Space Mono (Receipts)
- **Icons:** Font Awesome 6.5
- **Audio:** Web Audio API (Synthesizers & Filters)
- **Form Handling:** FormSubmit AJAX API
- **State Management:** Native JavaScript (ES6+) with `localStorage`

---

## 📁 Project Structure

```text
aschauhan-dev-cafe/
│
├── index.html                           # Complete single-file application
├── README.md                            # Documentation
├── IMG_20260305_015141_825_2.webp       # Default barista portrait
└── Gemini_Generated_Image_dgbu0zdgbu0zdgbu.png  # Brand mascot logo (optional asset)
```

---

## 🚀 Quick Start & Local Development

No Node.js runtime or build step required. The application runs immediately in any modern browser.

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/aschauhan-dev-cafe.git
cd aschauhan-dev-cafe
```

### 2. Run Locally
You can open `index.html` directly in your browser:
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

Or serve via any simple local HTTP server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (npx)
npx serve
```
Then navigate to `http://localhost:8000` in your browser.

---

## 🌐 Deployment to GitHub Pages

1. Push your code to your GitHub repository on the `main` branch:
   ```bash
   git add .
   git commit -m "feat: initial release of aschauhan-dev cafe"
   git branch -M main
   git remote add origin https://github.com/YOUR_GITHUB_USERNAME/aschauhan-dev-cafe.git
   git push -u origin main
   ```
2. Navigate to your repository on GitHub.
3. Go to **Settings** > **Pages** (under the "Code and automation" section).
4. Under **Build and deployment**:
   - **Source:** Select `Deploy from a branch`.
   - **Branch:** Select `main` and keep the directory as `/(root)`.
5. Click **Save**. Your site will be live within 1–2 minutes at:
   `https://YOUR_GITHUB_USERNAME.github.io/aschauhan-dev-cafe/`

---


## 👤 Barista Details

**Adarsh Singh Chauhan**  
*Undergraduate Computer Science & Engineering Scholar*  
**Barkatullah University Institute of Technology (BUIT), Bhopal**

- 📧 **Email:** [mraschauhan1@gmail.com](mailto:mraschauhan1@gmail.com)
- 📸 **Instagram:** [@a.s.chauhxn](https://instagram.com/a.s.chauhxn)
- 📍 **Location:** Bhopal, Madhya Pradesh, India

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE). Feel free to fork, customize the roasts, and brew your own portfolio!
