# jaeddelosa.tech

Static site, no build step. Upload the files as they are.

```
index.html              page (minified)
assets/styles.min.css   all styles (minified)
assets/app.min.js       all scripts: nav, tabs, Frontdesk chat widget (minified)
_headers                Cloudflare security + cache headers
robots.txt, sitemap.xml
jed.jpeg, favicon.ico   add these yourself
```

## Deploy on Cloudflare Pages

**From GitHub:** Pages → Connect to Git → pick this repo →
Framework preset **None**, Build command **(leave empty)**, Build output directory **/** → Deploy.

**Without GitHub:** Pages → Upload assets → drag this folder in.
