---
title: 'Home'
date: 2025-01-27
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero-with-stats
    content:
      title: Conference on Predictive Inference in Sports
      text: "**Beyond the Stats: Unleashing Predictive Power in Sports**"
      details: "June 4 & 5, 2025"
      primary_action:
        text: Abstract Submission
        url: https://iastate.qualtrics.com/jfe/form/SV_9yss741KCFfKidE
      items:
        - name: "Speakers"
          description: "15"
        - name: "Attendees"
          description: "50+"
        - name: "Venue"
          description: "Iowa State University"
        - name: "Location"
          description: "Ames, IA"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "bg-gradient-to-r from-cardinal-100 to-gold-100"
#      background:
#        color: ""
#        image:
#          # Add your image background to `assets/media/`.
#          filename: ""
#          filters:
#            brightness: 1.0
  - block: people
    id: speakers
    content:
      title: Speakers
      text: ""
      user_groups: ['Speakers']
    design:
      show_role: true
      show_social: true
      show_interests: false
      css_class: "bg-gray-100 dark:bg-gray-900"
  # - block: markdown
  #   id: agenda
  #   content:
  #     title: Agenda
  #     text: |
  #       **DAY 1**
  #       {style="padding-top: 2rem"}
  #       {{< table path="day1-1.csv" header="true" >}}
  #       
  #       **DAY 2**
  #       {style="padding-top: 2rem"}
  # 
  #       {{< table path="day2-1.csv" header="true" >}}
  - block: countdown
    content:
      title: ""
      text: "Conference Starts:"
      # text_after: "SAVE $100"
      date: '2025-06-04 00:00:00'
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-500"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: hero-with-stats
    id: register
    content:
      title: Registration
      primary_action:
        text: Register Now
        url: https://go.iastate.edu/EX30VZ
      text: |
        {{< table path="registration.csv" header="true" >}}
  - block: cta-image-paragraph
    id: sponsors
    content:
      items:
        - title: Athlyticz
          image: log-large-athlyticz.png
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: Predictive Inference
          text: The Department of Statistics at Iowa State University will host a conference on predictive inference and its applications on June 4 & 5, 2025, in Ames, Iowa. The conference is made possible by a gift from David Harville that has established the C. R. Henderson Fund for Excellence in Predictive Inference and Its Applications.
          # Upload image to `assets/media/` and reference the filename here
          image: henderson.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
#         - title: DISCOVER
#           text: Discover the latest in AI, GenAI, application development and much more.
#           # Upload image to `assets/media/` and reference the filename here
#           image: conference-headway-F2KRf_QfCqw.jpg
#         - title: HEAR FROM LEADERS REDEFINING THE AI LANDSCAPE
#           text: Hear valuable insights from data and AI experts and business leaders, while discovering the limitless #possibilities of data, AI and application collaboration for your organization.
#           # Upload image to `assets/media/` and reference the filename here
#           image: round-table-evangeline-shaw-xRlI-L-kvrw.jpg
#           button:
#             text: Abstract Submission
#             url: 'https://iastate.qualtrics.com/jfe/form/SV_9yss741KCFfKidE'
#     design:
#       # Section background color (CSS class)
  # - block: people
  #   id: organizers
  #   content:
  #     title: Organizers
  #     text: ""
  #     user_groups: ['Organizers']
  #   design:
  #     show_role: true
  #     show_social: true
  #     show_interests: false
  
#  - block: testimonials
#    content:
#      title: ""
#      text: ""
#      items:
#        - name: "Alice Smith"
#          role: "Researcher at X"
#          # Upload image to `assets/media/` and reference the filename here
#          image: "testimonial-1.jpg"
#          text: "It has to be the most insightful conference I've ever attended!"
#    design:
#      spacing:
#        # Reduce bottom spacing so the testimonial appears vertically centered between sections
#        padding: ["6rem", 0, 0, 0]
#  - block: logos
#    content:
#      title: "Sponsors Making This Possible"
#      text: "Thanks to the following sponsors for making this incredible event possible!"
#      # Image path relative to assets/media/ folder
#      logo_folder: 'sponsors/'
#    design:
#      card:
#        # Card background color (CSS class)
#        css_class: "bg-primary-700"
#        css_style: ""
#  - block: newsletter
#    content:
#      title: "Stay up to date"
#      text: "Be the first to receive conference updates such as added speakers, deadlines, and ticket deals."
#      text_cta: "Sign up to our newsletter 🔥"
#      button:
#        text: "Subscribe"
#      convertkit:
#        form_id: ''
#        msg_subscribed: "Success! Please check your email to confirm your subscription."
#    design:
#      card:
#        # Card background color (CSS class)
#        css_class: "bg-primary-700"
#        css_style: ""
---

