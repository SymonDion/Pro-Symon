# Symon Mwafulirwa — Portfolio Website

A responsive multi-page developer portfolio built with HTML5, CSS3 and vanilla JavaScript. No build tools or framework are required.

## Run locally
1. Extract the ZIP.
2. Open the project folder.
3. Double-click `index.html`, or use VS Code with the Live Server extension.
4. For local testing, open `http://127.0.0.1:5500` if using Live Server.

## Pages
- `index.html` — home
- `about.html` — biography and skills
- `portfolio.html` — searchable and filterable project gallery
- `services.html` — service listings
- `blog.html` — searchable starter article cards
- `testimonials.html` — testimonial placeholder page
- `contact.html` — contact details and enquiry form

## Customisation checklist before publishing
- Replace the SM monogram placeholder on About with a real professional portrait.
- Add real project screenshots to `images/` and update portfolio cards.
- Add verified live-demo and source-code URLs for projects. Do not present demo concepts as client work.
- Replace the Facebook search URL with the exact public profile or Page URL.
- Update the CV text with accurate education, experience, certifications and links.
- Add a backend form endpoint (or a form service) if you want submissions delivered without opening the visitor's email application.
- Add genuine client testimonials only with permission.
- Add your own domain to canonical URLs and Open Graph metadata when deploying.

## Contact form behaviour
The contact form validates fields in the browser and prepares an email using `mailto:`. It does not store or transmit submissions itself. For reliable enquiry delivery, connect it to a secure backend or trusted form service.

## WhatsApp
The WhatsApp link uses Malawi country code +265 and strips the leading zero from 0994047333.

## Languages and themes
- Theme choice: Developer Dark, Cyberpunk, Gold, Malawi.
- Language switch: English and Chichewa starter translation dictionary. The primary homepage content and global navigation are translated; add translation keys for all additional page content to achieve complete site-wide translation.
- Preferences are saved in localStorage.

## Deployment
Upload the extracted folder contents to any static hosting provider (GitHub Pages, Netlify, Cloudflare Pages or a standard web host). Ensure `index.html` is at the public root.

## Accessibility and performance
Semantic HTML, responsive layouts, visible form labels, reduced-motion support, lazy reliance on external assets avoided, and no JavaScript framework. Google Fonts are loaded externally; local system fonts remain fallback.
