[https://readingtechfolk.org/](https://readingtechfolk.org/)

## Deployment

The repository includes a GitHub Actions workflow that deploys the site to Cloudflare Pages. Deployments run automatically on every push to `main` and preview builds are created for each pull request.

Add these secrets to your repository configuration so the workflow can authenticate with Cloudflare:

- `CF_API_TOKEN` – API token used by the Wrangler action.
- `CF_ACCOUNT_ID` – Cloudflare account identifier required by the action.
