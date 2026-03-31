---
layout: post
title: Getting Started with This Theme
date: 2025-01-15
author: Your Name
excerpt: A guide to setting up and customizing your refined researcher blog.
---

Welcome! This is a sample blog post to demonstrate how to use this minimal researcher theme.

## Features

This theme is designed for researchers and academics who want:

- **Clean, minimal design** — focuses on your content, not distracting visuals
- **Easy customization** — simple YAML configuration and markdown posts
- **Responsive layout** — works beautifully on desktop, tablet, and mobile
- **Academic styling** — serif typography, generous whitespace, professional appearance
- **Open source** — built with Jekyll, fully customizable, free to use

## Getting Started

### 1. Customize Your Site

Edit `_config.yml` with your information:

```yaml
title: Your Name
author: Your Name
author_image: /assets/images/profile.jpg
contact_links:
  - label: Email
    url: "mailto:you@example.com"
  - label: Twitter
    url: "https://twitter.com/yourhandle"
```

### 2. Add Your Papers

Edit `_data/papers.yml` to list your research papers:

```yaml
- date: 2025-04-01
  title: Your Paper Title
  authors: Your Name, Co-author
  venue: Conference 2025
  links:
    - label: PDF
      url: "https://arxiv.org/pdf/..."
    - label: Code
      url: "https://github.com/..."
```

### 3. Write Blog Posts

Create `.md` files in `_posts/` directory:

```
_posts/2025-01-15-your-post-title.md
```

### 4. Customize Colors & Fonts

Edit `assets/css/main.css` to adjust:

- Color palette (background, text, links)
- Typography (font families, sizes)
- Spacing and layout
- Responsive breakpoints

## Structure

```
my-awesome-site/
├── _config.yml           # Site configuration
├── _data/
│   └── papers.yml        # Your papers data
├── _layouts/
│   ├── default.html      # Base template
│   ├── home.html         # Homepage layout
│   ├── post.html         # Blog post layout
│   └── papers.html       # Papers page layout
├── _posts/               # Blog posts (create this)
├── assets/
│   ├── css/
│   │   └── main.css      # Styles
│   └── images/
│       └── profile.jpg   # Your photo
├── index.md              # Homepage
├── papers.md             # Papers page
├── blog.md               # Blog page
└── Gemfile               # Ruby dependencies
```

## Tips

- **Use underlines for links** in markdown: `[link text](url)`
- **Keep paragraphs focused** — one idea per paragraph
- **Use headings strategically** — h2 for sections, h3 for subsections
- **Add code snippets** with proper syntax highlighting
- **Write in first person** — makes your research personal and authentic

## Next Steps

1. Add your profile photo to `/assets/images/profile.jpg`
2. Update your bio in `index.md`
3. Add your papers to `_data/papers.yml`
4. Write your first blog post in `_posts/`
5. Customize the colors in `assets/css/main.css`
6. Deploy to GitHub Pages or your hosting provider

Happy writing! 📝
