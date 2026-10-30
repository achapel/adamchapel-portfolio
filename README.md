# Adam Chapel Portfolio — starter

A small, responsive static portfolio scaffold for photography, about, projects, journal, and contact sections.

## Before publishing
1. Confirm you own `adamchapel.com` before using it as the canonical domain.
2. Replace photography placeholders with your own appropriately sized, compressed images.
3. Confirm the bio and project descriptions are accurate and comfortable to publish.
4. Add a real contact method only if you want it public. No email address has been exposed in this starter.
5. Update title, description, canonical URL, Open Graph metadata, and sitemap if the domain changes.
6. Add a privacy notice before enabling analytics if appropriate for your audience and applicable requirements.

## Local preview
From this directory, run:

```bash
python -m http.server 8000
```

Then open http://localhost:8000

## Cloudflare Pages
This is a static site with no build step. Create a GitHub repository, push these files to its root, then create a Cloudflare Pages project connected to that repository. Use the repository root as the build directory and leave the build command empty. Add the custom domain only after registering it and configuring the required DNS.

## SEO learning checklist
- Verify one descriptive page title and meta description.
- Use semantic headings (one main H1).
- Add descriptive alt text to meaningful images.
- Keep images compressed and appropriately sized.
- Check mobile layout and page speed.
- Verify ownership in Google Search Console and submit the sitemap.
- Add GA4 after creating a property; document what events you intend to measure.
