# 🛸 BUBBLES GB — Cybernetic Matrix & Tactical Interest Leaderboard

**Bubbles GB** is a futuristic, interactive web dashboard designed to track, rank, and analyze your personal interests, hobbies, and tactical focus areas. Built with a cyberpunk HUD interface, real-time analytics, mission history logging, and drag-and-drop reordering, it serves as a dynamic command center for your personal goals and lifestyle matrix.

---

## ✨ Features & Capabilities

- **Cybernetic HUD Interface:** Sleek dark-mode aesthetic with holographic neon accents, glowing status indicators, and responsive grid/list layouts.
- **Operator Override Mode:** Secure admin mode (authenticated via passcode `boogieis15`) allowing drag-and-drop node re-ranking, node additions, and inline editing.
- **Dynamic Rank Tracking:** Real-time visual rank indicators, climb/drop deltas, and visual score indicators (1–100 scale).
- **Mission History Vault:** Save dated snapshot records ("Mission Logs") of your top priorities to track how your focus evolves over time.
- **Telemetry Analytics:** Instant breakdown of your node matrix by category distribution and top-scoring interests.
- **Portable JSON Sync:** Export and import your complete database snapshot for seamless device migration and backup.
- **Cloud & Local Persistence:** Syncs with Firebase Firestore when online, with an automatic fallback to browser LocalStorage.

---

## 🔒 Security & Operator Access

To modify rank order, add new nodes, or edit existing items:
1. Click the **OPERATOR** button in the top HUD.
2. Enter the security passcode:
   ```text
   boogieis15
   ```
3. Once engaged, drag cards using the handle, or use the quick arrow keys to shift rankings.

---

## 🚀 Quick Start

1. Open `index.html` in any modern web browser.
2. Filter or search interests using the top matrix controls.
3. Switch between **Grid View** and **List View** to adjust visual density.
4. Access **ANALYTICS** or **VAULT** to inspect node breakdowns and previous mission logs.

---

## 🛠️ Tech Stack

- **HTML5 & Tailwind CSS** (Cyberpunk theme extension)
- **JavaScript (ES6+)**
- **Lucide Icons**
- **Firebase Firestore / Auth** (Optional cloud sync with local fallback)
