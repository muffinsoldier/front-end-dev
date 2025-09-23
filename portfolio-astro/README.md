# Portfolio Website

This is my personal portfolio built with [Astro](https://astro.build/) and Bootstrap 5.  
It includes my UX/UI projects as well as some extra works like illustrations.

## Pages
- **Home** – welcome message, small weather widget, featured projects  
- **Projects** – list of project cards (image, title, short text, tags, link)  
- **Project Detail** – planned, for case study pages  
- **More Works** – planned, a gallery for illustration / non-UX pieces  
- **Contact** – planned, simple links or form  

## Components
- `NavBar` – top navigation with active state  
- `Footer` – simple footer with copyright  
- `ProjectCard` – reusable card for projects (supports title, text, image, tags, link)

## Run locally
```bash
npm install
npm run dev

## Notes
Needs Node.js 18+. Weather API requires a key (not included). Some pages are still in progress.
