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
      title: 自学英语者之日志
      text: LukeLingo.com, 旨在记录本人自学英语过程之大小事
      primary_action:
        text: Get Started
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: https://docs.hugoblox.com
      announcement:
        text: 'Announcing the release of version 1.'
        link:
          text: Read more
          url: /blog/
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: cool-background.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "4A+"
          description: |
            听、说、读、写全覆盖
        - statistic: "100%"
          description: |
            源自英语母语者素材
        - statistic: "1M+"
          description: |
            每月更新博客内容
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: 为什么创立此网站？
      text: ''
      items:
        - name: 自我记录
          icon: magnifying-glass
          description:  将学习过程记录在网站上，形成一个持久的学习档案，帮助自己回顾学习历程，感受成长的脚步。
        - name: 打破学习孤岛
          icon: bolt
          description: 网站是一个与其他学习者建立联系的平台，打破学习孤岛，共同攀登语言学习的高峰。
        - name: 知识分享
          icon: sparkles
          description:  将积累的知识与其他学习者分享，为整个学习社群贡献有价值的信息。
        # - name: No-Code
        #   icon: code-bracket
        #   description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        # - name: Highly Rated
        #   icon: star
        #   description: Rated 5-stars by the community.
        # - name: Swappable Blocks
        #   icon: rectangle-group
        #   description: Build your pages with blocks - no coding required!
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: 影子跟读
          text: 博主正在实践的英语学习方法之一，据说能同时提升听、说、读三方面能力
          feature_icon: check
          features:
            - "Step. 1 选择跟读素材"
            - "Step. 2 学习素材脚本"
            - "Step. 3 逐句影子跟读"
            - "Step. 4 全文影子跟读"
          # Upload image to `assets/media/` and reference the filename here
          image: shadow.png
          button:
            text: Get Started
            url: https://hugoblox.com/templates/
        - title: 地道资源
          text: 基于博主兴趣所搜集的高质量信息源，以海外站点为主，皆需使用魔法访问
          feature_icon: bolt
          features:
            - "高质量 Youtube 频道推荐"
            - "高质量 Podcast 频道推荐"
            - "高质量文章和博客推荐"
          # Upload image to `assets/media/` and reference the filename here
          image: London.png
          button:
            text: Join Discord
            url: https://discord.gg/z8wNYzb
        - title: 实用工具
          text: 欲先善其事，必先利其器
          feature_icon: bolt
          features:
            - "英语权威词典"
            - "英语兴趣网站"
            - "AI 工具助力学习"
          # Upload image to `assets/media/` and reference the filename here
          image: tools.png
          button:
            text: Join Discord
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "路德维希·维特根斯坦"
          role: "奥地利哲学家"
          # Upload image to `assets/media/` and reference the filename here
          image: "Ludwig-Wittgenstein.jpg"
          text: 我的语言之局限，即我的世界之局限。
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      # title: ''
      text: 如果您有任何意见或建议，欢迎与我邮电沟通！
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: "font-size: 15px; width: 800px; height: 250px; display: flex; flex-direction: column; justify-content: center; align-items: center;"  # 调整字体大小和最大宽度，使文字居中
      background:
        # Choose a color such as from https://html-color-codes.info
        # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true
---
