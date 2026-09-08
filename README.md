# nikhilsharma-OM.github.io

Nikhil Sharma's academic job-market website, built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and hosted on GitHub Pages.

## Editing the site

All content lives in Markdown/YAML files — no local build tools are required, GitHub Pages builds the site automatically on every push to `main`.

* `_config.yml` — site title, sidebar bio, contact/social links
* `_pages/about.md` — homepage (bio + featured job market paper)
* `_pages/cv.md` — CV page
* `_publications/` — one file per paper (job market paper, under review, working papers)
* `_talks/` — one file per conference presentation
* `_teaching/` — teaching experience entries
* `files/CV_Nikhil_Sharma.pdf` — the CV PDF linked from the CV page
* `images/profile.png` — headshot

To update a paper's status or add a new talk, edit or add a Markdown file in the relevant folder and push — the live site updates within a minute or two.

## Local preview (optional)

```
bundle install
bundle exec jekyll serve -l -H localhost
```

Requires Ruby + Bundler installed locally. Not required to publish — GitHub Pages builds the site for you.
