# Setup

1. Create a new repo on GitHub — any name, e.g. `cybersecurity-portfolio` (not `ethansamuel71.github.io`, since that name's already taken by your vcard site).
2. Drop `index.html` and the `assets/` folder into it.
3. Settings → Pages → Deploy from branch → main → / (root). Your site publishes at:
   `https://ethansamuel71.github.io/cybersecurity-portfolio/`

# Adding a project or certificate

Open `index.html`, find the `const projects = [...]` or `const certs = [...]` block near the bottom.
Copy one `{ ... }` entry, edit the fields, add a comma. Save, commit, push.

- Linking to a repo, Credly badge, or anything already online → paste the URL in `link`.
- Uploading an actual file (a PDF certificate, a writeup) → put the file in `assets/` (certificates go
  well in `assets/certs/`), then set `link` to its path, e.g. `assets/certs/security-plus.pdf`.

# Resume

Put your resume PDF at `assets/resume-ethan-samuel.pdf` — the "Download resume" button already points there.

# Before you push

Replace the placeholder email/LinkedIn in the footer, and swap the monogram/bio text in the header for real content.
Double-check no real IPs, hostnames, or screenshots with sensitive info end up in `assets/`.
