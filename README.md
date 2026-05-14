# 🧩 Block Blast Prototype - Vibe Coder Assignment

A simplified web-based version of the core mechanics from the mobile hit **"Block Blast!"** by HungryStudio. This project was developed as part of the Vibe Coder evaluation for Infinity Games.

## 🔗 Project Links
* **Live Game:** [https://emystery.github.io](https://emystery.github.io)
* **Video Walkthrough (Loom):** [INSERT_YOUR_LOOM_LINK_HERE]

---

## 📝 Assignment Questions

**1. Which AI tools did you use, and how did you split the work between them?**
I utilized **Antigravity** for the initial structural scaffolding and the logic for the 8x8 grid system. I used **Gemini** to refine the UI/UX, handle the drag-and-drop event listeners, and implement the "Game Over" state check.

**2. What did the AI get wrong that you had to fix yourself?**
The AI initially struggled with the clearing logic for simultaneous row and column completions (combos). I had to manually adjust the script to ensure that if a block completed both a row and a column at once, both were cleared in the same frame and points were awarded correctly.

**3. Who is the target player for this game, and where can they be found?**
The target player is a hyper-casual gamer looking for short-burst, mentally stimulating puzzles. They are primarily found on mobile platforms and are often reached through short-form video ads on TikTok and Instagram that highlight "satisfying" gameplay loops.

**4. What's the one metric you'd watch in week one to decide if it's worth continuing?**
I would monitor **Day 1 Retention**. In the hyper-casual market, if players do not return for a second session within the first 24 hours, it indicates the core "hook" or satisfying feeling of the mechanic needs a pivot or the project should be killed.

**5. How would you get users to play this game?**
I would focus on creating "ASMR-style" gameplay videos showing large combos being cleared to generate organic interest on social media. Additionally, implementing a "daily high score" leaderboard would encourage social sharing and light competition among players.

---

## 🛠️ Tech Stack
* **Language:** Vanilla JavaScript (ES6+)
* **Styling:** CSS3 (Mobile-first responsive layout)
* **Structure:** HTML5 Canvas / DOM
* **AI Pair Programmers:** Google Antigravity & Gemini
* **Deployment:** GitHub Pages

---

## 📂 Prompt Log
The complete, unedited history of all prompts and AI responses used for this project can be found in the `PROMPTS.md` file within this repository.
