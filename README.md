# 🌐 Jorden — Restaurant Online Presence Website

A static website built with **Jekyll** and deployed via **GitHub Pages**. Designed to help restaurants establish a strong online presence with a blog, landing page, and service showcase.

---

## 🚀 Live Demo

🔗 [View Live Site](https://jordanstephen.github.io/jorden)

---

## 📁 Project Structure

```
jorden/
├── _posts/                  # Blog posts (Markdown format)
├── _layouts/                # HTML layout templates
├── _includes/               # Reusable partials (header, footer)
├── public/
│   └── images/              # All images and media files
├── assets/
│   ├── css/                 # Stylesheets
│   └── js/                  # JavaScript files
├── _config.yml              # Jekyll configuration
├── .pages.yml               # Pages CMS config
├── .pagescms.yaml           # Pages CMS extended config
├── index.html               # Homepage
├── blog.html                # Blog listing page
├── robots.txt               # SEO robots file
└── README.md                # This file
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Jekyll | Static site generator |
| GitHub Pages | Free hosting & deployment |
| Pages CMS | Content management |
| HTML/CSS | Frontend |
| Markdown | Blog content |

---

## ⚙️ Local Setup

### Prerequisites
- Ruby (v2.7+)
- Bundler gem

### Steps

```bash
# 1. Clone the repo
git clone https://github.com/jordanstephen/jorden.git
cd jorden

# 2. Install dependencies
bundle install

# 3. Run locally
bundle exec jekyll serve

# 4. Open in browser
# http://localhost:4000
```

---

## ✍️ Adding a New Blog Post

Create a new `.md` file inside `_posts/` with this naming format:

```
_posts/YYYY-MM-DD-your-post-title.md
```

Add this frontmatter at the top:

```yaml
---
layout: post
title: "Your Post Title"
date: 2025-05-14
categories: [restaurant, tips]
---

Your content here...
```

---

## 🌍 Deployment

This project auto-deploys via **GitHub Pages** on every push to the `main` branch.

No manual deployment needed — just push and the site updates within ~60 seconds.

---

## 📬 Contact

Made by [@jordanstephen](https://github.com/jordanstephen)

---

> ⭐ If you find this useful, consider giving the repo a star!
