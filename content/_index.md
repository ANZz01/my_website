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
      username: admin  # references content/authors/admin/_index.md
      text: ""         # keep empty or add a short tagline here
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: "📄 Download"
      text: |
        <a class="btn btn-primary" href="/my_website/uploads/Ng_Kwunfung_Resume.pdf" target="_blank">Download My CV</a>
---
