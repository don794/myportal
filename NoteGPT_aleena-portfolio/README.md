# Aleena Bilal — Portfolio & Assignment Portal

A six-page, production-ready static website built with **HTML5 + internal CSS only**
(no external stylesheet, no JavaScript).

## File structure

| File | Purpose |
|------|---------|
| `index.html` | Portal entry / welcome page |
| `register.html` | Account creation form |
| `login.html` | Login form |
| `dashboard.html` | GPA result table |
| `about.html` | Personal introduction |
| `contact.html` | Contact details + resume download |

```
aleena-portfolio/
├── index.html
├── register.html
├── login.html
├── dashboard.html
├── about.html
├── contact.html
├── README.md
└── assets/
    ├── profile-circle.png              (circular avatar - header, about, dashboard)
    ├── profile-square.jpg              (square photo - hero / banner)
    ├── project-assignment-portal.png   (project screenshot)
    ├── project-gpa-table.png           (project screenshot)
    └── Aleena-Bilal-Resume.pdf         (downloadable CV)
```

## Theme

* Background: black → cherry-red linear gradient (identical on all six pages)
* Accent colour: `#d2042d` (cherry red) and `#ff3355` (highlight)
* Font: Montserrat (system fallback stack included)
* Cherry-red glow on hover for buttons, links, cards, table rows and chips
* Responsive: single-column below 980 px, compact navigation below 700 px

## Editing notes

1. **Fonts** — each page holds one `<link>` to Google Fonts for Montserrat.
   Delete it for a 100 % offline copy; the internal stack falls back to system sans-serif.
2. **Fiverr / GitHub** — in `contact.html` (and the footers) replace
   `https://www.fiverr.com/` and `https://github.com/` with the real profile URLs.
3. **GPA table** — every marks / percentage / GPA cell already carries
   `data-field` and `data-subject` attributes, so a small JavaScript module can later
   make the table editable and recalculate the CGPA live.
4. **Forms** — front-end only. Point each `<form action="...">` at a back-end
   endpoint to make them functional.

## Copyright

© 2026 All rights reserved to Aleena Bilal.
