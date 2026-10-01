# The Keep by Handgraaf Estates

Source for [systems.handgraafestates.com](https://systems.handgraafestates.com), the estate operating system provided by Handgraaf Estates.

The Keep begins at placement handover. It supports onboarding, household standards, operating procedures, records, maintenance, vendors, and continuity. Recruitment, assessment, reference verification, background screening, and candidate applications belong to [Our Process](https://ourprocess.handgraafestates.com) and are maintained in the separate `handgraaf-our-process` repository.

## Project structure

- `index.html` — production landing page
- `netlify.toml` — Netlify deployment configuration

The site is a standalone static HTML deployment with no package installation or build step.

## Local preview

```sh
python3 -m http.server 4173
```

Open `http://127.0.0.1:4173/`.

## Deployment

Netlify publishes the repository root automatically from `main`.

- Production domain: [systems.handgraafestates.com](https://systems.handgraafestates.com)
- Dashboard demonstration: [demo.handgraafestates.com](https://demo.handgraafestates.com)
- Netlify site: `estatehandgraafestates.netlify.app`

After publishing, verify the production page on desktop and mobile and confirm that links to Our Process and the dashboard demonstration resolve correctly.

## Domain

The `systems` DNS CNAME points to `estatehandgraafestates.netlify.app`. TLS is managed by Netlify.
