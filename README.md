# Profile Card & Portfolio (Activity 2)

[![Live Website](https://img.shields.io/badge/Live%20Website-Profile%20Card-2ea44f?style=for-the-badge&logo=githubpages&logoColor=white)](https://blupizarra.github.io/Profile_Card_Act2/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=font-awesome&logoColor=white)](https://fontawesome.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Academic](https://img.shields.io/badge/APC-WEBPROG%20Activity%202-B3665B?style=for-the-badge)](https://www.apc.edu.ph/)

A responsive 3-page personal portfolio website built with semantic HTML5, CSS (CSS Box Model, Flexbox layout, and custom variables), and a slate-blue color palette. Features a profile landing page, technical skills showcase (robotics, data structures, web development), and an interactive contact card.

---

## Organized Project Architecture

```text
Profile_Card_Act2/
├── index.html                   # Main landing & profile page (GitHub Pages ready)
├── skills.html                  # Technical skills showcase
├── contact.html                 # Interactive contact card
├── css/
│   └── styles.css               # Consolidated global stylesheet (Flexbox, Box Model, Variables)
├── assets/
│   └── images/
│       ├── profile.jpg          # Profile photo
│       ├── robotics.jpg         # Robotics project showcase
│       └── certificates.jpg     # Certifications & Data Structures media
├── [WEBPROG] PIZARRA_index.html # Academic submission alias
├── [WEBPROG] PIZARRA_skills.html
├── [WEBPROG] PIZARRA_contact.html
├── [WEBPROG] PIZARRA_styles.css
├── .gitignore
└── README.md
```

### Key Organizational Improvements
- **Decoupled Images**: Extracted large embedded base64 strings into dedicated files under `assets/images/`, reducing repository HTML file bloat by over **90%** (~400KB down to ~2KB each).
- **Separation of Concerns**: Extracted inlined `<style>` tags into a unified, responsive stylesheet at `css/styles.css`.
- **Standard Web Routing**: Added clean standard filenames (`index.html`, `skills.html`, `contact.html`) enabling out-of-the-box hosting on GitHub Pages and static web servers.
- **Academic Compatibility**: Retained clean aliases for `[WEBPROG] PIZARRA_*` files ensuring full compatibility with institutional grading criteria.

---

## Color Palette

| Color Name | Hex Code | Swatch |
| :--- | :--- | :--- |
| **Dark Navy** | `#27374D` | ![#27374D](https://placehold.co/15x15/27374D/27374D.png) |
| **Slate Blue** | `#526D82` | ![#526D82](https://placehold.co/15x15/526D82/526D82.png) |
| **Light Blue** | `#9DB2BF` | ![#9DB2BF](https://placehold.co/15x15/9DB2BF/9DB2BF.png) |
| **Soft Ice** | `#DDE6ED` | ![#DDE6ED](https://placehold.co/15x15/DDE6ED/DDE6ED.png) |
| **White** | `#FFFFFF` | ![#FFFFFF](https://placehold.co/15x15/FFFFFF/FFFFFF.png) |

---

## How to View Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/BluPizarra/Profile_Card_Act2.git
   cd Profile_Card_Act2
   ```
2. **Open in Browser:**
   - Double-click **`index.html`** to launch in any modern browser.
   - Or open the project folder in **Visual Studio Code** and start with the **Live Server** extension.

---

## Author

- **Bludylan Cyrus Pizarra** ([@BluPizarra](https://github.com/BluPizarra))
- **Program**: BSIT, Asia Pacific College
- **LinkedIn**: [Bludylan Cyrus Pizarra](https://www.linkedin.com/in/bludylan-cyrus-pizarra-a48434378/)
