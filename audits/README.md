# Prospect audits

One file per prospect: `audits/<slug>.html` (lowercase, letters, numbers and dashes).

Prospects open them at `https://automate2scale.io/your-audit?a=<slug>` (the GHL page holding `ghl-audit-loader.html`).
The audit is open; "The new site" asks for first name + email, posts to the GHL webhook
(source "Website Audit - Prototype Unlock"), then unlocks and shows a "Book a Strategy Session" bar.
Mark's preview without the gate: add `&preview=1`.
