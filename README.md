# Strategic Lense — Static Site Template

This is the visual/frontend layer of your IR publication site. Open `index.html` in a
browser to preview it locally — all pages link to each other.

## What's here
- index.html          Home
- articles.html        Articles index (search/filter UI, list view)
- article-single.html  Full article template (body, sources, citation box, related articles)
- publications.html    Publications (policy briefs, working papers, etc.)
- research.html        Research projects (with status badges)
- about.html            Author bio, interests, timeline, skills
- cv.html               CV summary + download button
- contact.html          Contact form + academic links + newsletter box
- style.css             Shared design system for every page

## What's NOT here (needs real backend work)
- Publishing new articles without editing HTML — needs a CMS
- The contact form and newsletter box are visual only — wire to a form service
  (e.g. Formspree, Netlify Forms) or a backend
- No database, no auth, no admin dashboard

## Recommended next step
Rebuild this as a Next.js project with articles as Markdown files in a GitHub repo,
deployed free on Vercel. Add Decap CMS (free, git-based) for a real "write and publish"
admin screen with no server or database to maintain. Say the word and I'll scaffold
the actual Next.js starter project next.

## Placeholder content
Bios, CV entries, and the academic timeline are marked with placeholder notes —
replace with your real information before publishing. Do not leave invented credentials in.
