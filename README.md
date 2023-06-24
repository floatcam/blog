# blog
floatcam.ai publications

## How to add a new publication

1. Add a new folder in the publications folder with the following naming convention: `YYYY-MM-DD--<slug>`. For example, `2020-01-01--my-new-publication`.
2. Add a `index.md` file in this folder and fill out the [front matter](#front-matter) and content.
3. Add a featured image named `featured.jpg/png` in this folder.

## Front matter

The front matter of a publication should look like this:

```yaml
---
title: "Paper Title"
date: 2023-06-23
slug: my-new-publication
author: Example Author
duration: 5 minutes read
cover: ./featured.jpg
---
```

## Content

The content of a publication is written in [Markdown](https://www.markdownguide.org/cheat-sheet/).


## Images

Add images to your publication by placing them in your publication folder and referencing them in your publication content with the correct path:

```md
![My helpful screenshot](./screenshot.png)
```

## Submissions

To submit a publication, please open a pull request with your publication added to the `publications` folder. Please make sure that your publication follows the naming convention and includes all the necessary files. Your publication will be reviewed and merged. Once merged, your publication will be live on the website.
