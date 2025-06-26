[https://readingtechfolk.org/](https://readingtechfolk.org/)

This repository deploys automatically to **Cloudflare Pages**. A GitHub
Actions workflow runs `cloudflare/wrangler-action` on every push to
`main` and for all pull request events, creating preview deployments for
PRs.

To enable deployments you must set the following repository secrets:

- `CF_API_TOKEN` – API token with permission to deploy Pages projects.
- `CF_ACCOUNT_ID` – the Cloudflare account ID that hosts the project.
