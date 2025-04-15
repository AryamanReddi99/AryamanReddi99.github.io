---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: true
  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      date_format: 'January 2006'
      is_education_first: true
      # css_class: dark
      # background:
      #   color: black
      #   image:
      #     # Add your image background to `assets/media/`.
      #     filename: bg.svg
      #     filters:
      #       brightness: 0.5
      #     size: cover
      #     position: center
      #     parallax: true
  - block: collection
    id: papers
    content:
      title: Papers
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: article-grid
      columns: 3
      
      
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      view: compact
      columns: 3
      # spacing:
      #   padding: [0, 0, 0, 0]
  - block: collection
    id: blog
    content:
      title: Blog
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: article-grid
      # Reduce spacing
      columns: 2
      
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 2
  - block: markdown
    id: more
    content:
      title: More
      subtitle:
      text: |-
        Communities
          - I am a teaching assistant for the [Reinforcement Learning course at TU Darmstadt](https://www.tucan.tu-darmstadt.de/scripts/mgrqispi.dll?APPNAME=CampusNet&PRGNAME=COURSEDETAILS&ARGUMENTS=-N000000000000002,-N000036,-N0,-N383933943100166,-N383933943101167,-N0,-N0,-N0) 🤖
          - Former Secretary of the [Cambridge University Libertas Society](https://www.facebook.com/CambridgeLibertas), Cambridge's first free speech society ✒️
        
        Interesting links
        - [Don’t ask to ask, just ask](https://dontasktoask.com/)
        - [The XY Problem](https://xyproblem.info/)
        - [The Life of Jos Claerbout](http://sepwww.stanford.edu/sep/jon/family/jos/index.html)
        - [The Worst Rob Liefeld Drawings](https://www.progressiveboink.com/2012/4/21/2960508/worst-rob-liefeld-drawings) (the funniest article ever written)
    
  - block: cta-card
    id: contact
    content:
      title: Contact
      text: |-
        ✉️ aryaman{}reddi{}tu-darmstadt.de
        
        📍 E327, S2|02 Robert-Piloty-Gebäude, Technical University of Darmstadt, Darmstadt 64289
      button:
        text: LinkedIn
        url: https://www.linkedin.com/in/aryamanreddi/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-900"
        css_style: ""
---
