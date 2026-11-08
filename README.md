# brandongaona.com

Personal portfolio site. Plain HTML, CSS, and JavaScript with no build step.

## Files

- `index.html`: the whole site (styles and scripts inline)
- `resume.pdf`: linked from the Resume buttons

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Deploy

1. Push this folder to a GitHub repo.
2. In Vercel, choose Add New Project, import the repo, leave the framework preset as "Other", and deploy.
3. Add a custom domain under Project Settings > Domains and set the DNS records Vercel shows at your registrar.

Every push to `main` redeploys automatically.

## Updating

- Projects: edit the `.flagship` block or add an `<li>` to `.plist` in the Projects section.
- Resume: replace `resume.pdf` with the new file under the same name.
