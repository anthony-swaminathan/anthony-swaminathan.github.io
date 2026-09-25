# anthony-swaminathan.github.io

Personal academic website of Anthony Swaminathan, PhD candidate in Economics at Duke University.

Live site: https://anthony-swaminathan.github.io

Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (MIT license) and hosted on GitHub Pages. Every push to `main` rebuilds the site automatically in a few minutes.

## Where things live

| To change... | Edit |
|---|---|
| Home page text | `_pages/about.md` |
| Sidebar (name, photo, email, links) | `author:` section of `_config.yml` |
| Top menu | `_data/navigation.yml` |
| Papers | one file per paper in `_publications/` |
| Courses | one file per course in `_teaching/` |
| CV PDF | Dropbox `CV Documents/Swaminathan CV.pdf` (linked with a `raw=1` Dropbox share link) |
| Paper and syllabus PDFs | Dropbox folder `CV Documents/Public Files` (linked with `raw=1` Dropbox share links) |
| Headshot | `images/profile.png` |
| Styling | "SITE CUSTOMIZATIONS" section at the end of `assets/css/main.scss` |

### Adding a paper

Create a file in `_publications/`, for example `2026-10-01-new-paper.md`:

```markdown
---
title: "Paper Title"
collection: publications
category: working            # published | working | progress
permalink: /publication/new-paper
date: 2026-10-01             # newer dates appear first within a section
coauthors: 'with <a href="https://example.com">Coauthor Name</a>'   # optional
venue: 'Journal Name'        # optional, for published papers
note: 'Job Market Paper'     # optional, shown in parentheses after the title
draft: 'https://www.dropbox.com/...&raw=1'       # optional, adds a [Draft] link
published: 'https://doi.org/...'                 # optional, adds a [Published Paper] link
---

Abstract goes here (optional; shown as a collapsible "Abstract").
```

Section headings for each `category` are set under `publication_category` in `_config.yml`. The paper with `category: jmp` is also featured on the home page, using its `draft` link and abstract.

### Adding a course

Create a file in `_teaching/` with `type: "instructor"` or `type: "ta"`, plus `title`, `venue`, `date`, `terms`, and optionally `syllabus` (URL, shown as a [Syllabus] link) and `evaluation`. The text below the front matter becomes the collapsible course description.

### Updating the CV or a paper

Save the new PDF over the old one (in `CV Documents` for the CV, `CV Documents/Public Files` for papers) with the same file name. Moving or renaming a file within Dropbox also keeps its link working. The Dropbox link, and so the website, picks up the new version automatically.
