# Recipes

A Jekyll based repo of our favorite recipes.

See it live [here](https://apulverizer.github.io/recipes).

### Running locally

This is a Jekyll build. Make sure you have Jekyll [installed](https://jekyllrb.com/). To install, run this command in the terminal (or iTerm, etc):

```gem install bundler jekyll```

or to check if you've got it installed already:

```jekyll -v```

Clone or download this repo. Navigate to the folder in terminal (or iTerm, etc), and then run:

```jekyll serve```

With default settings, you should be able to view the site locally at `http://localhost:4000`

### Adding a recipe

To add a new recipe all you need to do is add a new markdown file with the appropriate properties:

```
layout: recipe
title:  "<title>"
tags: 
- <tag 1>
- <tag 2>
category: <breakfast, dinner, dessert, topping, ...>

ingredients:
- <ingredient 1>

directions:
- <direction 1>

---

<description of the recipe>
```

You can also reference other recipes as components by adding:

```
components:
- <extact title or other recipe>
```

### Credits

This was based on original work by [clarklab/chowdown](https://github.com/clarklab/chowdown)