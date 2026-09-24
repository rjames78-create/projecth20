ProjectH2O Website
==================
Built for: ProjectH2O — Southwest Michigan Water Solutions
Contact: ckooi2431@gmail.com | (269) 539-1185

FILES INCLUDED
--------------
index.html       - Homepage (hero, services, Clover feature, testimonials, CTA)
products.html    - Products & Services page (softeners, filtration, coolers, commercial)
about.html       - About Us / Owner Bio page (Chris Kooi)
quote.html       - Get a Free Quote form
contact.html     - Contact page with FAQ
styles.css       - Shared stylesheet for all pages
images/          - Folder for logo and any other images

HOW TO OPEN THE SITE
--------------------
Simply double-click index.html to open in your browser.
All pages are plain HTML/CSS — no server required to view locally.

IMPORTANT: ADD YOUR LOGO
------------------------
The site references images/logo.png in the navigation and footer of all pages.

1. Save the ProjectH2O logo as:
   images/logo.png

2. The logo should ideally be:
   - PNG format with transparent background
   - At least 200x200 pixels (square or landscape)

Until you add the logo file, you can use the placeholder SVG:
   images/logo-placeholder.svg

   (To use it temporarily, rename it to logo.png, or update the src= references
    in the HTML files to point to logo-placeholder.svg)

QUOTE / CONTACT FORMS
---------------------
Both the "Get a Quote" and "Contact" forms use mailto: links, which will open
your default email application when a visitor clicks Submit. The email will
be pre-filled with the form data and sent to ckooi2431@gmail.com.

Note: For a more robust solution in the future, consider a form service like:
  - Formspree (https://formspree.io) — free tier available
  - Netlify Forms (if hosted on Netlify)
  - EmailJS (https://www.emailjs.com)

These allow forms to submit directly from the website without opening an email client.

CUSTOMIZATION NOTES
-------------------
- Colors: Edit the :root variables in styles.css to change the color scheme
- Phone/Email: Search all .html files for "(269) 539-1185" or "ckooi2431@gmail.com" to update
- Bio content: Edit about.html — the timeline section under "Industry Experience"
- Service area counties: Edit about.html — the .area-counties section
- Testimonials: Edit index.html — the .testi-grid section (add real customer reviews!)
- Hours: Edit contact.html — the .hours-table section

HOSTING RECOMMENDATIONS
-----------------------
To put this site online, consider:
  - Hostinger, Bluehost, or SiteGround (shared hosting, ~$3-5/month)
  - Netlify (free for static sites: https://netlify.com)
  - GitHub Pages (free: https://pages.github.com)

Domain name ideas: projecth2o.com, projecth2omi.com, projecth2o.net

Built with care by Claude | April 2025
