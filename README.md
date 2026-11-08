# LJT-Homepage

Personal homepage of Junteng Liu, built with the [Academic Pages template](https://github.com/academicpages/academicpages.github.io).

## Contents

- **About** (`_pages/about.md`): personal details, academic background, research experience, publications, skills, honors and awards, and contact information.
- **Publications** (`_publications/`): the publication list, which is also recorded in the About section.

Site-wide settings live in `_config.yml`, and the header menu is configured in `_data/navigation.yml`.

## Publishing the site

The site is built by the GitHub Actions workflow in `.github/workflows/jekyll.yml` on every push to `master`.
To publish it on GitHub Pages:

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push a commit (or re-run the "Deploy Academic Pages template site to Pages" workflow from the Actions tab).

The site will then be available at `https://spaldingpitzenur80719.github.io/LJT-Homepage/`.
