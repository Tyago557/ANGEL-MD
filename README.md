🤖 ANGEL-MD- WHATSAPP BOT 

![ANGEL-MD Banner](https://img1.pixhost.to/images/6331/608513148_imgtmp.jpg)

![GitHub stars](https://img.shields.io/github/stars/Tyago557/ANGEL-MD?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/Tyago557/ANGEL-MD?style=flat-square)
![GitHub license](https://img.shields.io/github/license/Tyago557/ANGEL-MD?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/Tyago557/ANGEL-MD?style=flat-square)

---

🚀 Introduction

*ANGEL MD* is a powerful and feature-rich WhatsApp bot built using Node.js and the latest version of [Baileys](https://github.com/whiskeysockets/baileys). Designed for scalability and ease of use, ANGEL MD offers a wide range of commands and functionalities to enhance your WhatsApp experience.

---

🧠 Features

- ✅ *Fully Functional Commands*: All commands are operational and tested.
- 🛠️ *Easy Deployment*: Deploy via panel or manually with minimal setup.
- 🔄 *Auto-Updates*: Stay up-to-date with the latest features and fixes.

- - 📁 *Session Management*: Generate and manage sessions effortlessly.
- 🌐 *Multi-Platform Support*: Compatible with various deployment platforms.


---

🔧 Getting Started

1. Fork the Repository

Click the button below to fork the ANGEL MD repository:

[![Fork CRAZ](https://img.shields.io/badge/Fork%20ANGEL%20MD-Click%20Here-blue?style=for-the-badge&logo=github)](https://github.com/Tyago557/ANGEL-MD/fork)

2. Generate Session

Use the session generator to create your WhatsApp session:

[![Generate Session](https://img.shields.io/badge/Generate%20Session-Click%20Here-green?style=for-the-badge&logo=whatsapp)](https://crazy-sess.onrender.com)

3. Deploy the Bot

Choose your preferred deployment method:

[![Deploy on Render](https://img.shields.io/badge/Deploy%20on-Render-blue?style=for-the-badge&logo=render)](https://render.com/)


[![Deploy on Heroku](https://img.shields.io/badge/Deploy%20on-Heroku-purple?style=for-the-badge&logo=heroku)](https://heroku.com/)


[![Deploy on Railway](https://img.shields.io/badge/Deploy%20on-Railway-black?style=for-the-badge&logo=railway)](https://railway.app/)

[![Deploy on katabump](https://img.shields.io/badge/Deploy%20on-katabump-pink?style=for-the-badge&logo=katabump)](https://katabump.com/)

---

📂 Project Structure

```
ANGEL-MD/
├── lib/
├── database/
├── session/
├── media/
├── index.js
├── package.json
└── README.md
```
---
**DEPLOYMENT ON GITHUB IS AVAILABLE**
```
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
  schedule:
    - cron: '0 */6 * * *'  

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Install FFmpeg
      run: sudo apt-get install -y ffmpeg

    - name: Start application with timeout
      run: |
        timeout 21590s npm start  # Limite l'exécution à 5h 59m 50s

    - name: Save state (Optional)
      run: |
        ./save_state.sh
```
---

🧑‍💻 Developer

*DarkMods🌹*

- GitHub: [@Tyago557](https://github.com/Tyago557)

---

🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

📢 Stay Connected

Join our WhatsApp channel for updates and support:

[![Join WhatsApp Channel](https://whatsapp.com/channel/0029VamzCT5GzzKRylqvj33l

