---
weight: 10
date: ""
title: "Signals"
image: "camden.png"
color: "#ffffff"
type: "github"
github:
    repo: "kdevo/osprey"
    showInfo: true
terminal:
    lines:
    - type: input
      data: mkdir themes
      wait: 200
    - type: input
      data: cd themes
      wait: 200
    - type: input
      data: git clone https://github.com/kdevo/osprey-delight.git
      wait: 300
    - type: progress
      data: 100
      wait: 1000
    - data: ☕ Done! Have fun using Osprey Delight!
      wait: 900
    - type: input
      data: exit
      wait: 500
---

{github-description}
Check it out!