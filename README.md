# Ariel I. Morada Jr. Portfolio Website

This is the source code for the personal portfolio website of Ariel I. Morada Jr., built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.

## Features

- Responsive, modern design using custom layouts and CSS
- Homepage with professional summary, skills, and project highlights
- Section navigation (About, Skills, Experience, Projects) all on the homepage
- Assets for images, audio, and downloadable resume
- Contact form (optional, not linked by default)

## Project Structure

- `_config.yml` — Jekyll configuration (site title, description, navigation, etc.)
- `index.md` — Main homepage (all content and sections are here)
- `_layouts/` — Custom HTML layouts for the site
- `assets/` — Images, audio, CSS, and files (e.g., resume)
- Other markdown files (`about.md`, `projects.md`, `contact.md`) are present but not actively linked or used

## Local Development Setup

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/downloads/) (version 2.5.0 or higher)
- [Bundler](https://bundler.io/) (`gem install bundler`)
- [Jekyll](https://jekyllrb.com/) (`gem install jekyll`)

### Steps

1. **Clone the repository:**
   ```sh
   git clone https://github.com/aimoradajr/aimoradajr.github.io.git
   cd aimoradajr.github.io
   ```
2. **Install dependencies:**
   ```sh
   bundle install
   ```
3. **Serve the site locally:**
   ```sh
   bundle exec jekyll serve
   ```
   The site will be available at `http://localhost:4000` by default.

### Troubleshooting

- If you encounter issues with native gems, ensure you have a working C/C++ compiler (e.g., MSYS2 for Windows).
- For more help, see the [Jekyll documentation](https://jekyllrb.com/docs/).

## Deployment

This site is designed to be deployed automatically via GitHub Pages. Just push changes to the `master` branch.

---

Feel free to fork or adapt for your own portfolio!
