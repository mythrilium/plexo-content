# Plexo Content

Blog content for [Plexo Labs](https://plexolabs.com) — managed as GitOps.

## Structure

```
posts/
  my-post-slug.mdx      ← Blog post (MDX)
public/
  blog/                  ← Images and assets for posts
```

## Writing a Post

Create a new `.mdx` file in `posts/`:

```mdx
---
title: "Tu título acá"
description: "Descripción para SEO y social cards"
date: 2026-03-07
tags: ["pagos", "mercadopago"]
cover: "/blog/my-image.jpg"
published: true
---

Tu contenido en MDX acá. Podés usar **Markdown** y componentes React.
```

## Publishing

Push to `main` → triggers Vercel rebuild → live on blog.plexolabs.com

## Local Development

This repo is included as a git submodule in the main plexolabs app.
