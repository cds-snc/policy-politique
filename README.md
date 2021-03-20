# Policy team website repository

<https://cds-snc.github.io/policy-politique/>

This repository serves as a public archive of past work undertaken by the CDS Policy Team. Learn more on the [repository home page](https://cds-snc.github.io/policy-politique/en/).

This website is powered by [Hugo](https://gohugo.io/) running in [multilingual mode](https://gohugo.io/content-management/multilingual/). It’s hosted by GitHub Pages using the [`gh-pages`](https://github.com/tschaub/gh-pages) package. The visual design is adapted from the CFPB’s [DOCter Jekyll theme](https://github.com/cfpb/DOCter).

## Running the repo locally

### First run

1. Install Hugo using the [instructions on the Hugo website](https://gohugo.io/getting-started/installing/) for your operating system.
2. Install npm if not already installed, using the [nodejs instructions here](https://nodejs.org/en/download/).
3. Clone the repository to your computer.
3. Use npm to install the gh-pages package, by running `npm install` inside the repository folder.

### Local development

To preview changes to the website locally, run:

```
hugo server --disableFastRender
```

Then open the local site at [`http://localhost:1313/policy-politique/`](http://localhost:1313/policy-politique/). \
(Note that localhost without the `policy-politique` subfolder path will return a 404 error.)

To push new changes to the deployed GitHub Pages site, run:

```
npm run deploy
```
