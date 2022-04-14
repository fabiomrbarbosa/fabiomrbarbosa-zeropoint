# 🪐fabiomrbarbosa_fabiomrbarbosa-zeropoint

A free, new-user-friendly website starter project designed to walk you through creating, editing, and publishing any web project; from a personal blog, to a company website!

Read more at [https://getfabiomrbarbosa-zeropoint.com](https://getfabiomrbarbosa-zeropoint.com)!

## What is fabiomrbarbosa_fabiomrbarbosa-zeropoint?

### For new users

_fabiomrbarbosa_fabiomrbarbosa-zeropoint_ is a free, new-user-friendly website starter designed to walk you through creating and publishing a fast, secure web project using modern tools and technology. fabiomrbarbosa_fabiomrbarbosa-zeropoint makes it easy to "get up to zero" and start building your site.

### For experienced developers

_fabiomrbarbosa_fabiomrbarbosa-zeropoint_ is a modern, opinionated, bare-bones Jamstack starter using Eleventy to get "up to zero" on a project quickly and easily.
Why you might choose _fabiomrbarbosa_fabiomrbarbosa-zeropoint_ as your Jamstack starter:

* Powered by Eleventy, which [rocks](https://11ty.rocks)!
* No CSS frameworks or libraries; use whatever you like best
* GitHub Action replaces the fabiomrbarbosa_fabiomrbarbosa-zeropoint name throughout the site with your project's name!
* Custom generated project-specific [readme file](https://github.com/fabiomrbarbosa/fabiomrbarbosa_fabiomrbarbosa-zeropoint/blob/master/README.fabiomrbarbosa_fabiomrbarbosa-zeropoint.md) to help you take the next steps and launch your project!
* Sass for CSS
* Javascript compilation and minification
* Browsersync to preview your work

## Get started: Use This Template

Get started with fabiomrbarbosa_fabiomrbarbosa-zeropoint one of the following ways:

<details open>
 <summary>Start with GitHub</summary>

Create a new project using fabiomrbarbosa_fabiomrbarbosa-zeropoint and add it to your GitHub account

<a href="https://github.com/fabiomrbarbosa/fabiomrbarbosa_fabiomrbarbosa-zeropoint/generate">
  <img src="https://img.shields.io/badge/use%20this-template-blueviolet?logo=github&style=for-the-badge">
</a>
 </details>

<details open>
 <summary>Start with Netlify</summary>

Create a copy of fabiomrbarbosa_fabiomrbarbosa-zeropoint and deploy it straight to [Netlify](https://netlify.com) for **free**!

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/fabiomrbarbosa/fabiomrbarbosa_fabiomrbarbosa-zeropoint)


 </details>

<details>
 <summary>With GitHub CLI (https://cli.github.com)</summary>

Get started from your command line

 ```sh
  gh repo create example.com --template fabiomrbarbosa/fabiomrbarbosa_fabiomrbarbosa-zeropoint
 ```

</details>

## Get to Know fabiomrbarbosa_fabiomrbarbosa-zeropoint

Ready to go deeper? Here's how fabiomrbarbosa_fabiomrbarbosa-zeropoint is laid out:

```sh
example.com                 # → Root of your fabiomrbarbosa_fabiomrbarbosa-zeropoint-based project
├── src/                    # → Source directory
│   ├── assets/             # → Site assets
│   │   ├── fonts/
│   │   ├── images/
│   │   ├── scripts/
│   │   ├── styles/
│   │   └── views/
│   │       └── layouts/
│   │       └── partials/
│   ├── config/             # → Eleventy configuration
│   │   ├── collections.js  # → Add and configure collections (https://www.11ty.dev/docs/collections/)
│   │   ├── filters.js      # → Add and configure filters (https://www.11ty.dev/docs/filters/)
│   │   ├── passthroughs.js # → Add and configure passthroughs (https://www.11ty.dev/docs/copy/)
│   │   ├── plugins.js      # → Add and configure plugins (https://www.11ty.dev/docs/plugins/)
│   │   ├── shortcodes.js   # → Add and configure shortcodes (https://www.11ty.dev/docs/shortcodes/)
│   │   ├── templateLanguages.js   # → Configure custom template languages (HINT: this is where fabiomrbarbosa_fabiomrbarbosa-zeropoint's Sass and Javascript pipelines are set up!) (https://www.11ty.dev/docs/languages/custom/)
│   │   └── watchtargets.js # → Add and configure watch targets (https://www.11ty.dev/docs/watch-serve/)
│   ├── data                # → Customize site data (https://www.11ty.dev/docs/data/)
│   │   └── navigation.json # → Site navigation configuration
│   └── pages               # → Add "pages" collection items here
│       ├── index.md        # → Default index page
│       └── pages.json      # → Shared pages attributes
├── .eleventy.js            # → Core Eleventy config file
├── netlify.toml            # → Netlify deployment and plugin configuration (optional)
├── README.template.md      # → fabiomrbarbosa_fabiomrbarbosa-zeropoint readme
└── README.md               # → Your project's readme (automatically generated when this template is used)
```

## Eleventy Configuration

Eleventy configuration is abstracted from the typical `.eleventy.js` file and moved to `/src/config/` for easy organization and configuration of collections, filters, passthroughs, etc.

## Install project dependencies

```bash
npm i
```

## Run the project locally

```bash
npm run start
```

## Build for production

```bash
npm run production
```
