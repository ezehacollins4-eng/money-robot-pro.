MONEY ROBOT PRO — ANDROID WEB APP
=================================

Included
- Professional mobile-first dashboard
- Job-board search links (Google Jobs search, Upwork, LinkedIn, Jobberman Nigeria, Freelancer, Remote OK)
- Local skill-overlap scoring for pasted job descriptions
- Tailored proposal draft generator
- Application pipeline with status, job link, notes and follow-up date
- Task planner with completion tracking
- Income/expense tracker in Nigerian naira and a six-month visual
- Professional profile and downloadable profile summary
- JSON export/import backup
- Installable PWA manifest and service worker for offline shell caching

IMPORTANT LIMITS
- The job-match score is a local skills-overlap estimate, not a live AI model or a prediction of being hired.
- Proposal drafting uses templates in the browser; it does not call an AI API.
- Job searches open external websites. No job board is scraped, and no applications are submitted automatically.
- No earnings are guaranteed.
- All records are stored in this browser's local storage. Export backups regularly. Browser data clearing can erase records.
- Never put API keys or passwords into this front-end app.

HOW TO RUN ON ANDROID
1. Download and unzip this package.
2. To test quickly, open index.html in a browser. Some PWA features require hosting over HTTPS.
3. For the installable app experience, upload the contents of this folder to a static host such as Netlify, Cloudflare Pages or GitHub Pages.
4. Open the hosted HTTPS URL in Chrome on Android.
5. Use Chrome menu (⋮) → Add to Home screen / Install app.

PUBLISHING
Upload index.html, manifest.webmanifest, sw.js and icon.svg together, keeping their filenames unchanged. No build step is needed.

NEXT STEP FOR REAL AI
A true hosted AI assistant requires a secure backend/server function and an AI provider API key stored server-side. Do not place secret API keys in index.html. Live job aggregation may also require authorized APIs and compliance with each job board's terms.
