# [Recipes](https://mirrorkey.dev/Recipes)

This site hosts the recipes I use regularly for easy access.

It's built using Hugo with a modified version of the [Tanka](https://github.com/nanxstats/hugo-tanka) theme.

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

