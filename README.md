# Liang Yi — Academic Homepage

Personal academic homepage of Liang Yi, undergraduate student in Artificial Intelligence at USTC.

Website: https://Y1-Liang.github.io

## Local preview

If Ruby/Jekyll dependencies are installed:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open `http://localhost:4000`.

## Main content files

- `_pages/about.md` — homepage
- `_pages/publications.html` — publications
- `_pages/cv.md` — web CV
- `_data/navigation.yml` — top navigation
- `_config.yml` — site/author metadata
- `assets/css/main.scss` — styling

## Optional profile photo

The site currently intentionally has no profile photo rather than showing the template placeholder.
To add one, place a headshot in `images/profile.jpg` and set:

```yaml
author:
  avatar: "profile.jpg"
```

in `_config.yml`.
