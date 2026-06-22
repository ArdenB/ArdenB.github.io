# ardenburrell.com

Personal academic website for Arden Burrell. Built with [Jekyll](https://jekyllrb.com/) using [Beautiful Jekyll](https://github.com/daattali/beautiful-jekyll) (v6) as a remote theme, and hosted on GitHub Pages at [ardenburrell.com](https://ardenburrell.com).

## Editing content

The page content lives in the Markdown files at the repository root:

- `index.md` — home page
- `aboutme.md` — research
- `pubs.md` — publications
- `CV.md` — curriculum vitae

Site-wide settings (navigation bar, social links, colours, theme version) are in `_config.yml`. The theme itself is pulled in remotely via the `remote_theme` setting, so there are no vendored theme files to maintain.

## Local preview

    bundle install
    bundle exec jekyll serve

Then open <http://localhost:4000>.
