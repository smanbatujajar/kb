# SMAN 1 Batujajar Knowledge Base

To build this project, run

```bash
npm run build
```

You can run a development server with

```bash
npm run dev
```

This project is made with [VuePress](https://vuepress.vuejs.org/).

## Deployment

This project will be deployed automatically to `gh-pages` branch with [GitHub Actions](https://github.com/features/actions) using [deploy.yml](.github/workflows/deploy.yml).

## Custom domain

Put your custom domain name inside [CNAME](CNAME) file, then [configure your dns server](https://help.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site).

The CNAME file will be copied on deployment to `gh-pages` branch.