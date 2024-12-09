---
# Display name
title: Rohit Jena

# Name pronunciation (optional)
name_pronunciation: 

# Full name (for SEO)
first_name: Rohit
last_name: Jena

user_groups:
    - Researchers

# Status emoji
status:
  icon: '🚀'

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: PhD Student

username: rohitjena

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: PICSL
    url: https://picsl.upenn.edu
  - name: GRASP lab
    url: https://www.grasp.upenn.edu/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:firstinitial lastname (at nospam) seas .upenn (dot) edu'
    label: E-mail Me
  - icon: brands/x
    url: https://twitter.com/rohitrango
  # - icon: brands/instagram
  #   url: https://www.instagram.com/
  - icon: brands/github
    url: https://github.com/rohitrango
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/rohitrango
  - icon: academicons/google-scholar
    url: https://scholar.google.com/citations?user=kZQQFE4AAAAJ&hl=en
  - icon: academicons/orcid
    url: https://orcid.org/0000-0002-8707-383X

interests:
  - Deep Learning
  - Image Registration
  - Computer Vision

education:

  - area: PhD Artificial Intelligence
    institution: University of Pennsylvania
    date_start: 2021-05-20
    date_end: 2027-05-15
    summary: |
      Towards feature-aware deformable registration and unbiased evaluation.
    # button:
    #   text: 'Webpage'
    #   url: 'https://jenaroh.it'

  - area: Masters in Robotics
    institution: Carnegie Mellon University
    date_start: 2019-08-20
    date_end: 2021-05-15
    summary: |
      GPA: 4.13/4.0

      Masters Thesis: "Learning Mental Models of Experts in a Simulated Search and Rescue Scenario"
    button:
      text: Thesis PDF
      url: https://www.ri.cmu.edu/app/uploads/2021/08/cmu_msr_thesis.pdf
      
  - area: BTech in Computer Science and Engineering
    institution: Indian Institute of Technology, Bombay
    date_start: 2015-07-20
    date_end: 2019-05-15
    summary: |
      GPA: 9.56/10.0
      
      Courses included:
      - Machine Learning
      - Data Structures and Algorithms
      - Computer Vision
      - Operating Systems
      - Computer Networks

      Undergraduate Thesis: "Perfect Sampling and Uncertainty Estimation in Deep Networks"
      
work:
  - position: Deep Learning Research Intern
    company_name: NVIDIA
    company_url: ''
    company_logo: ''
    date_start: 2024-05-20
    date_end: '2024-09-06'
    summary: |2-
      Alignment for text-to-image diffusion models
      
  - position: Applied Scientist Intern
    company_name: Amazon Lab 126
    company_url: ''
    company_logo: ''
    date_start: 2022-05-20
    date_end: 2022-08-20
    summary: |
      Mesh-NeRF/3DGS hybrid models for human avatar recovery

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Python
        description: ''
        percent: 80
        icon: code-bracket
      - name: Data Science
        description: ''
        percent: 100
        icon: chart-bar
      - name: SQL
        description: ''
        percent: 40
        icon: circle-stack
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Hiking
        description: ''
        percent: 60
        icon: person-simple-walk
      - name: Cats
        description: ''
        percent: 100
        icon: cat
      - name: Photography
        description: ''
        percent: 80
        icon: camera

languages:
  - name: English
    percent: 100
  - name: Hindi
    percent: 90
  - name: Odia
    percent: 90

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:

  - title: Neural Networks and Deep Learning
    url: https://www.coursera.org/learn/neural-networks-deep-learning
    date: '2023-11-25'
    awarder: Coursera
    icon: coursera
    summary: |
      I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.

  - title: Blockchain Fundamentals
    url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    date: '2023-07-01'
    awarder: edX
    icon: edx
    summary: |
      Learned:
      - Synthesize your own blockchain solutions
      - Gain an in-depth understanding of the specific mechanics of Bitcoin
      - Understand Bitcoin’s real-life applications and learn how to attack and destroy Bitcoin, Ethereum, smart contracts and Dapps, and alternatives to Bitcoin’s Proof-of-Work consensus algorithm

  - title: 'Object-Oriented Programming in R'
    url: https://www.datacamp.com/courses/object-oriented-programming-with-s3-and-r6-in-r
    certificate_url: https://www.datacamp.com
    date: '2023-01-21'
    awarder: datacamp
    icon: datacamp
    summary: |
      Object-oriented programming (OOP) lets you specify relationships between functions and the objects that they can act on, helping you manage complexity in your code. This is an intermediate level course, providing an introduction to OOP, using the S3 and R6 systems. S3 is a great day-to-day R programming tool that simplifies some of the functions that you write. R6 is especially useful for industry-specific analyses, working with web APIs, and building GUIs.

type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      title: "Welcome"
      username: rohitjena
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/rohit-resume.pdf
    design:
      css_class: dark
      background:
        color: system
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1
          size: cover
          position: center
          parallax: true
  
  ## whatever else you want to add
  # - block: markdown
  #   content:
  #     title: More about me 👀
  #     text: |-
  #       lorem ipsum dolor sit amet consectetur adipiscing elit sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident sunt in culpa qui officia deserunt mollit anim id est laborum.

  ## If you want to show off your skills
  # - block: resume-experience
  #   content:
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     title: "Welcome"
  #     username: rohitjena

  ## If you want to show awards
  # - block: resume-awards
  #   content:
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     title: "Awards"
  #     username: rohitjena

---

<!-- This text will go on top of the file, checkout the reference image -->

I’m a Ph.D. student in CIS at University of Pennsylvania advised by [Prof. James C. Gee](/member/jimgee) and [Prof. Pratik Chaudhari](https://pratikac.github.io/).

I’m working on image registration, segmentation, and computer vision problems in general.

I completed my Masters in Robotics at The Robotics Institute, Carnegie Mellon University where I was advised by [Prof. Katia Sycara](http://www.cs.cmu.edu/~sycara/). I also worked with [Prof. Kayhan Batmanghelich](https://www.batman-lab.com/) on segmentation of vascular structures in medical images.

I completed my bachelors in Computer Science and Engineering from Indian Institute of Technology, Bombay in 2019. My undergraduate thesis is based on Perfect Sampling and Uncertainty Estimation in Deep Networks where I was advised by [Prof. Suyash P. Awate](https://www.cse.iitb.ac.in/~suyash/).

In my free time, I like to hike 🥾, play drums 🥁 and learn stenography 🎹. 

Check out my publications on my [Google Scholar](https://scholar.google.com/citations?user=kZQQFE4AAAAJ&hl=en) page.