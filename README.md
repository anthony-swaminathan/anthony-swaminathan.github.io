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
| CV and paper PDFs | `files/` (served at `https://anthony-swaminathan.github.io/files/NAME.pdf`) |
| Headshot | `images/profile.png` |

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
note: 'Job Market Paper'     # optional, shown in italics after the title
paperurl: '/files/new-paper.pdf'   # optional, makes the title a link
---

Abstract goes here (optional; shown as a click-to-expand "Abstract").
```

Section headings for each `category` are set under `publication_category` in `_config.yml`.

### Adding a course

Create a file in `_teaching/` with `type: "instructor"` or `type: "ta"`, plus `title`, `venue`, `date`, `terms`, and optionally `syllabus` and `evaluation`. The text below the front matter becomes the click-to-expand course description.

### Updating the CV

Replace `files/Swaminathan_CV.pdf` with a new file of the same name, then commit and push.
