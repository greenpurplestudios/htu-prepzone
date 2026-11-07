# htu-prepzone
🎓 HTU PrepZone & HTU Run

HTU PrepZone is an all-in-one smart study web application built for university students to master exam preparation, featuring dynamic mock tests, interactive 3D flashcards, quick-lookup cheat sheets, and an authentic campus-themed 2D pixel platformer game called HTU Run!

Developed with ❤️ by greenpurplestudios.

🌟 Key Features

📚 1. Smart Exam Engine & Study Modes

Comprehensive Mock Exam: Pulls 15 randomized questions per attempt from an extensive bank of 55+ validated questions. Answers and options are shuffled dynamically so no two attempts are identical.

Mistakes-Only Mode (مراجعة أخطائي فقط): Tracks questions answered incorrectly across any test session in local browser storage and builds custom quizzes targeting only your weak areas.

Sudden Death Mode (التحدي القاتل): A high-intensity speed test providing 20 seconds per question where a single mistake results in an immediate game over.

Detailed Explanations & Review: Step-by-step rationales provided for every question and answer option.

🎮 2. HTU Run (2D Pixel Campus Platformer)

Custom Character Selection: Play as:

👦 Short-haired Male Student

🧑 Medium Wavy-haired Male Student

👧 Long-haired Female Student

🧕 Hijabi Female Student

Authentic Campus Landmarks: Custom pixel-art background reflecting the university's signature limestone facades, modern curved bridge architecture, and red landmark sculpture.

Thematic Obstacles & Collectibles: Jump over professors with exam clipboards, heavy textbook stacks, and campus bins while collecting Astrolabe Coffee ☕ cups for bonus points.

Cross-Platform Controls: Full support for desktop keyboard controls (Space / Up Arrow) and responsive touch-tap controls on mobile screens.

🏆 3. Daily Leaderboard (لوحة المتصدرين)

Local ranking system showcasing top student performers in both exam scores and HTU Run arcade records.

Personalized guest avatars and custom student display names.

🎴 4. 3D Flip Flashcards & Quick Reference Guide

Interactive 3D flip study cards for rapid memorization.

Searchable directory covering critical national dates, military ranks, insignias, unit structures, and legislation.

📝 5. Integrated Study Notebook & Feedback System

Auto-Saving Notebook: Instant local saving for study notes and reminders without requiring an account.

Student Feedback Box: Direct suggestion inbox stored locally with dedicated quick-link integration to Instagram (@greenpurplestudios).

🔒 6. Zero-Config Guest Accounts & Secure Admin Gateway

Guest Profiles: No emails, passwords, or signup barriers required.

Cryptographic Admin Protection: Protected using browser-native SHA-256 cryptographic hashing (crypto.subtle), keeping the administrative access passphrase securely obscured from direct source code inspection.

🛠️ Tech Stack

Frontend: Single-File Architecture (HTML5, CSS3, Vanilla JavaScript (ES6+))

Styling: Tailwind CSS CDN & Dark/Light mode engine

Icons & Fonts: Lucide Icons, Google Fonts (Cairo & Press Start 2P)

Arcade Graphics: Native HTML5 2D Canvas API (zero external game libraries)

Storage: Native localStorage Web API

🚀 Quick Start & Deployment Guide

Option 1: Run Locally

Clone or download this repository:

git clone https://github.com/<your-username>/htu-prepzone.git


Open index.html directly in any modern web browser (Google Chrome, Safari, Microsoft Edge, Firefox).

Option 2: Deploy Free on GitHub Pages

Create a new repository on GitHub named htu-prepzone.

Push or upload index.html and README.md to the main branch.

Open repository Settings ⚙️ $\rightarrow$ Pages (in the sidebar).

Under Build and deployment:

Source: Deploy from a branch

Branch: main / folder: / (root)

Click Save.

Your live site will be ready in under 60 seconds at:

https://<your-username>.github.io/htu-prepzone/


🔐 Administrative Access

The admin portal provides inspection of student feedback submissions and allows JSON export of the current question bank:

Click the Shield Icon in the top navigation bar.

Enter the administrative passphrase configured for the deployment.

🤝 Feedback & Credits

Created and maintained by greenpurplestudios.

For feature suggestions, subject additions, or bug reports, feel free to reach out via:

Instagram: @greenpurplestudios

All course reference materials and exam questions are adapted from designated curriculum study guides and past paper question banks.
