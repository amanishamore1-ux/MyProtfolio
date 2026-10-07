# Anisha More | Portfolio

Anisha More's portfolio uses the supplied multi-page HTML, CSS and vanilla JavaScript design. The original card layout, typography, animations, four themes, responsive navigation, avatar lightbox, background music and arcade game are retained.

## Run locally

Extract the ZIP, open a terminal inside `Anisha-More-Portfolio`, and run:

```bash
python -m http.server 8000
```

On macOS or Linux, use `python3` if that is your Python command. Visit http://localhost:8000. No npm install or build step is required. Use a local HTTP server rather than a file URL so the animation files and browser preferences behave consistently.

## Pages

- `index.html`: introduction, portfolio navigation and resume download.
- `about.html`: background, interests and practical skills.
- `resume.html`: education, internship, categorized skills and resume viewer.
- `projects.html`: three project cards, category filters and local project-detail dialogs.
- `contact.html`: email, phone, social links, Mumbai map and email-composer form.
- `bubble-shooter.html`: preserved arcade game with neutral grid text and a link back to the portfolio.
- `assets/`: styles, JavaScript, animation files, music, project illustrations, portrait, favicon and resume.

## Content and assets

The supplied resume and LinkedIn PDF are the primary personal-information sources. The separately supplied portrait is used without changing its pixels, with CSS framing for the circular avatar and a full-image lightbox. The supplied GitHub screenshot provides the `amanishamore1-ux` username and confirms Django for the blogging project.

The bundled `assets/documents/Anisha_More_Resume.pdf` is an unchanged copy of the supplied resume. Both View Resume and Download Resume use this local PDF.

The three projects are AI-Based Blogging Website, Smart Expense Splitter and PLC-Based Door Interlocking System. No project screenshots were supplied, so the cards use abstract SVG illustrations, not product screenshots. No project dates or public demo URLs were supplied. The blogging repository in the screenshot is private; no project source-code or live-demo links are presented. The local View Details buttons work without public repositories.

No certificate files, awards, competition results or positions of responsibility were supplied, so these sections are omitted. Unsupported social accounts and numerical skill ratings are removed. Interests in data analysis, machine learning, Excel, Power BI and data structures are described as interests or areas of learning, without invented proficiency levels.

## Source differences

- The newer LinkedIn PDF names RGIT and a B.Tech in AI & Data Science; the resume names Mumbai University and a B.E. The website uses the newer B.Tech wording, RGIT and Mumbai University. The resume download is preserved as supplied.
- The resume lists the diploma as 2022–2025; the LinkedIn PDF lists 2023–2025. The website uses the resume's 2022–2025 dates and its grades: degree CGPA 9.27, diploma CGPA 9.3 and SSC 83%. The percentage is labelled as a percentage rather than CGPA.
- Both files list the internship in 2024–2025. The LinkedIn description explicitly calls it six months; the website follows that description rather than the export's automatic one-year duration label. No exact months are inferred.

## Contact form

The form opens the visitor's email application with a draft addressed to `amanishamore1@gmail.com`. The visitor sends it in their email app. It does not submit messages to a server or store them. A configured email app is required for `mailto:` links.

## Deployment

See `PUBLISHING.md`. Deploy the complete contents of `Anisha-More-Portfolio`, including all HTML files and the entire `assets` folder. No framework conversion or build tool is needed.

The existing font families, Ionicons 5.5.2 and dotLottie Player 2.7.12 are bundled locally in `assets/fonts` and `assets/vendor`. Animation, typography, icons and music load without a CDN connection. Third-party license files are included alongside these assets. Theme and music preferences are stored in the browser. Browsers may require a user interaction before playing music. The location map is an external Google Maps embed.
