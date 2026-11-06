# GoogieHost Web Hosting Review Directory

A responsive, static hosting-review directory built with plain HTML, CSS and JavaScript.

## Project files

- `index.html` — complete website, including provider cards, search, category filters, testing methodology and FAQs.
- `.nojekyll` — tells GitHub Pages to publish files without Jekyll processing.
- `netlify.toml` — Netlify build and publish configuration for a future deployment.
- `render.yaml` — retained as an optional Render Static Site configuration.

## Deploy on GitHub Pages

No build command or package installation is required.

1. Open this repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then click **Save**.
5. Wait for the Pages deployment to finish. GitHub will show the published URL in the Pages section.

For this repository, the expected project-site URL is:

`https://bestfreewebhosting.github.io/webhosting/`

The URL will work after Pages is enabled successfully and the repository is accessible to Pages.

## Deploy on Netlify later

The same files are compatible with Netlify; no conversion is needed.

1. Sign in to Netlify and choose **Add new project → Import an existing project**.
2. Connect GitHub and select `bestfreewebhosting/webhosting`.
3. Netlify reads `netlify.toml` automatically.
4. Keep the build command empty and publish directory as `.`.
5. Deploy. Future pushes to the connected branch can trigger new deployments.

You can also use Netlify's manual deploy by uploading the site files, with `index.html` at the published folder's root.

## Optional Render deployment

The `render.yaml` file is retained for a future Render Static Site deployment. It is not needed for GitHub Pages or Netlify.

## Local preview

Open `index.html` in a browser, or serve the repository root with any local static-file server.

## Before publishing

- Verify every provider review URL and replace any outdated slug.
- Check every displayed rating, score, test date and performance claim against the linked review.
- Do not publish placeholder or estimated test results as measured facts.
- Keep the canonical URL pointed at the intended primary GoogieHost page if this repository is only a mirror/demo. If this becomes the permanent public review page, update the canonical and social metadata to the final domain.
- Keep affiliate disclosures visible where affiliate links are used.

## Technical notes

This is a static front-end website. It does not require Node.js, PHP, a database, environment variables or a server-side runtime. Search and category filtering run in the browser with JavaScript.
