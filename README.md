# [mirrorkey.dev/recipes](https://mirrorkey.dev/recipes)

> A minimal site that hosts recipes for easy access.

I got tired of juggling a small virtual pile of links, pdfs, emails, and paper recipes. This site replaces that: all the recipes that I regularly reference in one place, alterations and attributions included. No more wading through 10 paragraphs of SEO groveling + ad popups that slow the page to a crawl. This site is simple: an alphabetical list of recipes, each containing the necessary ingredients and steps, and at most one image per recipe.

The site itself is built using Hugo with a modified version of the [Tanka](https://github.com/nanxstats/hugo-tanka) theme.

# Development

## Installation

```bash
sudo apt-get install hugo
```

## New recipe
```bash
hugo new posts/recipe-name.md
```

## Hot-reload server
```bash
hugo server -D # includes posts in draft state
```

Pushing to main deploys to github pages.
Remember to remove `draft: true` from content front-matter so that posts will appear in deployed version.

