# HusterCourses
This web site documents and archives the courses I have taught for 
Duquesne university from 2015 to the present.

I hope this helps.

project:
  type: website

website:
  title: "HusterCourses"
  sidebar:
    style: docked
    search: true
    collapse-level: 1
    contents:
      - href: index.qmd
        text: Home
      - section: "Courses"
        contents:
          - href: GAP1/gap1.qmd
            text: GAP 1
          - href: GAP1Vernier/GAP1Vernier.qmd
            text: GAP1 Pre 2020
      - section: "About ProfHuster"
        contents:
          - href: About/about.qmd
            text: Education and Experience
          - href: About/interests.qmd
            text: Interests

format:
  html:
    theme: cosmo
    css: styles.css
    toc: true



