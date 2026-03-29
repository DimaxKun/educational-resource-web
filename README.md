# UC Resources Hub

A central academic resource hub for the **University of the Cordilleras** (UC), designed to help students and faculty easily discover and access educational materials, journals, libraries, and college-specific resources.

## Overview

UC Resources Hub is a responsive, single-page web application that aggregates academic resources across UC's colleges and departments. It features a clean, branded interface with smooth animations and direct links to the university's library databases and open educational resources.

## Features

- Hero section with a call-to-action linking to resource categories
- Featured resources section highlighting Libraries, Free Online Resources, and Open Educational Resources
- College-specific categories: Accountancy, Arts & Sciences, Teacher Education, Nursing, Information Technology, and Engineering
- Sample learning resources including journals and open-access databases
- About section with UC's mission statement and a contact form
- Fully responsive layout using Bootstrap 5

## Tech Stack

- HTML5
- CSS3 (custom animations, responsive design)
- Bootstrap 5.3.8
- Google Fonts (Fjalla One)

## Project Structure

```
├── index.html          # Main application page
├── index.css           # Custom styles and animations
├── appBuilding2.json   # App configuration (hosted URL)
└── images/
    ├── uc_logo_green_ext_h150.png
    ├── uc-web-bg.jpg
    ├── ali-icon.png
    └── image-1.png ... image-6.png  # College category images
```

## Getting Started

No build tools required. Just open `index.html` in a browser or serve it with any static file server.

```bash
# Using Python
python -m http.server 8080

# Using Node.js (npx)
npx serve .
```

Then visit `http://localhost:8080`.

## Sections

| Section | Description |
|---|---|
| Home | Hero banner with intro text and CTA |
| Featured Resources | Quick links to UC library portals |
| Categories | Per-college resource and course links |
| Sample Resources | Curated journals and open-access databases |
| About | Mission statement and contact form |

## Credits

Developed by Mohammad Ali Dimacaling  
© 2026 All rights reserved.

University of the Cordilleras — Baguio City, Philippines  
[uc-bcf.edu.ph](https://www.uc-bcf.edu.ph)
