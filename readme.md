# 🎮 Number Baseball Game (HTML5 + CSS)

This is a lightweight **Number Baseball Game** built using **only HTML5 and CSS**, generated using **Amazon Q CLI** for the [AWS Game Challenge Event](https://community.aws/content/2xIoduO0xhkhUApQpVUIqBFGmAc/build-games-with-amazon-q-cli-and-score-a-t-shirt).

![Screenshot](screenshots/Screenshot-v2-1.png)
![Screenshot](screenshots/Screenshot-v2-2.png)
![Screenshot](screenshots/Screenshot-v2-3.png)

---

## 🧠 My Prompt to Amazon Q CLI

> **First Prompt:**  
> _Make a number-baseball game in HTML5 and CSS only, in the folder of `/Users/kabkee/Downloads`._

> **Second Prompt:**  
> _That's a great result and I like the design as well. I'd like to add a feature that the user can switch the digit numbers 3 to 4. The 3-digit baseball game is original one but somehow quite easy._

Amazon Q CLI interpreted the prompt and generated a fully functional number baseball game in a single `.html` file. It now supports both **3-digit** (Easy) and **4-digit** (Hard) gameplay!

---

## 🚀 Features

- 🎨 Clean, responsive design with modern styling
- 🔢 3-digit or 4-digit number input with auto-focus navigation
- ✅ Real-time validation (unique digits only)
- 🧠 Strike & Ball feedback after each guess
- 🧾 Guess history display
- 🎉 Win detection + celebration message
- 📱 Mobile-friendly layout
- 💫 Smooth animations and hover effects
- ⚙️ Difficulty selector (3-digit Easy / 4-digit Hard)

---

## 🎯 Game Rules

1. The computer generates a random 3-digit or 4-digit number (all digits are unique).
2. You guess the number using the input fields.
3. After each guess, you'll get:
   - **Strikes**: correct digit in the correct position.
   - **Balls**: correct digit but in the wrong position.
4. Get **3 or 4 strikes** (depending on difficulty) to win!

---

## 🧩 Mechanics

- All digits must be **unique** (0–9)
- Attempts are counted and displayed
- Guess history is retained
- Difficulty can be changed at any time (auto-reset)
- You can **restart** anytime

> ℹ️ The secret number is logged to the browser console for testing purposes — you can remove that line for actual gameplay.

---

## 🕹️ How to Play

Simply open the file in your browser: