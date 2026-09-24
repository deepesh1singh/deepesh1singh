# Deepesh Singh — Portfolio

A personal portfolio website built with vanilla HTML, CSS, and JavaScript. Content (skills, internships, projects, achievements, contact links) is data-driven from a single `data.js` file and rendered into the page at runtime by `script.js`.

**Live site:** _add your deployed URL here (e.g. GitHub Pages / Vercel / Netlify link)_

---

## About

Computer Science Dual Degree student at IIT Kharagpur (B.Tech. + M.Tech.), focused on machine learning, artificial intelligence, LLMs, data structures & algorithms, and system design.

## Sections

The site is a single page (`index.html`) with the following sections, each rendered from `data.js`:

| Section | Source array in `data.js` | Rendered by |
|---|---|---|
| Coursework | `COURSEWORK` | `renderCoursework()` |
| Skills | `SKILLS` | `renderSkills()` |
| Internships | `INTERNSHIPS` | `renderInternships()` |
| Projects | `PROJECTS` | `renderProjects()` |
| Coding Profiles | `CODING_PROFILES` | `renderCodingProfiles()` |
| Achievements | `ACHIEVEMENTS` | `renderAchievements()` |
| Contact | `CONTACT` | `renderContact()` |

## Skills

Each skill group in `SKILLS` carries an `icon` key that maps to an inline SVG defined in the `ICONS` object in `script.js`, rendered via the `iconOr()` helper:

```js
const SKILLS = [
  { group: "Languages & Databases",   icon: "code",   items: [...] },
  { group: "Frameworks & Libraries",  icon: "layers", items: [...] },
  { group: "Tools & Technologies",    icon: "tool",   items: [...] },
  { group: "Core Competencies",       icon: "target", items: [...] },
];
```

`renderSkills()` wraps each icon in a `.skill-icon` badge:

```js
<span class="skill-icon">${iconOr(s.icon)}</span>
```

To add a new skill group with its own icon:
1. Add a new SVG entry to `ICONS` in `script.js` (keep the `viewBox="0 0 24 24"` and `stroke="currentColor"` / `fill="currentColor"` convention so it inherits the theme color).
2. Reference that key in a new `SKILLS` entry's `icon` field.

If a group's `icon` key doesn't exist in `ICONS`, `iconOr()` silently falls back to the `code` icon, so a typo won't break the layout — but double-check the key matches exactly.

## Internships

`INTERNSHIPS` in `data.js` currently lists two entries:

- **InternPE** — AI/ML Internship (May 2026 – July 2026)
- **Amdocs Technologies** — Software Developer Intern (Dec 2025 – Mar 2026)

Each entry follows this shape:

```js
{
  org: "Company Name",
  role: "Role Title",
  period: "Month Year – Month Year",
  image: "kebab-case-slug",       // maps to image/<slug>.png
  link: "https://github.com/...",
  description: "...",
  tags: ["Tag1", "Tag2"],
}
```

## Projects

`PROJECTS` holds 37 entries, each with a `category` of `"Development"`, `"Data"`, or `"Quant"` used for the filter buttons on the page. Every project follows the same shape as internships above.

### Images

Images are loaded by the `imageBlock()` helper in `script.js`:

```js
<img src="image/${slug}.png" alt="${altText}" loading="lazy"
     onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';" />
<div class="img-placeholder">${altText}</div>
```

The `image` field on each project/internship must exactly match a filename (without extension) inside the `image/` folder. If the file is missing, the `onerror` handler swaps in a text placeholder instead of a broken image icon — so a missing file degrades gracefully rather than breaking the page.

**Naming convention:** the image slug is the kebab-case version of the project title (lowercase, spaces → hyphens, punctuation stripped), e.g.:

```
title: "Cache-Aware Performance Optimization using gem5 and RISC-V"
image: "cache-aware-performance-optimization-using-gem5-and-risc-v"
→ file: image/cache-aware-performance-optimization-using-gem5-and-risc-v.png
```

**Currently missing image files** (placeholders will show until these are added to `image/`):

| Entry | Expected file |
|---|---|
| Amdocs Technologies internship | `image/event-management-system.png` |
| High-Performance Financial Data Processing | `image/high-performance-financial-data-processing.png` |
| TaskQueue Server-Worker | `image/taskqueue-server-worker.png` |

To fix any of these, add a correctly named `.png` (a screenshot, diagram, or repo social-preview image works well) into `image/`; no code change is required once the filename matches the `image` slug already set in `data.js`.

## Tech Stack

- HTML5 / CSS3 (no framework)
- Vanilla JavaScript (ES6+), no build step
- Inline SVG icons (no icon library dependency)

## Project Structure

```
deepesh-singh-portfolio/
├── index.html          # Page structure and section containers
├── style.css           # All styling (theme, layout, components)
├── script.js           # ICONS map + render functions for every section
├── data.js             # All content: coursework, skills, internships, projects, achievements, contact
├── image/              # Project & internship screenshots (kebab-case .png filenames)
└── README.md
```

## Running Locally

No build step or dependencies — it's static HTML/CSS/JS.

```bash
git clone https://github.com/deepesh1singh/<repo-name>.git
cd <repo-name>
# then just open index.html in a browser, or serve it:
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Updating Content

All content lives in `data.js`. To add a new project, append an object to the `PROJECTS` array with a unique `id`, matching the shape shown above, and drop a correctly named image into `image/`. No changes to `index.html` or `script.js` are needed for new content — only for new sections or new skill icons.

## Coding Profiles

- **Codeforces:** [Deepesh_singh](https://codeforces.com/profile/Deepesh_singh) — Expert, 1654 rating
- **GitHub:** [deepesh1singh](https://github.com/deepesh1singh) — 37+ public repositories

## Contact

- **Email:** [deepesh002singh@gmail.com](mailto:deepesh002singh@gmail.com)
- **LinkedIn:** [deepesh-singh-05846b240](https://www.linkedin.com/in/deepesh-singh-05846b240/)
- **X (Twitter):** [@deepesh_ssingh](https://x.com/deepesh_ssingh)
- **Instagram:** [@deepesh.ssingh](https://instagram.com/deepesh.ssingh)
- **Threads:** [@deepesh.ssingh](https://threads.net/@deepesh.ssingh)

---
