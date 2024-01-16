# This is Search Engine Optimization. It'll help your website look better on search.
seo:
  title:       "Ann Arbor | 16-18 February 2023"
  description: "This is a sample hackathon website that you can use by following instructions on GitHub."
  image:       "https://prime.mlh.io/img/logos/mlh-prime-color.svg"

# Event information.
event:
  name:        "Example Hacks"
  description: "This is a sample hackathon website that you can use by following instructions on GitHub."
  date:        "5 - 6 August 2022"
  location:    "Holmdel, NJ, United States"

  trust_badge:
    year:   "2024"  # season year
    region: "na"    # "na" or "eu"
    color:  "white" # "white", "black", "gray", "red", "blue" or "yellow"

  hero:
    links:
      - text: "Apply"    
          redirect_uri: 
      - text: "Sponsor"
        href: 

  about:
    description: >
      Example Hacks is a hackathon hosted at The University of Example.
      This is your opportunity to describe your event, what to expect, where it is & anything unique to your event.
      Keep it straightforward, don't make it too long.

  # Info Sections
  info:
    sections:
      - image: "images/image1.png"
        title: "LEARN."
        description: >
          We can write something nice with a graphic (as above) to make the event more appealing.
      - image: "images/image2.png"
        title: "BUILD."
        description: >
          We can write something nice with a graphic (as above) to make the event more appealing.
      - image: "images/image3.png"
        title: "SHARE."
        description: >
          We can write something nice with a graphic (as above) to make the event more appealing.

  # Frequently asked questions.
  faq:
    - question: "What is a hackathon?"
      answer: >
        A hackathon is an invention marathon. Students come together to build cool
        software & hardware hacks over 24-48 hours. It's [very beginner friendly](https://medium.com/@tfogo/hackathons-are-for-beginners-77a9c9c0e000#.cj21niskl).
    - question: "How much does it cost?"
      answer: >
        Nothing. Attending a hackathon is free.
    - question: "Do I need to be a student to attend?"
      answer: >
        Yes. Only students who are currently enrolled at a college/university or
        have graduated within the past 12 months are eligible to attend.
    - question: "Where is the event?"
      answer: >
        The event is being hosted at [insert venue location here].
    - question: "What is Major League Hacking?"
      answer: >
        Major League Hacking is [the official student hackathon league](https://mlh.io) in North America & Europe.
        We work with over 200 Member Events and empower over 70,000 students every year.
    - question: "Is there a code of conduct?"
      answer: >
        Yes there is. We enforce it very strongly. You can [find it here](https://static.mlh.io/docs/mlh-code-of-conduct.pdf).

  # This is the message you'll receive once you've registered.
  register:
    message: >
      You'll receive more information closer to the hackathon.

# ----------------------------------------------------
# -- Ignore this unless you know what you're doing. --
# ----------------------------------------------------

markdown: kramdown
exclude:
 - node_modules
 - gulpfile.js
 - Gemfile
 - Gemfile.lock
 - package.json
 - README.md
 - CNAME
