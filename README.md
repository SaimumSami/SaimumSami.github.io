# Sheikh Saimum Alam | EEE E-Portfolio

A static website (HTML, CSS, JS) that you can host free on GitHub Pages.

## Publish on GitHub Pages

1. Create a GitHub repository named `<your-username>.github.io` (or any name, e.g. `portfolio`).
2. Upload everything in this folder to the repository root (`index.html` must be at the top level).
3. Go to **Settings > Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute your site is live at `https://<your-username>.github.io/` (or `/portfolio/`).

## Things to add before you submit

| What | Where |
| --- | --- |
| Profile photo | `assets/img/profile.jpg` (square works best). It replaces the "SA" initials automatically. |
| Introduction video | `assets/video/intro.mp4` (under 100 MB), or use the YouTube option in the comment inside `index.html`. |
| Project screenshots (Simulink, COMSOL, waveforms, schematics) | `assets/img/results/` using the file names shown in each project page's "Results and Evidence" boxes. They appear automatically. |
| Real parameters and numbers | Edit the text in `projects/*.html`: component values, bandwidth, efficiency, test results. |

## Structure

```
index.html            Homepage, resume, projects, video, contact
projects/             One page per project (A to D)
assets/css/style.css  Styles
assets/js/main.js     Mobile menu
assets/img/           Diagrams (and your profile photo)
assets/Sami_CV.docx   Downloadable CV
```
