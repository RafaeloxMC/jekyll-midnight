---
layout: post
title: "Installing the Jekyll Midnight Theme"
date: 2025-06-20 14:30:00 +0000
author: "Jekyll Midnight"
tags: [jekyll, midnight-theme, installation, setup]
excerpt: "Step-by-step guide to installing and configuring the Jekyll Midnight theme for your Jekyll site."
---

# Installing the Jekyll Midnight Theme

This guide will walk you through installing and setting up the Jekyll Midnight theme for your Jekyll site.

## Prerequisites

Before installing the theme, make sure you have:

1. **Ruby** installed (version 2.7 or higher)
2. **Jekyll** and **Bundler** gems installed
3. A basic understanding of Jekyll

If you need to install Jekyll first:

```bash
gem install jekyll bundler
```

## Installation Methods

### Method 1: Fork or Download

1. Fork this repository or download the source code
2. Navigate to the theme directory
3. Install dependencies:

```bash
bundle install
```

4. Serve the site locally:

```bash
bundle exec jekyll serve
```

### Method 2: Use as a Jekyll Theme

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-midnight-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-midnight-theme
```

Then execute:

```bash
bundle install
bundle exec jekyll serve
```

## Configuration

### Basic \_config.yml Setup

Update your `_config.yml` file with the following basic configuration:

```yaml
title: Your Site Title
description: Your site description
url: "https://yourusername.github.io"
baseurl: ""

# Build settings
markdown: kramdown
highlighter: rouge
permalink: /:year/:month/:day/:title/

# Theme settings
theme: jekyll-midnight-theme

# Navigation
navigation:
    - title: Home
      url: /
    - title: Blog
      url: /blog/
    - title: About
      url: /about/
```

## Customizing the Theme

The theme includes several customizable components:

-   **Colors**: Modify `_sass/base.scss` for color schemes
-   **Typography**: Adjust fonts in the same file
-   **Layout**: Edit files in `_layouts/` directory
-   **Navigation**: Update `_includes/navbar.html`

## Next Steps

Once installed, you can:

1. Create new posts in the `_posts` directory
2. Customize the navigation menu
3. Add your own pages
4. Modify the styling to match your preferences

Your Jekyll Midnight theme is now ready to use!
