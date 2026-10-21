# Golden Hour Tools landing page

Static landing page at https://goldenhourtools.com (and www) linking to each tool.

- `public/index.html`  the page. To add a tool, copy one `<a class="tool">` block and change the link and text.
- `wrangler.jsonc`     Worker config (static assets only, custom domains for the bare domain and www)

Every push to `main` deploys through Cloudflare Workers Builds (`npx wrangler deploy`).
