---
title: 'Home'
date: 2025-04-30
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: 'NanoProNet: An "ImageNet" dataset for protein corona research!'
      text: 📌 2.76 M annotated nanomaterial–protein samples  📌
      primary_action:
        text: Download dataset
        url: /data/
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: /about/
      announcement:
        text: "Pre-trained foundation model for fine-tuning"
        link:
          text: "Read more"
          url: /model/
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
  - block: stats
    content:
      items:
        - statistic: "2.76M+"
          description: |
            Nanomaterial–protein  
            samples
        - statistic: "33.7k+"
          description: |
            Number of  
            unique proteins
        - statistic: "28"
          description: |
            Nanomaterial, incubation  
            & separation parameters
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    #id: data
    content:
      title: Features
      text: "AI at the forefront: empowering nanomaterial-protein interaction research 🤖"
      items:
        - name: Largest public dataset
          icon: circle-stack
          description: Over 2.76 million annotated nanomaterial–protein interaction samples and 33k unique proteins to advance research and model training.
        - name: Support generalizable predictions
          icon: bolt
          description: The use of universal text and protein language models supports generalized prediction on unseen samples and proteins.
        - name: Easy to use
          icon: sparkles
          description: Researchers with a basic machine learning background can easily follow the detailed guidelines and clear usage instructions provided.
        - name: High predictive performance
          icon: presentation-chart-bar
          description: The model is capable of accurate base predictions, handling predictions with missing feature information effectively, and generalizing reliably to unseen data.
        - name: Adaptable with fine-tuning
          icon: star
          description: Serving as a foundation model, it can be fine-tuned to specific applications, improving its ability to learn from few examples.
        - name: Active research community
          icon: rectangle-group
          description: This will drive progress in protein corona research, positioning it as a vital component in the rapidly evolving field of AI for Science.
  - block: testimonials
    content:
      title: "From the authors"
      text: "We are thankful for the support and collaboration that made this work possible."
      items:
        - name: "Hengjie Yu"
          role: "Postdoc at Westlake University"
          # Upload image to `assets/media/` and reference the filename here
          image: "hjyu.jpg"
          text: "We hope this dataset and model accelerate AI-driven protein corona research and its nanomedicine and broader applications!"
        - name: "Yaochu Jin"
          role: "Chair Professor of AI at Westlake University"
          # Upload image to `assets/media/` and reference the filename here
          image: "ycjin.jpg"
          text: "We are committed to application-driven and trustworthy AI research, exploring its broad applications in industry, science, and art."
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["1rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Deploying the foundation model or fine-tuning for specific applications
      text: As easy as 1, 2, 3!
      button:
        text: Get started
        url: https://github.com/YuHengjie/nanopronet-public
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-500"
        css_style: ""
---
