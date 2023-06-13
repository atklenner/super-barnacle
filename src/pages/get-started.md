---
title: Get started
permalink: /get-started/index.html
description: Websites built with this starter
layout: page
preloads:
  href: '/assets/fonts/robotomono/robotomono-variablefont_wght-webfont.woff2'
  as: 'font'
  type: 'font/woff2'
  crossorigin: true
---

- **Important:** edit meta data in `src/_data/meta.js`, it's being used all over the template.
- Have a look at the [blog posts](/blog/), they explain some basic features that aren't covered here.
- Search for 'eleventy-excellent.netlify.app'. You'll find an entry in `src/assets/css/global/global-styles.css`. Replace with your own domain. This is about the external link indicators, they are matched with your domain. If you don't want to use external link indicators, delete the whole style rule (not the whole style sheet!).
- Edit your preferences (colors, fluid text sizes etc.) in `src/assets/design-tokens/*.json`.
- Optional: add your custom (favicon) icons in `src/assets/images/favicon`.
- If you don't want to feature any code examples, you may delete the whole stylesheet for syntax highlighting: `src/assets/css/blocks/code.css`.
- Add and delete your custom block stylesheets in `src/assets/css/blocks/*.css`, they get pulled in your output stylesheet automatically.
