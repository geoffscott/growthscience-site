# Growth Science Site

Executive coaching and advisory services grounded in trust, clarity, and human-centered leadership.

## Site Structure

- **Homepage** (`index.md`) — Main entry point with hero image and service overview
- **About** (`_pages/about.md`) — Background and philosophy
- **Kindness Flywheel** (`_pages/kindness-flywheel.md`) — Content series on culture, strategy, and leadership in the AI era
- **Posts** (`_posts/`) — Articles and thinking pieces
- **Navigation** (`_data/navigation.yml`) — Main menu configuration

## Building Locally

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000` to view the site.

## Theme

Built with [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/)

Customization:
- `_config.yml` — Site configuration
- `_includes/head/custom.html` — Favicon and color variables
- `_includes/footer.html` — Footer with copyright
- `assets/` — Logo, favicon, hero image, and stylesheets

## Publishing

Commit changes and push to `main` branch. GitHub Pages will automatically build and deploy.

## Assets

- `assets/images/logo.svg` — Site logo (dark)
- `assets/images/logo-light.svg` — Alternate logo (light)
- `assets/images/favicon.ico` — Browser tab icon
- `assets/images/hero-image.jpg` — Homepage hero image
