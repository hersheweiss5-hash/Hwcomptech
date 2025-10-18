HW CompareTech — Vercel-ready ZIP
----------------------------------
Contents:
- dist/ (drop into Vercel upload)
- dist/index.html (homepage)
- dist/contact.html (contact form uses mailto fallback and saves a local backup)
- Click tracking: stored in browser localStorage 'hw_clicks' and export via button
- GA4 Measurement ID is included and loads after cookie consent

Deploy (manual):
1. Go to https://vercel.com/new
2. Choose 'Deploy manually' -> Upload the ZIP file
3. Wait ~10-30 seconds for the preview URL (e.g. https://yourproject.vercel.app)
4. Test: open site, accept cookies, click Buy on a product, then use 'Export click log' to download hw_clicks.json

Notes:
- To receive contact form submissions by email reliably, connect a form provider (Formspree, Vercel Forms) or configure backend handling.
- When ready, I can convert localStorage click logs to a serverless endpoint for long-term storage.
