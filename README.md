# BM Macro 🗡️ Blade & Soul Optimization Tool

BM Macro is an **advanced gameplay enhancement tool** for the **Blade Master** class in *Blade & Soul Neo*. It automates skill sequences and optimizes in-game event detection to improve **combat accuracy and efficiency**.

---

## 🚀 Key Features

- **Operation Modes:**  
  - **Puncture:** Time-based macros with critic detection for Puncture/Pierce Build 
  - **Hybrid:** Visual detection (Pixel Search) to react to in-game events for Hybrid Fire build
- **Configurable Macros:** Customize key sequences, loops, and wait times
- **Intelligent Detection System:** Adaptive algorithms for critical text detection, color pre-filtering, dynamic search radius
- **Preset Management:** Save/load local or cloud configurations
- **Automatic Updates:** Always stay updated with the latest improvements
- **Graphical User Interface (GUI):** Easy configuration and macro flow visualization

---

## ⚙️ Installation & Usage

1. **Download & Extract:**  
   [Download](https://github.com/hamulyn/bmmacro/releases/latest) the executable or extract it to your desired folder.
2. **Configure `config.ini`:**  
   Automatically generated with editable settings.
3. **Run `BM_Macro.exe`:**  
   Login or register to access main script.
4. **Adjust Settings:**  
   Use the GUI to configure hotkeys, timings, and operation modes.

---

## 📖 Full User Manual

### 1️⃣ Interface & Navigation

- **Login/Registration Screen:** Required for cloud features  
- **Main Menu (Hotkey: `Delete`):** Control center to access all other GUIs

---

### 2️⃣ Default Hotkey Settings

| Function                | Default Hotkey |
|-------------------------|----------------|
| Macro 1                 | XButton1       |
| Macro 2                 | XButton2       |
| Menu                    | Delete         |
| Suspend                 | F12            |
| Toggle Mode (Puncture/Hybrid) | Home     |

---

### 3️⃣ Operation Modes

#### Puncture Mode
Executes skills based on **Crit**.

#### Hybrid Mode
Combines key sequences with visual detection of on-screen events, such as **Focus** consume.

---

### 4️⃣ Detection Settings
**Configurable via the GUI**

- Optimized algorithms for text detection (like critical hits)
- Detection Area: Coordinates puncture_x1, puncture_y1, puncture_x2, puncture_y2 define the screen area to search.
- Critical Text Color: Configure color to improve detection accuracy.
- Confidence Threshold: min_confidence_threshold and max_confidence_threshold define detection validity.

---

### 5️⃣ Preset Management

- Local Presets: Saved on your computer, ideal for personal backups.
- Cloud Presets: Synchronized with your account, accessible from any computer and shareable with other users.

---

### 6️⃣ Common Troubleshooting

- Macro not working: Ensure the macro is not suspended (F12) and the correct mode is selected.
- Connection Issues: Tool will try to reconnect automatically; check your internet connection if it fails.
- Low Performance: Adjust the search area,confidence thresholds,patterns and others settings in the GUI.
- Update Failed: Tool tries to download updates from GitHub. If it fails, check your connection or download manually.
