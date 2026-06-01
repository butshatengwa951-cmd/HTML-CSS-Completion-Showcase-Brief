# My First Portfolio

**A personal portfolio website built with HTML & CSS featuring earthy tones, layered opacity, and organic design elements inspired by nature.**

## Short Project Description
A multi-page responsive portfolio showcasing my web development journey, skills, and projects. The design uses natural colors and opacity to create a retrospective, nostalgic feel — like flipping through an old field journal or weathered photo album.

## Purpose of the Website
This site serves as my professional home base for:
- Introducing myself and my background
- Displaying technical skills learned in class
- Showcasing coding projects and exercises
- Documenting my learning journey in web development
- Providing a way for peers, mentors, and employers to contact me

## Features of Your Project
- **4-page structure**: `index.html`, `about.html`, `projects.html`, `contact.html` with consistent navigation
- **Retrospective nature aesthetic**: Moss green, river stone, bark brown, morning mist, and clay palette using `rgba()` opacity layers
- **Responsive design**: Mobile-first layout that adapts to tablet and desktop using media queries
- **Interactive elements**: Hover transitions, smooth scrolling, button states
- **Accessible forms**: Labeled inputs, proper form structure with validation-ready markup
- **Semantic markup**: Clean, SEO-friendly HTML structure
- **Zero external dependencies**: No fonts, images, or libraries — works fully offline

## HTML Concepts Used
- Document structure: `<!DOCTYPE html>`, `html`, `head`, `meta charset`, `meta viewport`, `title`, `body`
- Semantic elements: `header`, `nav`, `main`, `section`, `article`, `footer`
- Text content: `h1-h3`, `p`, `span`, `strong`, `em`
- Links & navigation: `a href` with internal page links
- Lists: `ul`, `ol`, `li` for skills and navigation menus
- Media: `img` with descriptive `alt` text using inline SVG
- Tables: `table`, `thead`, `tbody`, `tr`, `th`, `td` for education timeline
- Forms: `form`, `label for`, `input type="text|email"`, `textarea`, `button type="submit"`
- Comments and proper indentation for readability

## CSS Concepts Used
- **Selectors**: Element, class `.class`, ID `#id`, pseudo-classes `:hover`, `:focus`, `:nth-child`
- **Box model**: `margin`, `padding`, `border`, `box-sizing: border-box`
- **Layout**: Flexbox for navigation and alignment, CSS Grid for project card layout
- **Responsive design**: `@media` queries for 3 breakpoints (mobile ≤768px, tablet 769-1024px, desktop >1024px)
- **Color & opacity**: CSS custom properties `:root`, `rgba()`, `hsla()` for layered effects
- **Typography**: `font-family` system stack, `font-size`, `line-height`, `letter-spacing`, `text-align`
- **Visual effects**: `box-shadow` with opacity, `border-radius`, `transition: all 0.3s ease`, `opacity`
- **Backgrounds**: `linear-gradient` for paper texture and depth
- **Organization**: External `style.css`, CSS comments, consistent spacing, DRY principles

## How to View the Project
**Option 1: Run Locally**
1. Download all files and maintain this folder structure: portfolio/
| – index.html
| – about.html
| – projects.html
| – contact.html
| – css/
| – style.css
2. Double-click `index.html` to open in your browser

**Option 2: GitHub Pages**
1. Create a new repo named `your-username.github.io` or `portfolio`
2. Upload all files maintaining the folder structure
3. Go to Settings → Pages → Deploy from `main` branch
4. Visit `https://your-username.github.io/portfolio`

## Screenshots
**Desktop View**

<img width="1920" height="1080" alt="Screenshot 2026-06-01 110048" src="https://github.com/user-attachments/assets/939e2555-6b0c-4b1a-bd86-17d0c388c777" />

*Home page with hero section, nature palette, and opacity overlays*

**Mobile View**

![alt text](<Screenshot 2026-06-01 112338-1.png>)

*Responsive project cards stacking on mobile*


## Challenges Faced
1. **CSS file linking**: Initial 404 errors because `style.css` wasn’t created yet. Solved by understanding relative paths and folder structure.
2. **Opacity layering**: Getting the right balance of `rgba()` values so text stayed readable over textured backgrounds. Used contrast checking and adjusted alpha values.
3. **Responsive grid**: Project cards looked cramped on tablet. Fixed with media query breakpoints to switch from 3-col → 2-col → 1-col.
4. **No external resources**: Creating visual interest without images or Google Fonts. Leaned into CSS gradients, SVG shapes, and typography instead.

## What I Learned
- How to structure a multi-page site with shared CSS
- The importance of semantic HTML for accessibility and SEO
- Using Flexbox vs Grid and when each makes sense
- How opacity and layering create depth and mood in design
- Mobile-first responsive workflow with media queries
- Git/GitHub workflow: commits, pushing, GitHub Pages deployment
- Debugging with browser DevTools for CSS and file paths

## Future Improvements
- Add JavaScript for form validation and mobile hamburger menu
- Implement a dark mode toggle using CSS variables
- Create a blog section using `article` elements
- Add actual project screenshots instead of SVG placeholders
- Animate sections on scroll with `IntersectionObserver`
- Improve accessibility with ARIA labels and keyboard navigation
- Add a downloadable CV/Resume button
- Connect contact form to Formspree or Netlify Forms

## Your Name
**Butsha Tengwa**
Aspiring Web Developer | Cape Town, Western Cape
butshatengwa951@gmail.com | https://www.linkedin.com/in/butsha-tengwa-66378a313/ | https://github.com/butshatengwa951-cmd

## GitHub Pages / Deployed Link
🚀 **Live Site**: https://butshatengwa951-cmd.github.io/HTML-CSS-Completion-Showcase-Brief/
📂 **Repository**: https://github.com/butshatengwa951-cmd/HTML-CSS-Completion-Showcase-Brief.git

---
