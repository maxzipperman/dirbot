Zipperman Law — Static Site (Base)

This folder contains the single-file static site base you provided. All CSS and JS are inline in `index.html` for easy editing.

Quick edits
- Main file: `index.html`
- Email to receive form emails: search for `INTAKE_EMAIL`
- Navigation and routes: the `routes` object in the `<script>` section
- Content sections: look for `renderHome`, `renderApproach`, `renderService`, `renderServices`, `renderResources`, `renderReferrals`, `renderPayments`

Preview locally
1) From this folder:

```bash
cd /workspace/site
python3 -m http.server 8000
```

2) Open `http://localhost:8000` in your browser (or your editor's preview).

Notes
- The contact and referral forms use a `mailto:` link that opens your email client; no server is required.
- When you're ready, this can be deployed on any static host (GitHub Pages, Netlify, Vercel, S3/CloudFront, etc.) by serving this folder as the site root.