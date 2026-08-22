# Deployment Handoff

## GitHub

Repository: `obi-somu/cleanspace-malta-production`

Production branch: `master`

## Netlify

Static site configuration:

- Build command: none
- Publish directory: `.`
- Base directory: repository root

After GitHub upload, Netlify should be connected to this repository for continuous deployment. Every push to `master` should trigger a production deployment.

## After first production deployment

Update the site's canonical URLs and sitemap to the final Netlify/custom-domain URL, then commit and push those changes.
