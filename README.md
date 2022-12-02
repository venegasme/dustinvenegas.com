# <dustinvenegas.com>

Statically generated website for <https://dustinvenegas.com> using [Hugo](https://gohugo.io) with a template named [PaperMod](https://github.com/adityatelange/hugo-PaperMod/).

## Running

Install [hugo](https://gohugo.io/commands/hugo/) and run the website locally.

```sh
# runs a local server at localhost:1313
hugo server --watch --verbose --cleanDestinationDir --disableFastRender --buildDrafts
```

## Deployed as a CloudFlare Page

- [Hugo - Hosting on CloudFlare Pages](https://gohugo.io/hosting-and-deployment/hosting-on-cloudflare-pages/)
- [CloudFlare Developers - Deploy a Hugo Site](https://developers.cloudflare.com/pages/framework-guides/deploy-a-hugo-site/).
- [CloudFlare Developers - Redirect www to apex](https://developers.cloudflare.com/pages/how-to/www-redirect/).

My CloudFlare Page build command: `hugo -b $CF_PAGES_URL`, environment variables: `HUGO_VERSION=v0.92.2`.
