# Milad Golmoradi — Engineering Portfolio

A static, responsive portfolio website for mechanical design, robotics, system dynamics and mechatronics work. No installation or build step is required. **All displayed project figures are taken from supplied engineering reports, CAD/project materials or the previous portfolio** (rather than invented experimental data).

## Live website setup (GitHub Pages)

1. Create a **public** GitHub repository, such as `engineering-portfolio`.
2. Extract the ZIP archive on your computer. Upload **the contents of the extracted `Milad_Golmoradi_GitHub_Portfolio` folder**, not the ZIP itself, into the repository's root. `index.html` must sit at repository root.
3. In the repository, navigate to **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, branch **main**, folder **/(root)**, and save.
5. Once GitHub Pages publishes the site, the typical address will be `https://YOUR-USERNAME.github.io/engineering-portfolio/`.
6. Test the home page, project case studies, PDF links, DOI links, and image previews. Then add your public portfolio URL as a hyperlink named **Engineering Portfolio** in your CV.

GitHub Pages requires time to publish changes after committing. `index.html` and `.nojekyll` are already provided; GitHub Actions and Node are **not required**.

## Contents

- `index.html` — homepage with project discovery, research and contact links.
- `projects/*.html` — 10 engineering case studies with real figures, methods, personal contribution, outcomes and limitations.
- `assets/images/` — optimized images sourced from the provided materials.
- `assets/css/style.css` — responsive visual styling.
- `assets/js/main.js` — project category filters.
- `documents/Milad_Golmoradi_Engineering_Portfolio.pdf` — the reviewed eight-page portfolio.
- `documents/*.pdf` — detailed supporting reports, with student-number identifiers removed where found and identifying assignment covers removed for CMS reports. 
- `UPLOAD_GUIDE_FA.md` — concise Persian publishing guide.

## Scope and attribution

- **Robot end-effector:** The aluminum tool-holder CAD design was Milad's personal contribution; wider robot dynamics and simulation work was collaborative. The original group presentation is not distributed in this package because group-member consent for its public distribution has not been confirmed. Selected technical screenshots are used as examples of team project results.
- **Moss segmentation:** A collaborative project. A sanitized public selection of the slides is included, with the identifying cover removed.
- **uPVC machine:** Reverse engineering and CAD reconstruction of an existing machine; not a claim of inventing or manufacturing it.
- **Cruise, steering, pendulum, bicycle, Kalman tracking, and buck converter:** Modeling/simulation studies, not physical product demonstrations.
- **Research papers:** Publication DOI links are included; publisher-formatted paper PDFs are not redistributed because copyright/reuse rights may vary.
- **University homework covers:** Excluded from technical reports to keep the public presentation professional and remove matricola identifiers. Supporting report content may still retain academic language, which is normal for source material.
- **Mechanical CAD native files and source code:** Not provided in this chat's accessible files, so they are not included or invented. You can add original CATIA/SolidWorks/Inventor/MATLAB project files later after reviewing privacy, licenses and sharing rights.

## Updating content

Project pages are plain HTML files inside `projects/`; image files live in `assets/images/`. To replace visuals with original higher-resolution exports, upload the new image and update the `<img src>` reference. To add projects, duplicate a project page and link it from `index.html`.

## Contact

- [LinkedIn](https://www.linkedin.com/in/milad-golmoradi-4b556298/)
- [Google Scholar](https://scholar.google.com/citations?user=z2pCdiEAAAAJ&hl=en)
- Email: golmoradi17@gmail.com

This package is meant to be public. **Review the information before publishing**, especially detailed source reports and screenshots for confidentiality or third-party permissions. This is a curated portfolio, not a repository of private production/CAD designs.
