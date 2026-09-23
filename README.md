<div align="center">

  <!-- Banner (Aesthetic/Anime dark banner) -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=220&section=header&text=Hi,%20I'm%20Yusuf!&fontSize=42&fontColor=58a6ff&animation=twinkle" width="100%" />

  <br />

  <!-- Ijtimoiy tarmoq va aloqa tugmalari -->
  <p align="center">
    <a href="https://t.me/telegram_username"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" /></a>
    <a href="mailto:emailingiz@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  </p>

  <!-- Profil ko'rishlar soni -->
  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=58a6ff&style=flat-square&label=Profile+Views" />
  </p>

</div>

---

### 💻 Men haqimda (About Me)

- 🇺🇿 Joylashuv: **Jizzax, O'zbekiston**
- 🚀 Soha: **Frontend Developer** (React, Javascript)
- 🎓 Maqsad: **Full Stack Developer** darajasiga etishish
- ⚡ Qiziqishlar: Veb-dasturlash, zamonaviy texnologiyalar va anime/kodlash

---

### 🛠️ Texnologiyalar (Languages & Tools)

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js,sass,git,react&theme=dark" />
  </a>
</p>

---

### 📊 GitHub Statistikam (Stats)

<div align="center">

  <!-- Umumiy statistikalar -->
  name: Generate Snake Animation

on:
  schedule:
    # Har 24 soatda avtomatik yangilanadi
    - cron: "0 0 * * *" 
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

</div>

<br />

<div align="center">

  <!-- Faollik kunlari (Streak Stats) -->
  
</div>

---




---

<p align="center">
  <i>⚡ Dasturlash va izlanishda davom etamiz!</i>
</p>
