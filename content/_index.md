---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: 讓 FitAMR 做你的跑腿小弟, 讓你專注更重要的工作
      # title: Build Your Landing Pages with Hugo Blox
      # text: 🧱 EASY. FREE (OPEN SOURCE). NO-CODE  🧱
      text: 🏎 創新. 便利. 節省時間 🏎
      # primary_action:
      #   text: Get Started
      #   url: https://hugoblox.com/templates/
      #   icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://docs.hugoblox.com
      announcement:
        text: "Announcing the release of version 1."
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
---
