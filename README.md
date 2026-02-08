# Barbara Draghi - Personal Academic Website
This is the source code for Barbara Draghi's academic website, built for deployment on GitHub Pages.  
It features a clean modular _Jekyll_ rebuild with a dark glass aesthetic.


## 🧩 Folder Overview
   - _includes/ → reusable components (head, header, nav, footer)
   - _layouts/ → page templates for home and inner pages
   - /assets/css/style.css → glassmorphic theme stylesheet
   - /pages/ → markdown content pages (Research, Projects, etc.)

## 🌐 Access your website:
   - Once deployed, the website will be available at:  https://barbaradraghi.github.io

To run locally:
```bash
bundle install
bundle exec jekyll serve
```
Then open your browser at http://127.0.0.1:4000


## 📁 Project Structure

```
barbaradraghi.github.io/
├── _config.yml
│
├── _data/
│   ├── nav.yml                  # Navigation menu entries (title + link)
│   └── events.yml               # List of events, talks, awards, posters, etc.
│
├── _includes/                   # Reusable partials
│   ├── head.html                # <head> metadata, CSS, fonts, favicon
│   ├── header.html              # Site header (name, logo)
│   ├── nav.html                 # Navbar built from nav.yml
│   └── footer.html              # Footer section (contact info, social icons)
│
├── _layouts/                    # HTML layouts
│   ├── default.html             # Base layout with includes
│   ├── home.html                # Homepage template
│   └── page.html                # Generic page layout (for research, contact, etc.)
│
├── assets/
│   ├── css/
│   │   └── style.css            # Unified dark/light mode CSS
│   ├── images                   # Images (profile, covers, icons, etc.)
│   │   └── profile.png          
│   ├── video/                   # Background/hero videos (optional)
│
├── pages/                       # Individual content pages
│   ├── research.md
│   ├── projects.md
│   ├── events-talks.md
│   ├── coffee-learn.md
│   └── contact-cv.md
│
├── index.md                     # Homepage (uses layout: home)
├── README.md                    # Repository info & setup instructions
└── .gitignore                   # Ignore build files (_site/, cache, etc.)

```

```
