# Wizard: Middle-earth Master 🧙‍♂️💍

A fully featured, Lord of the Rings-themed digital scorekeeper for the **Wizard Card Game**. Built with pure HTML, CSS, and Vanilla JavaScript, this app replaces pen and paper with an animated, responsive, and mathematically secure scoring dashboard.

## ✨ Features

* **Middle-earth Theme:** Features a glassmorphism UI overlaying a classic map of Middle-earth, complete with a CSS-animated horse and cart journeying across the screen.
* **Official Wizard Scoring:** Automatically calculates the +20 bonus and +10 per trick for correct bids, and penalizes -10 points per trick difference for missed bids.
* **Dynamic Trick Counter:** Real-time validation ensures the table doesn't enter mathematically impossible trick combinations.
* **The Chronicle (Live Standings):** A persistent, responsive sidebar that tracks total scores and round-by-round point deltas.
* **Time-Travel (Undo System):** Made a typo? Robust "Back" buttons allow the Scoremaster to step backward through the Bidding and Results phases, or even undo a completed round's math safely.
* **Custom Game Setup:** Supports 3 to 10 players, standard or Wizard decks, and full or custom game lengths.
* **Data Loss Prevention:** Built-in browser warnings prevent accidental page refreshes from erasing the game state.

## 📂 Project Structure

To run this app, you only need two files in the same directory:
1. `index.html` (The main application code)
2. `image_4de622.jpg` (The Middle-earth background map)

## 🚀 How to Run (Local)

1. Create a new folder on your computer.
2. Save the application code as `index.html`.
3. Save your Middle-earth map image in the same folder and ensure it is named `image_4de622.jpg`.
4. Double-click `index.html` to open it in any modern web browser (Chrome, Safari, Firefox, Edge). 

## 📱 How to Install on iOS/Android (Web App)

You can host this app for free to use it as a mobile app at the gaming table:

1. Upload `index.html` and `image_4de622.jpg` to a free GitHub repository.
2. Deploy the repository using a free service like **Vercel** or **GitHub Pages**.
3. Open the live deployment link in Safari (iOS) or Chrome (Android).
4. Tap the **Share** button and select **"Add to Home Screen"**.
5. The app will now launch in full-screen mode like a native application!

## 🎲 App Flow & How to Use

1. **Setup:** Select your player count, deck type, and game length. The app will automatically calculate how many physical decks you need to shuffle together for the final round.
2. **The Fellowship:** Enter the names of all players at the table.
3. **Bidding Phase:** As players declare their bids, the Scoremaster enters them. The Trick Counter will display if the table is overbidding or underbidding the round.
4. **Results Phase:** After the hand is played, enter the *actual* number of tricks won by each player. The Trick Counter will turn green when exactly 100% of the round's tricks are accounted for.
5. **Score Screen:** View the updated Chronicle. If a mistake was made, use the "Undo Scores" button to go back. Otherwise, click "Continue Journey" to advance to the next round.

## ⚖️ Scoring Rules Implemented

This app strictly follows the standard Wizard scoring rules:
* You must make your **EXACT** bid to win points.
* **Correct Bid:** Earn a 20-point bonus, plus 10 points for each trick taken.
* **Incorrect Bid:** Lose 10 points for each trick you are over or under your bid.

---
*“Not all those who wander are lost... but those who miscount their tricks certainly lose.”*
