# SMART INDIA HACKATHON 2026 — INAUGURATION EXPERIENCE
## Terna Engineering College, Navi Mumbai | Managed by Intellecta

A professional, offline-first, cinematic interactive inauguration presentation designed specifically for projection at official college events.

---

## 🚀 HOW TO RUN FOR THE EVENT

### Method 1: Direct File Open (Recommended)
1. Open the project folder on the presentation laptop.
2. Double-click **`index.html`** to open it in Google Chrome, Microsoft Edge, or any modern Web Browser.
3. Press **`F`** on your keyboard to enter Fullscreen mode.
4. The presentation is now ready for the Principal/Dignitary.

### Method 2: Local Server (Optional)
If your browser restricts local file loading or audio playback:
```bash
python -m http.server 8080
```
Then open `http://localhost:8080` in your browser and press **`F`** for fullscreen.

### Method 3: GitHub Pages (Online)
Push this repository to GitHub and enable GitHub Pages from Settings → Pages → Deploy from branch (main). The `.nojekyll` file is already included.

---

## 📱 MOBILE REMOTE CONTROL (ZERO PYTHON / GITHUB PAGES COMPATIBLE)

You can trigger the inauguration presentation directly from your mobile phone!

1. **Open `remote.html` on your phone**:
   - **Local**: Open `remote.html` in your phone's browser (or host locally / access via GitHub Pages).
   - **GitHub Pages**: Open `https://<your-username>.github.io/<repo-name>/remote.html` on your phone.
2. Tap the big glowing **`PRESS ENTER [ LAUNCH INAUGURATION ]`** button.
3. The presentation running on the projector laptop will instantly receive the JS Webhook signal and launch the experience!

---

## 🎬 PRINCIPAL & EVENT FLOW (100% AUTOMATED)

1. **Pre-Launch Screen (Scene 0)**
   - The screen displays ambient tactical command headers and institutional branding.
   - The Principal approaches the laptop (or you tap the button on your phone!).

2. **Principal Action: PRESS ENTER ONCE (or Tap Mobile Remote)**
   - Pressing **ENTER** (or tapping Mobile Remote) automatically enters Fullscreen mode, starts the **BGM soundtrack**, and runs the entire **Master Inauguration Sequence**:
     1. **System Activation**: Energy core lock & status pulse (3s)
     2. **Tactical Countdown**: Fullscreen **03 → 02 → 01** (4.2s)
     3. **SIH Reveal**: Hero launch of Smart India Hackathon 2026 (4.5s)
     4. **Live Announcement**: *"THE WAIT IS OVER."* → *"IS NOW LIVE."* (**Extended: 12 seconds**)
     5. **Terna Institutional Reveal**: Dedicated Terna Engineering College screen (4s)
     6. **IIC Innovation Reveal**: Institution's Innovation Council screen (4s)
     7. **Intellecta Dedicated Reveal**: Logo reveal with motto (5s)
     8. **Hackathon Overview**: 8-Hour Offline Telemetry (4.5s)
     9. **Tracks**: Software Edition vs. Hardware Edition (5s)
     10. **Mission Timeline**: Interactive timeline with Judging Session highlight (5.5s)
     11. **The Challenge**: Ideate • Build • Present • Win (5.5s)
     12. **Final Hero Lockup**: Permanent closing lockup showing all major brand logos (HOLDS INDEFINITELY)

   - **Total automated runtime: ~60 seconds**
   - **BGM loops continuously** throughout the entire experience.

---

## ⌨️ KEYBOARD SHORTCUTS (OPERATOR / TESTING)

| Key | Action |
|---|---|
| **ENTER** | Launch inauguration sequence (Single press, Scene 0) |
| **F** | Toggle Fullscreen mode |
| **M** | Toggle Mute / Unmute BGM audio |
| **R** / **P** | Restart presentation to Pre-Launch screen |
| **SPACE** / **RIGHT ARROW** | Advance scene manually (Testing/Operator override) |
| **LEFT ARROW** | Previous scene (Testing/Operator override) |
| **CTRL + SHIFT + D** | Toggle Operator Debug HUD |

---

## 📁 ASSET STRUCTURE

```
├── index.html                   # Complete single-file presentation application
├── remote.html                  # Mobile web remote controller
├── README.md                    # Event operational guide
├── .nojekyll                    # GitHub Pages bypass file
└── assets/
    ├── bgm.mp3                  # Background music (Valorant Champions BGM)
    ├── logos/
    │   ├── terna.png            # Terna Engineering College logo
    │   ├── iic.png              # Institution's Innovation Council logo
    │   ├── sih.png              # Smart India Hackathon logo
    │   └── intellecta.png       # Intellecta vector logo
    ├── references/              # Event poster artwork references
    └── optional/                # Optional campus background images
```

---

## 🛡️ EVENT SAFETY & FAILSAFE GUARANTEES

This application was engineered specifically for live college event reliability:
1. **100% Automated Master Timeline**: Zero reliance on manual slide switching during the live launch.
2. **Offline-First Execution**: Local ENTER key works 100% offline without any network requirement.
3. **JS Webhooks (Mobile Remote)**: Uses Server-Sent Events (`ntfy.sh`), 100% compatible with static GitHub Pages without needing Python servers.
4. **BGM Audio**: Plays automatically on ENTER / Remote trigger and loops throughout. Press **M** to mute/unmute.
5. **Indefinite Final Hold**: Holds permanently on Scene 12 (Final Hero Lockup) without looping back to Scene 0.
6. **No Scrollbars**: Rigid viewport bounds (`100vw` / `100vh`) with `overflow: hidden`.
7. **GitHub Pages Ready**: All assets use relative paths with clean filenames. `.nojekyll` included.
