# SortRush

A web-based categorization race with real-time progress tracking, built with React, Vite, and Tailwind CSS.

## Run in VS Code
1. Extract the folder and open it in **VS Code** (`File → Open Folder`).
2. Open the integrated terminal (`Ctrl + ~`).
3. Install dependencies and start the local server:
   ```bash
   npm install
   npm run dev
   ```
4. `Ctrl + Click` the `http://localhost:5173` link in the terminal.

## Game Modes
- **Solo vs. Bot:** Pick a deck and difficulty (`Easy`, `Medium`, `Hard`), then click **Start Practice Race**.
- **Same-PC 1v1 (1 Keyboard):** Split-screen local play on one computer using the same seeded card queue:
  - **Player 1:** `A` (Left bin) / `D` (Right bin)
  - **Player 2:** `←` (Left bin) / `→` (Right bin)
- **1v1 Live Room (2 Browser Tabs):**
  1. Open `http://localhost:5173` in **Tab 1** and click **Host New Room** to get a 4-character room code.
  2. Open `http://localhost:5173` in **Tab 2**, enter the room code, and click **Join**.
  3. Both players can pick their desired **Category Deck**—if they pick different decks, a **Random Deck Roulette** chooses between them before the countdown starts.
