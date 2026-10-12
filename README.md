# Mehran Keivanimehr — personal website

Source for **https://mehrankeivanimehr.github.io**, built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages. GitHub builds the site automatically whenever the `master` branch changes.

## Where things live

| What | File |
| --- | --- |
| Name, title, email, profile links, Google verification code | `_config.yml` |
| Home page text (bio) | `index.html` |
| News items | `_data/news.yml` |
| Publications | `_data/publications.yml` |
| Projects | `_data/projects.yml` |
| Teaching | `_data/teaching.yml` |
| CV page (education, experience, skills) | `_data/cv.yml` |
| Photo | `assets/img/profile.jpg` and `assets/img/profile.webp` |
| CV PDF | put it in `assets/pdf/` and set `cv_pdf` in `_config.yml` |
| Styles (colors, fonts, layout) | `assets/css/style.css` |

## Common updates

- **Add a news item:** add an entry at the top of `_data/news.yml`.
- **Add a paper:** add an entry to `_data/publications.yml`; set `selected: true` to also show it on the home page.
- **Add a downloadable CV:** upload `assets/pdf/Mehran_Keivanimehr_CV.pdf`, then set `cv_pdf: /assets/pdf/Mehran_Keivanimehr_CV.pdf` in `_config.yml`.

## Preview locally

```bash
gem install jekyll -v 3.10.0 kramdown-parser-gfm webrick
jekyll serve
```

Then open http://localhost:4000.
