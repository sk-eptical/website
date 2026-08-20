---
title: ''
summary: ''
date: 2026-08-20
type: landing

sections:

  # INTRO
  - block: hero
    id: home
    content:
      title: "Hi, I'm sk."
      text: "A student, tutor and lifelong learner."
      primary_action:
        text: "Explore"
        url: "#explore"
      secondary_action:
        text: "About me"
        url: "#about"
    design:
      spacing:
        padding: ["6rem", "0", "5rem", "0"]

  # FOUR MAIN AREAS
  - block: features
    id: explore
    content:
      title: "Explore"
      items:
        - name: "Resources"
          description: "A-Level Chemistry resources, explanations and study materials."
          icon: book-open
          url: /resources/

        - name: "Tutoring"
          description: "A-Level Chemistry tutoring and teaching resources."
          icon: academic-cap
          url: /tutoring/

        - name: "Journal"
          description: "Gap year, travel, learning and whatever else I feel like documenting."
          icon: pencil
          url: /journal/

        - name: "Things"
          description: "Projects, hobbies, books, films, German, art and more."
          icon: sparkles
          url: /things/

    design:
      columns: 2
      spacing:
        padding: ["4rem", "0", "5rem", "0"]

  # SHORT ABOUT SECTION
  - block: markdown
    id: about
    content:
      title: "A little about me"
      text: |
        I'm currently taking a gap year before university.

        This site is a small corner of the internet where I keep track of
        things I'm learning, teaching, making and experiencing.

        Over time, it'll probably change quite a lot.
    design:
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  # RECENT JOURNAL POSTS
  - block: collection
    id: journal
    content:
      title: "Latest"
      subtitle: "A few recent things."
      filters:
        folders:
          - journal
      count: 3
      order: desc
    design:
      view: card
      columns: 3
      spacing:
        padding: ["4rem", "0", "5rem", "0"]

  # NOW
  - block: markdown
    id: now
    content:
      title: "Now"
      text: |
        **Currently:**

        📚 Preparing for university applications  
        🧪 Building A-Level Chemistry resources  
        👩‍🏫 Starting tutoring  
        🇩🇪 Learning German  
        🚗 Learning to drive  
        ✈️ Planning some travelling
    design:
      spacing:
        padding: ["4rem", "0", "5rem", "0"]
---
