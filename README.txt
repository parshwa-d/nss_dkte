DKTE NSS Website

Files:
- index.html: main website with volunteer registration form
- thank-you.html: confirmation page after registration submission
- assets/: logos (if used by the page)

Backend form storage:
The registration form is configured for Netlify Forms. Deploy this folder to your Netlify site with form detection enabled. After deploying, submit one test registration, then open Netlify Dashboard > your site > Forms > volunteer-registration to view submissions. If the form does not appear, check Site configuration > Forms and enable form detection, then trigger a new deploy.

Important: Netlify Forms stores submissions in your Netlify site dashboard; it is not a separate SQL database. Limit dashboard access to authorized NSS staff and add a privacy notice/consent if required by your institution.
