# The Kindness Flywheel

A GitHub Pages site exploring why kindness is the competitive advantage in the AI era.

## Setup

### Local Development

1. Install Ruby and Bundler (if not already installed)
2. Clone this repo and navigate to it
3. Install dependencies:
   ```bash
   bundle install
   ```
4. Run Jekyll locally:
   ```bash
   bundle exec jekyll serve
   ```
5. Open http://localhost:4000/kindness-flywheel in your browser

### Publishing

Posts are automatically published when merged to `main`. Jekyll rebuilds the site via GitHub Actions.

## File Structure

```
kindness-flywheel/
├── _posts/              # Blog posts (YYYY-MM-DD-slug.md)
├── _pages/              # Static pages (about, etc.)
├── _config.yml          # Site configuration
├── Gemfile              # Ruby dependencies
├── assets/
│   ├── css/
│   │   └── custom.css   # Color and font customization
│   └── images/          # Images (logo, bio photo, etc.)
└── index.md             # Homepage
```

## Customization

### Colors & Fonts

Edit `assets/css/custom.css` to customize:
- Primary colors
- Secondary colors  
- Font families
- Link colors
- Heading styles

Current customization defaults:
- Primary: Dark blue-gray (#2c3e50)
- Accent: Bright blue (#3498db)
- Secondary: Gold (#f39c12)

### Site Metadata

Edit `_config.yml` to customize:
- Site title, subtitle, description
- Author name and bio
- Social links (LinkedIn, GitHub, etc.)
- Navigation structure
- Footer content

### Logo

Add your logo image to `assets/images/` and reference it in `_config.yml`:
```yaml
logo: "/assets/images/logo.png"
```

## Publishing Posts

Create a new markdown file in `_posts/` with the naming convention `YYYY-MM-DD-slug.md`:

```markdown
---
title: "Post Title"
date: 2026-03-20
excerpt: "Brief excerpt shown in lists"
categories:
  - strategy
  - leadership
tags:
  - keyword1
  - keyword2
---

Your post content here...
```

### Front Matter Options

- `title`: Post title
- `date`: Publication date (YYYY-MM-DD)
- `excerpt`: Short summary for listings
- `categories`: Organizational categories
- `tags`: Searchable keywords
- `author_profile`: Show/hide author info (default: false)
- `read_time`: Show/hide reading time estimate
- `toc`: Show/hide table of contents
- `related`: Show related posts

## Theme

This site uses [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) customized for The Kindness Flywheel.

### Theme Documentation

- [Getting Started](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)
- [Configuration](https://mmistakes.github.io/minimal-mistakes/docs/configuration/)
- [Post Formatting](https://mmistakes.github.io/minimal-mistakes/docs/posts/)

## Deployment

The site auto-deploys to GitHub Pages when you push to `main`. No additional steps needed.

Visit: https://geoffscott.github.io/kindness-flywheel

## Publishing Workflow

When the publishing skill is ready, it will:
1. Create a new markdown file in `_posts/`
2. Add proper front matter (title, date, excerpt, categories, tags)
3. Commit and push to `main`
4. GitHub Pages auto-rebuilds
5. Post appears live on the site

## Questions?

Refer to the [Minimal Mistakes documentation](https://mmistakes.github.io/minimal-mistakes/) for detailed customization options.
