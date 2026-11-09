---
layout: home
nav_title: Home

# The big title across the top of the home page
banner_title: Lanka Software Foundation

# The full-width "bars" on the home page, in order from top to bottom.
# Each bar can have: eyebrow (small text above the heading), heading, text, and links (buttons).
bars:
  - id: mission
    eyebrow: Open Source for Public Good
    heading: Building Digital Public Infrastructure for the World
    text: |
      In today's complex state of geopolitics marked by de-globalization and weaponized economics, software security is a key aspect of national security and national independence, especially in the digital public infrastructure that powers nations. Free and open source software that can be freely developed, deployed and used without restrictions from world powers is the path to software freedom.
    links:
      - label: What are Digital Public Infrastructure (DPI)
        url: /digital-public-infrastructure/
      - label: Our beliefs on how DPI should be built
        url: /our-beliefs-on-dpi/

  - id: who-we-are
    heading: Who we are
    text: |
      The Lanka Software Foundation (LSF) was founded in 2003 on a simple belief: that Sri Lanka should be known not as a low-cost place to outsource software, but as a place where talented engineers create the software the world runs on.

      Over two decades, LSF's work has led to widely used open source software and companies, including:

      - **Apache Axis2:** the engine behind a generation of web services. A ground-up redesign of the widely used Apache Axis, it powers how enterprise and government systems exchange data over the web.
      - **WSO2:** founded in 2005 and built on the Axis2 work by the LSF team, WSO2 grew into a global open source company whose API management, integration and identity software is used by enterprises and governments worldwide.
      - **Sahana:** a free and open source disaster management system, first developed in the wake of the 2004 Indian Ocean tsunami, and later deployed in the 2005 Pakistan earthquakes, 2010 Haiti earthquake and 2012 Hurricane Sandy.

      Today, we build open source Digital Public Infrastructure, that any country is free to use, adapt and make its own, so that every nation, whatever its size, can build the digital foundations its people deserve.
    links:
      - label: Read our full story
        url: /about/
      - label: Meet our team
        url: /team/

  - id: products
    heading: Our Products
    type: products
    # Product names, in the order to show them (must match the titles of the pages in _projects/)
    products: [OpenNSW, OpenNDX, OpenGovMail, OpenSuperApp]

  - id: news
    heading: News
    type: news
    # How many of the latest news items (from _posts/) to show
    count: 3
    links:
      - label: See all news
        url: /news/
---
