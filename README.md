<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=150&section=header&text=jeremy@mauretz&fontSize=40&fontColor=00FF41&animation=fadeIn&fontAlignY=35" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00FF41&center=true&vCenter=true&width=500&lines=Hi%2C+I'm+Jeremy+Mauretz;IT+Student+%40+Metland+School;Web+Dev+%7C+Networking+%7C+Hardware" alt="Typing SVG" />
</p>

```
                   -`                    jeremy@mauretz
                  .o+`                   --------------
                 `ooo/                   OS: Arch Linux x86_64
                `+oooo:                  Identity: Jeremy Mauretz
               `+oooooo:                 Role: IT Student @ Metland School
               -+oooooo+:                Focus: Web Dev | Networking | Hardware Assembly
             `/:-:++oooo+:               Skills: HTML/CSS/JS, Python, MikroTik, LAN Setup
            `/++++/+++++++:              Design: Figma, UI/UX Prototyping, Multimedia
           `/++++++++++++++:             Projects: Dino Wallet (UI/UX & DB), TrackinID (IoT/GPS)
          `/+++ooooooooooooo/`           Org: ITEC Equipment Manager & Media
         ./ooosssso++osssssso+`          Certs: STADA Citra Orientation 2024
        .oossssso-````/ossssss+`         Languages: English (B1), Indonesian
       -osssssso.      :ssssssso.        Location: Bogor Regency, Indonesia
      :osssssss/        osssso+++.       Portfolio: portofolioversion2.vercel.app
     /ossssssss/        +ssssooo/-       Contacts: jeremymauretz64@gmail.com
   `/ossssso+/:-        -:/+osssso+-
  `+sso+:-`                 `.-/+oso:
 `++:.                           `-/+/
 .`                                 `/
```

<br>

## 🚀 Pinned Projects

<p align="center">
  <a href="https://github.com/richiedavie/portofolio"><img height="150em" src="https://github-readme-stats.vercel.app/api/pin/?username=richiedavie&repo=portofolio&theme=dark" /></a>
  <a href="https://github.com/richiedavie/trackinID"><img height="150em" src="https://github-readme-stats.vercel.app/api/pin/?username=richiedavie&repo=trackinID&theme=dark" /></a>
</p>

<br>

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/richiedavie/richiedavie/output/github-contribution-grid-snake-dark.svg" alt="snake animation" />
</p>

<sub>To enable the snake animation above, add the workflow file below at `.github/workflows/snake.yml` in this repo:</sub>

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: richiedavie
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

<br>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=richiedavie&color=00FF41&style=flat-square" alt="profile views" />
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:1a1a2e&height=100&section=footer" />
