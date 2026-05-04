# furkankesen.com

Minimal static personal contact page.

## Cheapest deployment

Use GitHub Pages for free hosting. GitHub Pages is free for public repositories on GitHub Free.
Publishing from a private repository requires GitHub Pro, GitHub Team, GitHub Enterprise Cloud, or GitHub Enterprise Server.

1. Create a GitHub repository for this folder.
2. Push `index.html`, `favicon.svg`, `CNAME`, and this `README.md`.
3. In the repository settings, enable Pages from the main branch.
4. Add your custom domain in the GitHub Pages settings before changing DNS.
5. In Namecheap DNS, remove any default parked/redirect records and point the domain to GitHub Pages:
   - `A` record for `@` to `185.199.108.153`
   - `A` record for `@` to `185.199.109.153`
   - `A` record for `@` to `185.199.110.153`
   - `A` record for `@` to `185.199.111.153`
   - `CNAME` record for `www` to your GitHub Pages hostname
6. Do not add wildcard DNS records.
7. Turn on `Enforce HTTPS` in GitHub Pages once GitHub allows it.

DNS and HTTPS can take a few minutes to 24 hours to settle.
