# Liang Yi — Academic Homepage

Source for [Y1-Liang.github.io](https://Y1-Liang.github.io), the academic homepage of Liang Yi, an undergraduate researcher in Artificial Intelligence at USTC.

## Local preview

If Ruby/Jekyll dependencies are installed:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open `http://localhost:4000`.

## Content map

- `_pages/about.md` — introduction, research interests, news, and selected work
- `_pages/publications.html` — full publication list
- `_pages/cv.md` — web CV
- `_data/navigation.yml` — top navigation
- `_config.yml` — site/author metadata
- `assets/css/main.scss` — styling

## Profile photo

The site intentionally uses a monogram until a real profile photo is available.
To add one, place a headshot in `images/profile.jpg` and set:

```yaml
author:
  avatar: "profile.jpg"
```

in `_config.yml`.
