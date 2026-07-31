# ⚔️ Chore RPG

> **Turn real-life household productivity into an epic tabletop campaign!**

**Chore RPG** is a lightweight, zero-dependency, single-file web application designed to gamify household chores through a structured 30-minute productivity and rest loop. Complete chores to earn extra dice (`d4`, `d6`, `d8`), build your party roster, and unleash your combat dice pool against mythical threat levels!

---

## ✨ Features

- 🧹 **Work Phase (Quest Board):** Check off real-world tasks (cleaning, organizing, maintenance) to collect bonus dice for your total pool.
- 🛡️ **Dynamic Party Size Scaling (1 to 4 Players):** Adjust your active roster size on the fly. Required target encounter DCs dynamically recalculate so solo players or smaller groups face balanced difficulty targets.
- 🎨 **Expanded Hero Customization & Icon Selection:** Edit hero profiles with custom names, classes, and a wide array of icons—ranging from cute/whimsical archetypes (Fairies, Princesses, Unicorn Knights) to classic D&D classes (Paladins, Wizards, Rogues).
- 🗑️ **Saved Hero Library & Deletion:** Quick-swap visiting guests or saved characters from a dropdown library. Delete unused or accidental profiles directly from the hero edit menu.
- ⚔️ **Encounter Arena:** Face off against enemies with threat levels scaled dynamically to your party, or set custom target difficulties.
- 🏅 **MVP Selection & Combat Log:** Designate a standout hero for each fight and track your campaign's victory and defeat timeline.
- 🍀 **Luck & Reroll Mechanics:** Spend limited Luck points to reroll low base `d20` rolls during clutch encounters.
- 💾 **Automatic Saving (`localStorage`):** Progress, party settings, player libraries, and quest logs are saved automatically in browser storage.
- 📥 **Export & Import Save Backups:** Easily backup your campaign to a JSON file (`ChoreRPG_Save_YYYY-MM-DD.json`) or transfer save history between devices.
- 📱 **Mobile & iOS Friendly:** Fully responsive design built with Tailwind CSS. Can be added directly to your mobile Home Screen as a standalone web app.

---

## 🚀 Quick Start & Deployment

### Running Locally
1. Download or clone this repository.
2. Open `index.html` directly in any modern web browser (Safari, Chrome, Firefox, Edge).

### Hosting via GitHub Pages (Recommended)
1. Push your repository to GitHub.
2. In your repository, go to **Settings** > **Pages**.
3. Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/ (root)`.
4. Click **Save**. Within 1–2 minutes, your app will be live at:
   `https://<your-username>.github.io/<your-repo-name>/`

---

## 📱 How to Run as an App on iOS / Mobile

1. Open your live GitHub Pages URL in **Safari** on your iPhone or iPad.
2. Tap the **Share** icon (the square with an upward arrow at the bottom of the screen).
3. Scroll down and select **Add to Home Screen**.
4. Launch **Chore RPG** directly from your home screen like a native app!

---

## 📖 The 30-Minute Gameplay Loop

+-------------------------------------------------------------+
|                   30-MINUTE BLOCK                           |
+-------------------------------------------------------------+
|                                                             |
|   1. SET ROSTER     -->  Choose Party Size (1–4 Players)    |
|                          Customize heroes, icons, & classes |
|                                                             |
|   2. WORK PHASE     -->  Spend 20-25 mins doing chores      |
|                          Check off quests = Earn bonus dice |
|                                                             |
|   3. ENCOUNTER ARENA --> Set Threat DC (Auto-scales to size)|
|                          Tag MVP & unleash total dice pool! |
|                                                             |
|   4. BACKUP DATA    -->  Use Export/Import to save history  |
|                                                             |
+-------------------------------------------------------------+

---

## 💡 Customizable Chore Preset Ideas

Need inspiration for structuring your quest board? Here are recommended real-world task categories to pair with dice rewards:

| Real-World Chore | Fantasy Quest Name | Reward Dice |
| :--- | :--- | :--- |
| Clear & wipe dining table | *Purify the Grand Dining Hall* | `+1 d4` |
| Take out trash & recycling | *Clear the Dungeon Refuse* | `+1 d4` |
| Vacuum main room / hallways | *Banish the Dust Elementals* | `+1 d6` |
| Fold and put away laundry | *Sort the Armor Inventory* | `+1 d6` |
| Deep clean bathroom | *Scrub the Alchemist's Lab* | `+1 d8` |
| Mop or scrub kitchen floors | *Scour the Overlord's Fortress* | `+1 d8` |

---

## 🛠️ Built With

- **HTML5 & Vanilla JavaScript (ES6+)** – Zero external frameworks required.
- **Tailwind CSS (CDN)** – Clean, modern, dark-mode visual interface.
- **Web Storage API (`localStorage`)** – Persistent state retention across sessions.
- **FileReader & Blob API** – Client-side JSON file export and import.

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.
