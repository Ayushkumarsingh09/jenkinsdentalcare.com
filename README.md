# Live Website

Live Demo: https://jenkinsdentalcarecom.vercel.app

# Jenkins Dental Care — Premium Website Redesign

A complete redesign of [jenkinsdentalcare.com](https://www.jenkinsdentalcare.com/) — built as a fast, static site that communicates trust, comfort, and hometown family care.

## Brand Positioning

**"Your Hometown Dental Family"** — premium private dentistry blended with Southern hospitality, modern healthcare branding, and family-centered care.

## Tech Stack

- Pure HTML, CSS, and JavaScript (no build step required)
- Standard shared hosting compatible
- Mobile-first responsive design
- SEO-friendly semantic markup with Schema.org structured data
- Lightweight — no frameworks, no VPS required

## Project Structure

```
jenkinsdentalcare.com/
├── index.html          # Homepage (all 14 sections)
├── patients.html       # New patient information
├── css/
│   └── styles.css      # Design system & styles
├── js/
│   └── main.js         # Interactions & animations
└── assets/
    └── images/         # Real clinic photography
```

## Local Preview

```bash
# Python
python -m http.server 8080

# Node.js
npx serve .
```

Then open `http://localhost:8080`

## Deployment

Upload all files to your web host's public directory (e.g. `public_html`). No server configuration needed.

## Contact Info (Site Content)

- **Phone:** 662-887-3426
- **Email:** jenkinsdentalcare@yahoo.com
- **Address:** 211 Highway 82 East, Indianola, MS 38751
- **Hours:** Mon–Thu 8:00 AM – 5:00 PM

## Notes

- All photography sourced from the existing Jenkins Dental Care website
- Contact form shows a confirmation message locally; connect to your form handler (Formspree, email service, etc.) for production
- Patient form PDFs can be linked once provided by the clinic
