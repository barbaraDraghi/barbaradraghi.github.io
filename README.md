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
├── _data/nav.yml
├── _includes/
│   ├── head.html
│   ├── header.html
│   ├── nav.html
│   └── footer.html
├── _layouts/
│   ├── default.html
│   ├── home.html
│   └── page.html
├── assets/
│   ├── css/style.css
│   └── img/
├── pages/
│   ├── research.md
│   ├── coffee-learn.md
│   ├── events-talks.md
│   ├── projects.md
│   └── contact-cv.md
├── index.md
└── README.md


```
