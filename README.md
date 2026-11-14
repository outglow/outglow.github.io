# outglow.github.io

The Outglow website, https://outglow.github.io/. Its source is `site/` of
[outglow/outglow](https://github.com/outglow/outglow); `.github/workflows/pages.yml`
here builds it with that repository's `site.yml` (base `/`) and deploys it. The website
workflow of outglow/outglow writes the commit to build to `SOURCE` and pushes it (deploy key),
so the site here follows every change of the site there and every release.
