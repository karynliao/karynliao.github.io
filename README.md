# Karyn Liao · Portfolio

Personal portfolio site, built with Jekyll and published with GitHub Pages.

## Editing content (no code)

Sign in at https://app.pagescms.org with GitHub and open this repository. You can edit:

- **Site text & contact**: home intro, photo, About page text, résumé PDF, email
- **Experience**: job list on the About page
- **Projects**: add, edit, reorder case studies, and upload cover images

Saving in Pages CMS commits to the repository, and GitHub Pages republishes the site in about a minute.

## Where things live

| What | File |
| --- | --- |
| Site text, contact | `_data/site.yml` |
| Experience | `_data/experience.yml` |
| Case studies | `_projects/*.md` |
| Images, PDFs | `assets/images/` |
| Design (colors, fonts, layout) | `assets/css/style.css`, `_layouts/`, `_includes/` |

## Run locally

```
gem install jekyll
jekyll serve
```
