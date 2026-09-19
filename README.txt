Anil Kumar Yadav — Portfolio Website (Multi-Page Version)
============================================================

PAGES
-----
index.html            Home (Hero)
about.html             About Me
skills.html            Skills
experience.html        Experience
projects.html          Featured Projects + Achievements
services.html          Services
certifications.html    Certifications + Testimonials
blog.html              Blog
contact.html           Contact (form, map placeholder, WhatsApp/Call/Email buttons)

SHARED FILES
------------
css/style.css          All styling (colors, layout, animations, dark/light theme) — shared by every page
js/script.js            All interactivity (theme toggle, mobile menu, typing effect, counters, reveal
                        animations, scroll progress bar) — shared by every page
assets/Anil-Kumar-Yadav-Resume.pdf   Auto-generated 1-page resume linked from the "Download Resume" buttons

HOW TO USE
----------
1. Double-click index.html to open the site locally in any browser — the top nav links between
   the pages above (About, Skills, Experience, Projects, Services, Certifications, Blog, Contact).
2. To publish it live, upload the whole "portfolio" folder to any static host:
   - Netlify / Vercel (drag & drop the folder)
   - GitHub Pages
   - Any shared hosting (upload via FTP / cPanel File Manager)
3. No build step, no dependencies — it's plain HTML/CSS/JS. Every page shares the same
   css/style.css and js/script.js, so edits to styling or behaviour only need to be made once.

WHAT YOU MAY WANT TO PERSONALISE
---------------------------------
- Replace the "AY" initials avatar on about.html with a real photo if you have one
  (swap the .avatar-card div for an <img> tag).
- Update assets/Anil-Kumar-Yadav-Resume.pdf with your real, detailed resume (same filename,
  or update the href in each page's "Download Resume" button/link).
- Replace the placeholder social links (LinkedIn, GitHub, Twitter/X, Instagram, Facebook) in
  the footer of every page with your real profile URLs.
- Replace the "#" links on Featured Projects (Live Demo / Case Study) and Blog cards with your
  real project/article URLs once you have them.
- The Google Map on contact.html is a placeholder box — swap it for a real embedded Google
  Maps iframe for Indira Nagar, Sector 19, Lucknow if you'd like a live map.
- The contact form is a static front-end demo (shows a "Message Sent" confirmation but does not
  actually send email). Connect it to a form backend such as Formspree, EmailJS, or your own
  server endpoint to receive real messages.

NOTE
----
If you'd prefer the original single-scrolling-page version (everything in one index.html with
in-page anchor navigation instead of separate pages), that version is included as
index_single_backup.html for reference — just rename it to index.html to use it instead.

FEATURES INCLUDED
------------------
Dark/Light mode toggle · Sticky nav with per-page active-link highlighting · Scroll progress bar ·
Typing animation headline on Home · Scroll-reveal animations · Animated skill progress bars ·
Animated achievement counters · Glassmorphism/gradient hero with a "live SERP" signature panel ·
Mobile navigation drawer · Floating WhatsApp button · Back-to-top button · SEO meta tags,
Open Graph, Twitter Card & Schema.org (Person) structured data on every page · Fully responsive layout.
