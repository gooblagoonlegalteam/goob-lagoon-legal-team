# Goob Lagoon Legal Team – Official Complaint Department & Litigation Services

This repository contains the parody website for the **Goob Lagoon Legal Team**, a comedic project inspired by CaseOh’s Goob Lagoon memes.  
It is a static HTML site hosted on **GitHub Pages** and paired with a Google Form for the complaint intake system.

---

## Live Site
[https://gooblagoonlegalteam.com](https://gooblagoonlegalteam.com)

---

## Repository Contents
- `index.html` – the main website file
- `LegalTeamLogo.png` – the site’s minimalist logo
- `CNAME` – custom domain configuration for GitHub Pages (`gooblagoonlegalteam.com`)
- `README.md` – this file

---

## Deployment (GitHub Pages)
This site is deployed using **GitHub Pages**.

- All content is served from the `main` branch.
- When changes are pushed to `main`, the site automatically rebuilds within about one minute.
- The site is available at `https://gooblagoonlegalteam.github.io/goob-lagoon-legal-team/` (or at the custom domain, if configured).

---

## Updating the Site
For the maintainer:

1. Edit `index.html` directly in the repository (or locally and push).  
2. To update the complaint button, replace the Google Form link in this code block:

   ```html
   <a class="btn" 
      href="https://forms.gle/your-form-id" 
      target="_blank" rel="noopener">
      File an Official Complaint
   </a>
