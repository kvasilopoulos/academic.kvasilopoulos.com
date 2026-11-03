# Personal website 

Hosted on Cloudflare Workers as static assets (`wrangler.jsonc`, serving `public/`). Every push to `main` is built by Cloudflare Workers Builds with extended Hugo (`npx --yes hugo-extended@0.110.0`; the theme needs the extended edition) and deployed with `npx wrangler deploy`.


The website powered by [Hugo](https://gohugo.io/) and adapted from the [Academic theme](https://sourcethemes.com/academic/).

