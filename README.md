# CleanSpace Malta

Production-ready static website for **CleanSpace Malta**, a local cleaning service focused on rooms, studios, shared apartments, small flats and move-in / move-out cleaning in Malta.

## Production goals

- Make the service understandable within a few seconds.
- Convert Facebook and direct traffic into WhatsApp enquiries.
- Keep the experience lightweight, mobile-first and trustworthy.
- Avoid invented testimonials, certifications, insurance claims or business-registration claims.
- Keep price information clearly described as guidance until a final quote is confirmed.

## Stack

- Semantic HTML5
- Modern responsive CSS
- Small vanilla JavaScript navigation helper
- WebP/PNG image assets
- Schema.org LocalBusiness + FAQ structured data
- Netlify configuration

## Contact configured

- Business phone / WhatsApp: `+356 7908 5861`

## Local development

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

### Netlify

- Build command: **none**
- Publish directory: `.`
- Production branch: `master`

The included `netlify.toml` sets the publish directory and baseline security/cache headers.

## Post-deployment SEO checklist

After the final public URL is known:

1. Add a canonical URL to `index.html`, `privacy.html` and `terms.html`.
2. Change Open Graph image references to absolute URLs if desired.
3. Add the final website URL to the LocalBusiness structured data.
4. Create `sitemap.xml` using the final domain and reference it from `robots.txt`.
5. Verify the site in Google Search Console if the service becomes an established public business.

## Editing rule

Do not add claims such as "insured", "licensed", "verified cleaners", "background checked", "registered company" or customer-review scores unless they are factually verified and approved for publication.
