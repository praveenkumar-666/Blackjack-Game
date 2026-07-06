# Blackjack Game

A classic, interactive web-based Blackjack game built using HTML, CSS, and vanilla JavaScript. Test your luck against the deck to see if you can hit 21 without busting!

---

## 🎮 Game Interface Overview

The game features a casino-themed green aesthetic with direct interactive elements:

* **Casino Style Theme:** A deep green background (`rgb(0, 106, 49)`) paired with goldenrod accents.


* **Dynamic Information Displays:** Live trackers showing your current cards, total sum, and remaining player chips.


* **Interactive Control Buttons:** Dynamic buttons to start the game and request a new card.



---

## 🚀 Features

* **Dynamic Card Generation:** The game utilizes standard Blackjack point assignment rules where Aces are worth 11 and face cards (Jack, Queen, King) are worth 10.


* **Real-time Game State Logic:** Automatically tracks your card total and updates the display contextually:


* Prompts you to draw another card if your sum is 20 or lower.


* Celebrates your win with a *"Wohooo! You've got BlackJack!"* message if you land exactly on 21.


* Alerts you that *"you're out of game!"* if you bust (go over 21).




* **Player Profiles:** Keeps track of player names and available chip stacks.



---

## 🛠️ File Structure

The project consists of three core files:

* `index.html` - Handles the markup structure and DOM element mapping.


* `index.css` - Manages visual styling, centering layouts, sizing headers, and custom button animations.


* `script.js` - Contains the algorithmic game logic, random array generations, state tracking, and mathematical conditions.



---

## 🎮 How to Play

1. **Launch the Game:** Open the `index.html` file in any modern web browser.


2. **Start a Round:** Click the **START GAME** button to draw your first two random cards.


3. **Draw Cards:**
* If your sum is below 21, evaluate your hand and click **NEW CARD** to hit and add another card to your total.


* If you hit 21 exactly, you win the round!


* If your total passes 21, you bust and the round ends.
