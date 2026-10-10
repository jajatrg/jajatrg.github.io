# Jacqueline Trang – Portfolio

Personal portfolio (Business Intelligence & Data Analytics), built with
[Jekyll](https://jekyllrb.com/) and the
[Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme, hosted on GitHub Pages.

Live site: https://jajatrg.github.io

## Structure

| Path | Content |
|---|---|
| `_config.yml` | Site settings (title, author, links, theme) |
| `index.md` | Homepage |
| `_pages/` | Projects, Experience, About and 404 pages |
| `_projects/` | One Markdown file per project |
| `_data/navigation.yml` | Top menu |
| `assets/images/` | Images (profile photo, project visuals) |

## Add a project

Create a new file in `_projects/`, for example `_projects/my-project.md`:

```markdown
---
title: "Project title"
excerpt: "One-sentence summary shown in the project list."
order: 6          # position in the list
date: 2026-11-01
---

Project description in Markdown…
```

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
