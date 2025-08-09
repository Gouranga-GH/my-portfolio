
# Gouranga Jha — Portfolio (HTML/CSS/JS)

Static personal portfolio showcasing projects, skills, and contact information. Built with semantic HTML, modern CSS, and a light layer of JavaScript for animations and interactivity. No build step required.

## Live Demo
- GitHub Pages: https://gouranga-gh.github.io/my-portfolio/

## Features
- Animated hero with particle effect, typewriter title, and CTA buttons
- Smooth scrolling, sticky navbar with scroll styling, scroll progress bar
- AOS-powered section animations and subtle card hover effects
- Responsive project and skill cards (Bootstrap grid)
- Loading screen and scroll-to-top floating action button

## Tech Stack
- HTML5 with inline CSS
- Bootstrap 4.5.2 (CSS/JS)
- jQuery 3.5.1 (slim) and Popper.js
- Google Fonts: Poppins
- Font Awesome 6.0.0 (icons)
- AOS 2.3.1 (Animate On Scroll)
- Vanilla JavaScript (no frameworks)

CDNs are loaded directly in `index.html`.

## Project Structure
```
my-portfolio/
  index.html                # Single-page site (sections: Home, About, Projects, Skills, Contact)
  icons/                    # Social icons used in Contact section
  images/
    about/                  # About section image(s)
    bg_imgs/                # Background images (hero/contact overlays)
    projects/               # Thumbnails for project cards
    skills/                 # Thumbnails for skills cards
  README.md                 # This file
```

## Run Locally
No build tools needed.

Option A: Double-click `index.html` to open in your browser.


```

## Customize Content
- About: Update text and image at `images/about/1.jpg` in the `#about` section of `index.html`.
- Projects: Each project card lives in the `#projects` section. Duplicate a card block and update the image, title, description, and link. Thumbnails are under `images/projects/`.
- Skills: Cards live in the `#skills` section. Update titles, descriptions, and images under `images/skills/`.
- Contact: Update email/phone and social links in the `#contact` section. Social icons are in `icons/`.

Minimal project card template:
```html
<div class="col-lg-4 col-md-6 mb-4" data-aos="fade-up">
  <div class="project-card">
    <img src="images/projects/your_image.jpg" class="project-image" alt="your_alt">
    <div class="project-content">
      <h5 class="project-title"><b>Your Project Title</b></h5>
      <p class="project-description">One-line description of the project.</p>
      <a href="https://github.com/your/repo" class="btn btn-project">Source Code</a>
    </div>
  </div>
  </div>
```

## Deploy (GitHub Pages)
1. Push to GitHub in a public repo named `my-portfolio` (or any name).
2. On GitHub: Settings → Pages → Source: `main` branch, root (`/`).
3. Visit the published URL (shown by GitHub Pages). For this repo it is `https://gouranga-gh.github.io/my-portfolio/`.

## Notes
- Images are local assets under `images/`. Replace them with your own to reduce repo size.
- External libraries are loaded via CDN (no node/npm).

## Contact
- Email: [post.gourang@gmail.com](mailto:post.gourang@gmail.com)
- LinkedIn: https://www.linkedin.com/in/gouranga-jha-3a562a271/
- GitHub: https://github.com/Gouranga-GH

