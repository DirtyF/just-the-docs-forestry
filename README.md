# Just the docs - Jekyll Documentation Forestry starter

![Preview](https://user-images.githubusercontent.com/896475/47384541-89053c80-d6d5-11e8-98dc-dba16e192de9.gif)

[Live Preview](https://pmarsceill.github.io/just-the-docs/)

[Just the docs Jekyll theme](https://github.com/pmarsceill/just-the-docs) is developed by Patrick Marsceill.

## Requirements

- GitHub, GitLab or BitBucket account
- Ruby > 2.5
- Jekyll ~> 3.8

## Content Management

![](images/forestry.jpg)

[![import to Forestry](https://assets.forestry.io/import-to-forestryK.svg)](https://app.forestry.io/quick-start?repo=forestryio/just-the-docs-jekyll-starter&engine=jekyll)

This project has been pre-configured to work with [Forestry](https://forestry.io) a git-based CMS, [import your repository in Forestry](https://app.forestry.io/quick-start?repo=forestryio/just-the-docs-jekyll-starter&engine=jekyll) and you'll be able to edit and preview your site ✨.

Any changes you make in Forestry will be commited back to the repo, and deployed if you use [Netlify](#netlify) or [Vercel](#vercel).

## Local development

```bash
# install project dependencies
bundle install
# Start local dev server
bundle exec jekyll serve
```

## Deployment and hosting

### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/forestryio/just-the-docs-jekyll-starter)

1. Set the build command to: `jekyll build`
2. Set the publish directory to: `_site`

That's it, now your site gets deployed automatically on `git push` or when saving documents from Forestry.

### Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/project?template=https://github.com/forestryio/just-the-docs-jekyll-starter)

Follow the steps.

## Feedback

[Open an issue](https://github.com/pmarsceill/just-the-docs/issues) in the theme's repository.

## LICENSE

MIT
