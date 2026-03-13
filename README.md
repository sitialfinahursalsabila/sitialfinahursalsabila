# Hi, I'm Siti Alfinahur Salsabila 👋

<img width="100%" alt="my header" src="https://github.com/user-attachments/assets/0d47b1e0-f1f4-42bc-94ae-ecabb132cf2a" />

### 🎓 Profile
I am a **4th-semester Informatics Engineering student at UIN Malang**. I focus on modern web development, creating scalable applications with **Laravel** and **Next.js**, and exploring data-driven solutions.

* 🚀 **Currently Building:** [ZIANA-CBT-System](https://github.com/sitialfinahursalsabila) - An interactive learning platform.
* 🛠️ **Technical Interests:** Full-stack Web Development, Database Management, and UI/UX Design.
* 📚 **Education:** Informatics Engineering, Maulana Malik Ibrahim State Islamic University Malang.

---

### 🛠️ Tech Stack

| Category | Tools & Technologies |
| :--- | :--- |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-black?style=flat-square&logo=next.js&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-%2338B2AC.svg?style=flat-square&logo=tailwind-css&logoColor=white) ![Flowbite](https://img.shields.io/badge/Flowbite-black?style=flat-square&logo=flowbite&logoColor=blue) |
| **Backend** | ![Laravel](https://img.shields.io/badge/Laravel-%23FF2D20.svg?style=flat-square&logo=laravel&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-%23777BB4.svg?style=flat-square&logo=php&logoColor=white) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-%2300f.svg?style=flat-square&logo=mysql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) |

---

### 🐍 Contribution Graph
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sitialfinahursalsabila/sitialfinahursalsabila/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sitialfinahursalsabila/sitialfinahursalsabila/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/sitialfinahursalsabila/sitialfinahursalsabila/output/github-contribution-grid-snake.svg">
</picture>

---

### 📊 GitHub Analytics
<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=sitialfinahursalsabila&show_icons=true&theme=nord" alt="stats" height="150" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sitialfinahursalsabila&layout=compact&theme=nord" alt="top langs" height="150" />
</p>

---

### 📫 Connect with Me
<p align="left">
<a href="https://linkedin.com/in/sitialfinahursalsabila" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="sitialfinahursalsabila" height="30" width="40" /></a>
<a href="mailto:emailanda@gmail.com" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/gmail.svg" alt="email" height="30" width="40" /></a>
</p>


name: generate animation

on:
  # dijalankan otomatis setiap 24 jam
  schedule:
    - cron: "0 */24 * * *" 
  
  # mengizinkan menjalankan manual kapan saja
  workflow_dispatch:
  
  # dijalankan setiap ada push ke branch main
  push:
    branches:
    - main

jobs:
  generate:
    permissions: 
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5
    
