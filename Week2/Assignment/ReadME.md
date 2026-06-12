# 🎲 React Dice Game – Assignment

It's time to roll the dice.

This Week 2 assignment will help you apply everything you've learned about **React** so far. You'll build a small but fun game that involves number picking, random chance, score tracking, and a bit of luck (but mostly logic).

---

## 📝 Problem Statement

Build a **React-based dice game** that lets users:
- Select a number between 1 and 6
- Roll a dice
- Gain or lose points based on the result

Yes, it's like gambling — but educational.

---

## 📋 Game Rules

- Select a number between 1–6 before rolling.
- On clicking **"Roll Dice"**, a dice face appears randomly.
- If your selection **matches** the dice roll:
  - You score **+N points** (N = selected number)
- If it doesn't:
  - You lose **2 points**
- Include a **Reset Score** button
- Show an **error** if the user tries to roll without selecting a number
- Add a button to **toggle the rules** (because we all forget them)

---

## 🛠 Min. Required Features

-  Number selection (1–6) with clear visual feedback
-  Random dice roll (with dice face image)
-  Score updates in real-time
-  Reset score functionality
-  Toggle to show/hide rules
-  Error handling for missing number selection
-  Responsive layout that works on all screens

---

## 🛠 Optional Features (only frontend i.e. store locally)

-  Roll History: Store and display the last 5 rolls.
-  Track the highest score achieved during the session.
-  Dark Mode
-  Leaderboard: Store multiple game sessions
-  Statistics Dashboard (Show: Total Rolls, Correct Guesses, Wrong Guesses, Accuracy %)
-  You are free to add more features

---

## 🧩 Suggested Components (Just for reference, you can create as your choice)

- `App`: Manages global game state and navigation
- `Home`: A simple landing page with a start button and a friendly dice image
- `Game`: Core gameplay — number selection, dice roll, score logic
- `Box`: For rendering selectable numbers (1–6)
- `Button`: A reusable component for all clickable buttons

---

## 🧑‍💻 Tech Stack

- **React.js** (v18+)
- **Functional Components**
- **Hooks** (`useState`, `useContext`)
- **React Context API** (to share state globally)
- **CSS Modules** or any styling approach you're comfortable with

---

## 🎥 Assignment Walkthrough - A video to make you understand it simply

[![Watch Assignment Explanation](https://img.youtube.com/vi/I9fNyYl4_yo/hqdefault.jpg)](https://drive.google.com/file/d/1lXqyW8Wn_BCxA0h4dM3a6tFRsRa11XW2/view?usp=sharing)


This video will help you understand how the Dice Game works and to make it clear you don't need to replicate this, you can come up with better designs and extra features but try to have the functionalities as it is.

## 📅 Submission Details

- **Deadline:** 13th June 2026, 11:59 PM
- **Submit here:** [Assignment Submission Form](https://forms.gle/E2e7GfybJdjCm2rf8)

---

## 💡 Tips

- Don't overthink — start small and test your logic.
- Make sure your score logic is solid before styling it pretty.
- Use [React Docs](https://react.dev/learn) if something doesn’t make sense (which is normal).
- And no, you don’t have to actually shake your laptop to roll the dice — just click a button.

---

Good luck — may the odds (and the dice) be in your favor!
