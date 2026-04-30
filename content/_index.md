---
title: 'Home'
date: 2023-10-24
type: landing

sections:
  - block: hero
    content:
      title: Build Your Landing Pages with Hugo Blox
      text: 🧱 EASY. FREE (OPEN SOURCE). NO-CODE  🧱
      primary_action:
        text: Get Started
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: https://docs.hugoblox.com
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
          size: cover
          position: center
          parallax: false
  - block: logos
    content:
      title: Trusted by teams at
      items:
        - icon: brands/github
          name: GitHub
        - icon: brands/google
          name: Google
        - icon: brands/microsoft
          name: Microsoft
        - icon: brands/nvidia
          name: NVIDIA
        - icon: brands/openai
          name: OpenAI
        - icon: brands/anthropic
          name: Anthropic
        - icon: brands/stripe
          name: Stripe
        - icon: brands/vercel
          name: Vercel
    design:
      layout: marquee
      logo_style: grayscale
      logo_size: md
      marquee_speed: 35
      css_class: "bg-gray-50 dark:bg-gray-900"
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  - block: stats
    content:
      items:
        - statistic: "1M+"
          description: |
            Websites built  
            with Hugo Blox
        - statistic: "10k+"
          description: |
            GitHub stars  
            since 2016
        - statistic: "3k+"
          description: |
            Discord community  
            for support
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Features
      text: Build your site with blocks 🧱
      items:
        - name: Optimized SEO
          icon: magnifying-glass
          description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
        - name: Fast
          icon: bolt
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Easy
          icon: sparkles
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
        - name: No-Code
          icon: code-bracket
          description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        - name: Highly Rated
          icon: star
          description: Rated 5-stars by the community.
        - name: Swappable Blocks
          icon: rectangle-group
          description: Build your pages with blocks - no coding required!
  - block: pricing
    id: pricing
    content:
      title: "Simple, transparent pricing"
      subtitle: "Start for free. Upgrade when you're ready. No credit card required."
      billing_toggle:
        enabled: true
        monthly_label: Monthly
        yearly_label: Yearly
        yearly_discount: "Save 20%"
      tiers:
        - name: Starter
          description: "Perfect for personal projects and portfolios."
          price:
            monthly: "0"
            yearly: "0"
            currency: "$"
          price_note: "Free forever"
          highlight: false
          cta:
            text: Get started free
            url: https://hugoblox.com/templates/
            icon: hero/arrow-right
            style: outline
          features:
            - text: "5 pages"
              included: true
            - text: "1 GB storage"
              included: true
            - text: "Custom domain"
              included: false
            - text: Analytics dashboard
              included: false
            - text: Priority support
              included: false
        - name: Pro
          badge: Most popular
          description: "For freelancers and teams building seriously."
          price:
            monthly: "19"
            yearly: "15"
            currency: "$"
          price_suffix: /month
          price_note_monthly: "Billed monthly"
          price_note_yearly: "Billed annually"
          highlight: true
          cta:
            text: Start free trial
            url: https://hugoblox.com/templates/
            icon: hero/arrow-right
            style: primary
          features:
            - text: Unlimited pages
              included: true
            - text: "10 GB storage"
              included: true
            - text: Custom domain
              included: true
            - text: Analytics dashboard
              included: true
            - text: Priority support
              included: false
        - name: Business
          description: "Scale with confidence and dedicated support."
          price:
            monthly: "49"
            yearly: "39"
            currency: "$"
          price_suffix: /month
          price_note_monthly: "Billed monthly"
          price_note_yearly: "Billed annually"
          highlight: false
          cta:
            text: Start free trial
            url: https://hugoblox.com/templates/
            icon: hero/arrow-right
            style: outline
          features:
            - text: Unlimited pages
              included: true
            - text: "100 GB storage"
              included: true
            - text: Custom domain
              included: true
            - text: Analytics dashboard
              included: true
            - text: Priority support
              included: true

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Build your future-proof website
          text: As easy as 1, 2, 3!
          feature_icon: check
          features:
            - "Future-proof - edit your content in text files"
            - "Website is generated by a single app, Hugo"
            - "No JavaScript knowledge required"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Get Started
            url: https://hugoblox.com/templates/
        - title: Large Community
          text: Join our large community on Discord - ask questions and get live responses
          feature_icon: bolt
          features:
            - "Dedicated support channel"
            - "3,000+ users on Discord"
            - "Share your site and get feedback"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
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
        - name: "Hugo Smith"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Build your future-proof website
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-300"
        css_style: ""
---
