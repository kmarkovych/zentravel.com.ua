# zentravel.com.ua landing

Static GitHub Pages redirect site for the legacy domain zentravel.com.ua, pointing visitors to cruise-life.pro (Cruise Life, current owner of the ZenTravel brand).

## Reuse for another legacy domain

1. Copy this directory to a new folder.
2. Update `CNAME` with the new domain (no trailing newline).
3. Change the wordmark, hero and tile copy in `index.html` and `404.html` to match the old brand.
4. Update `canonical`, Open Graph `og:url`, `sitemap.xml` loc and `robots.txt` Sitemap to the new domain.
5. Create a new GitHub repo, push this directory, enable Pages (branch `main`, root) and add a custom domain matching `CNAME`.
6. Point the registrar's DNS: apex `A` records to GitHub Pages IPs (or `ALIAS`/`ANAME` to `<user>.github.io`), plus `www` `CNAME` to `<user>.github.io` if needed.
