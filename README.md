# Debdut Chowdhury — Portfolio Website

Source for my personal portfolio website.

## About

I'm a **Senior Data Analyst** with nearly 4 years of experience designing scalable **ETL pipelines**, **cloud architectures**, and **data warehousing** solutions across **GCP** and **AWS**. I work with **Python**, **SQL**, **PySpark**, and **BigQuery**, and turn complex data into executive insight through **Power BI**, **Tableau**, and **Looker** dashboards. This site highlights:

- Data engineering, cloud migration, and analytics & BI work
- Tech stack and skills
- Work experience, education, and achievements
- Personal project: NetGuardAI (ML-powered network anomaly detection)
- Résumé download
- Contact links (email, phone, LinkedIn, GitHub)

---

## Features

- Single self-contained `index.html` — no build step and no dependencies (the only external request is the Fraunces font from Google Fonts)
- Dark theme by default, with a persistent light/dark switcher (`localStorage` + `prefers-color-scheme` fallback)
- Custom warm light theme (`#FAEFD4` background, `#4A3D1C` text)
- Fully responsive, accessible (semantic landmarks, skip link, focus-visible states), and print-friendly
- Résumé download front and center

---

## Tech Stack

- Plain HTML5 + CSS (inlined, no framework)
- Vanilla JavaScript for the theme toggle, scroll reveal, and active nav link
- Can be hosted for free on GitHub Pages, Netlify, or Vercel

---

## Project Structure

```
.
├── index.html                  # The entire website (HTML + CSS + JS)
├── Debdut_Chowdhury_Resume.pdf # Résumé linked from the download buttons
└── README.md
```

---

## Run Locally

No installation needed. Open `index.html` in your browser, or serve the folder with any static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## Résumé

Download it directly from the site, or [grab the PDF here](./Debdut_Chowdhury_Resume.pdf).

---

## Contact

- Email: [debdut.chowdhury.official@gmail.com](mailto:debdut.chowdhury.official@gmail.com)
- Phone: [+91 6290097207](tel:+916290097207)
- LinkedIn: [linkedin.com/in/debdutchowdhury](https://linkedin.com/in/debdutchowdhury)
- GitHub: [github.com/deb2t](https://github.com/deb2t)

---

> If you like this project, feel free to star the repo and connect with me on LinkedIn.
