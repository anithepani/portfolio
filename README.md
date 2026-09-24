# Personal Portfolio Website

**CS344: Web Engineering &mdash; Lab 3 (Fall 2026)**

| | |
|---|---|
| **Name** | Aryan Zia |
| **Registration No.** | 505899 |
| **Section** | A (SE15A) |
| **Program** | BE Software Engineering, SEECS, NUST |

## About

A multi-page personal portfolio website built with pure **HTML5 and CSS3**.
This is the Lab 3 version, extended from Lab 2, with improvements in code
organisation based on the Lab 3 objectives:

- All styling is placed in a single **external stylesheet**.
- Project files are organised into proper folders (`css/`, `images/`).
- The navigation menu is aligned **horizontally using `float`**.
- Content and images are arranged using **`float` and `clear`**.
- The site is published live using **GitHub Pages**.

## Folder Structure

```
portfolio/
├── index.html          # Home page
├── hobbies.html        # Hobbies page
├── skills.html         # Personal skills page
├── gallery.html        # Image gallery page
├── contact.html        # Contact form page
├── css/
│   └── style.css       # Single external stylesheet for the whole site
├── images/
│   ├── profile.jpg     # Profile picture (Home page)
│   ├── photo1.jpg      # Gallery image
│   ├── photo2.jpg      # Gallery image
│   ├── photo3.jpg      # Gallery image
│   ├── photo4.jpg      # Gallery image
│   ├── photo5.jpg      # Gallery image
│   └── photo6.jpg      # Gallery image
└── README.md
```

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Introduction, about me and quick links |
| Hobbies | `hobbies.html` | Favourite hobbies |
| Personal Skills | `skills.html` | Programming, spoken and other skills |
| Image Gallery | `gallery.html` | Six images arranged with `float` |
| Contact Me | `contact.html` | Contact details and a form |

## Features

- Shared header, navigation menu and footer on every page.
- One external `css/style.css` linked by all pages (no inline/internal CSS).
- Horizontal navigation menu built with floated list items.
- Home page profile image floated left with text wrapping beside it.
- Image gallery built with floated figures and a clearfix.
- Consistent colour scheme (`#16324f` and `#2e9cca`), fonts, borders and spacing.
- No JavaScript and no CSS frameworks (as required by the lab).

## Links

- **GitHub Repository:** https://github.com/anithepani/portfolio
- **Live Site (GitHub Pages):** https://anithepani.github.io/portfolio/

## How to Run Locally

1. Download or clone the repository.
2. Open `index.html` in any modern web browser.

---

&copy; 2026 Aryan Zia &mdash; CS344 Web Engineering, Lab 3
