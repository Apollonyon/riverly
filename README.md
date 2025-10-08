# riverly.dev

![Node.js >= 20](https://img.shields.io/badge/node.js-%3E%3D20-brightgreen)
![pnpm >= 9](https://img.shields.io/badge/pnpm-%3E%3D9-blue)

> The source code for my personal blog, live at [riverly.dev](https://riverly.dev).

[**🖥️ Live Site**](https://riverly.dev)

![Preview Image](https://raw.githubusercontent.com/saicaca/resource/main/fuwari/home.png)

## 🌱 About this Project

This repository contains the source code for my personal blog. It's built using [Astro](https://astro.build) and is based on the beautiful [Fuwari theme](https://github.com/saicaca/fuwari) by [saicaca](https://github.com/saicaca).

The site is automatically deployed from this repository to my own server whenever I push a new commit.

## ✨ Features & Tech Stack

- Built with [Astro](https://astro.build) and styled with [Tailwind CSS](https://tailwindcss.com)
- Smooth animations and page transitions via Astro View Transitions
- Light / dark mode support
- Responsive design
- Search functionality with [Pagefind](https://pagefind.app/)
- Markdown extended features (Admonitions, Expressive Code)
- Table of contents for posts
- RSS feed generation

## 🚀 Development Commands

All commands are run from the root of the project in a terminal:

| Command | Action |
|:---|:---|
| `pnpm install` | Installs dependencies |
| `pnpm dev` | Starts local dev server at `localhost:4321` |
| `pnpm build` | Builds the production site to `./dist/` |
| `pnpm preview` | Previews the production build locally |
| `pnpm check` | Runs Astro's diagnostic checks |

## 📝 Writing Posts

Posts are written in Markdown and located in the `src/content/posts/` directory. The frontmatter for each post should follow this format:

```yaml
---
title: My First Blog Post
published: 2025-10-08
description: This is the first post of my new blog.
image: ./cover.jpg # Optional cover image for the post
tags: [Astro, Personal]
category: Tech # Optional category
draft: false # Set to true to hide from the live site
---

Your post content starts here...