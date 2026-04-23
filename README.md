#LifeQuest: Dark Arcade Journal 🚀
Level up your life with a gamified productivity suite.

LifeQuest is a high-performance, "Dark Arcade" themed productivity application designed to turn daily discipline into an immersive RPG experience. Built with a sleek, neon-glassmorphism aesthetic, it combines task management, habit tracking, and pomodoro focus sessions with a deep gamification engine.

🛠 Features
🎮 Gamification Engine
XP & Leveling: Earn Experience Points (XP) for completing missions and honoring protocols. Progress through ranks from Rookie to Ascended.

Global Streaks: Maintain daily activity to build your fire. Includes a Freeze mechanic—earn one every 14 days to protect your streak during off-days.

Trophy Room: 17 unique unlockable awards (e.g., Night Owl, Perfectionist, Speed Runner) to celebrate your milestones.

Visual Feedback: Real-time confetti bursts and level-up flashes for dopamine-driven productivity.

📝 Mission Control (Tasks)
Priority-Based Rewards: Categorize tasks by priority (Low to Critical) to determine XP yield (10 to 100 XP).

Smart Filtering: Sort by missions due today, overdue tasks, or completed history.

Category Tracking: Organize work, study, health, and personal goals.

🔥 Habit Protocols
Daily Check-ins: Simple one-tap habit completion.

Streak Tracking: Monitor current and longest streaks per habit with visual fire icons.

7-Day Mini-History: A quick-glance sparkline for each habit to visualize your recent consistency.

⏱️ Focus Mode (Pomodoro)
Built-in timer with customizable intervals (25m Work, 5m/15m Breaks).

XP Bonuses: Earn 25 XP for every focus session completed.

Dynamic UI: Tab titles and headers update in real-time to keep you locked in.

📅 Data Logs (Calendar)
Activity Heatmap: View your historical productivity via a color-coded calendar.

Daily Breakdown: Click any date to see exactly which missions were completed and protocols honored on that day.

🎨 Design & Tech
Aesthetic: Dark Arcade / Cyberpunk.

Colors: Electric Violet, Cyan, and Amber accents on an OLED-friendly pitch-black background.

Stack: Pure HTML5, CSS3 (Custom Variables & Glassmorphism), and Vanilla JavaScript.

Data: Fully local-first. All progress is saved to localStorage.

Mobile Ready: Responsive sidebar that transforms into a bottom navigation bar for on-the-go questing.

🚀 Getting Started
Launch: Simply open index.html in any modern web browser.

Initialize: Set your Display Name and Avatar in Settings.

Deploy: Click the + FAB (Floating Action Button) to create your first Mission or Protocol.

Backup: Use the Export feature in Settings to download a JSON backup of your progress.

🛡️ Data Privacy
Your data never leaves your machine. LifeQuest operates entirely within your browser's local storage. To move your data to a different device, use the Export/Import tool in the Settings menu.

"The mission is simple: Become the best version of yourself, one XP at a time."# LifeQuest

#🛠️ Local Installation & Execution
1. Save the Code
Copy the code provided for the index.html file.

Create a new folder on your computer (e.g., Documents/LifeQuest).

Open a text editor (like VS Code, Notepad, or TextEdit).

Paste the code and save the file exactly as index.html.

2. Launch the Application
Method A (Double Click): Navigate to your folder and double-click the index.html file. It will open in your default web browser (Chrome, Firefox, or Edge recommended).

Method B (Drag and Drop): Open your browser and drag the index.html file directly into an empty tab.

3. (Optional) Run with a Local Server
If you are a developer and want to avoid potential "File Origin" issues or plan to expand the code, use a local server:

VS Code: Install the Live Server extension, right-click index.html, and select "Open with Live Server."

Python: If you have Python installed, open your terminal in that folder and run:

Bash
python -m http.server 8000
Then, go to http://localhost:8000 in your browser.

💡 Quick Start Tips for Shubh
Since you are currently working with HTML/CSS, JavaScript, and React, here are a few ways to personalize this locally:

Custom Themes: You can modify the CSS variables in the :root section to match your favorite coding environment.

Hardware Sync: Since you are interested in IoT and ESP32 projects, you could eventually use a local API to bridge this journal with a physical "Level Up" LED or buzzer using your Arduino skills.

Data Persistence: Remember that the data is stored in your browser's localStorage. If you clear your browser cache, your progress will be lost unless you use the Export Backup JSON button in the Settings.

🛡️ Troubleshooting
Blank Screen? Ensure the file extension is .html and not .html.txt.

Icons not showing? The app uses standard emojis and Google Fonts. Ensure you have an active internet connection for the fonts to load properly from the CDN.