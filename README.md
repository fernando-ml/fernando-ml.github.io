# Fernando Martínez-López's website

Personal research website for [fernandoml.me](https://fernandoml.me), hosted on GitHub Pages with Jekyll.

## Local preview

Use Ruby 3.3 and Bundler:

```sh
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Open `http://127.0.0.1:4000`. For a production build, run `bundle exec jekyll build`.

## Updating content

- `_pages/about.md`: homepage, research focus, and internship availability.
- `_pages/ongoingresearch.md`: current research directions and work in progress.
- `_data/profile.yml`: education, experience, skills, and awards, shared by the homepage and CV page.
- `_publications/`: paper details and metadata. Set `selected: true` and `feature_order` to feature an RL paper. Use `publication_year` for the venue year; `date` may record the original manuscript date. Add `paperurl`, `codeurl`, or `demourl` only for verified artifacts. `status: "Submitted manuscript"` separates submitted work from publications.
- `_portfolio/`: project descriptions. `order` controls display order, and `project_type` distinguishes research, applied work, and learning projects.
- `files/Fernando_Martinez_CV.pdf`: current downloadable CV. Replace this file when updating the CV, then synchronize `_data/profile.yml` and the contact email in `_config.yml`.
- `_data/navigation.yml`: main navigation.
- `_layouts/profile.html` and `assets/css/profile.css`: shared layout and responsive styles.

Before publishing, build the site, verify the paper and code links, and check the homepage and CV page on desktop and mobile. Remove the summer 2027 availability message when it is no longer current. Do not publish example credentials, placeholder content, unsupported metrics, or unpublished research results.

## Publishing

The production branch is `master`. Merging an approved change to that branch triggers the repository's GitHub Pages build. Build output (`_site/`) and local dependencies are not committed.

The repository originated from [AcademicPages](https://github.com/academicpages/academicpages.github.io) and [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes); retained theme files keep their original licensing.
