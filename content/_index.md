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
  - block: features
    id: features
    content:
      title: Features
      text: FitAMR 提供多樣化的應用, 讓你的工作更輕鬆
      items:
        - name: 獨立研發
          icon: magnifying-glass
          description: 從構想出發, 歷經多次原型迭代, 整合軟硬體技術, 提供客戶最接地氣的解決方案
        - name: 自主導航
          icon: bolt
          description: 透過激光雷達、攝影機、超音波等感測器, 進行環境感知, 並透過SLAM技術, 進行地圖建立與定位
        - name: 量身訂做應用
          icon: sparkles
          description: 依據客戶需求, 提供量身訂做的應用, 貼近辦公室、工廠現場的實際需求
        - name: 創新整合
          icon: code-bracket
          description: 整合機器人、機械手臂、視覺辨識、物聯網等技術, 提供客戶最完整的解決方案
        - name: 技術導向
          icon: star
          description: ROS2、AI、機器學習、深度學習等技術, 提供客戶最前沿的技術應用
        - name: TBD
          icon: rectangle-group
          description: AAA
---
