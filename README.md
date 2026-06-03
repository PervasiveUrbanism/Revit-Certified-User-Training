# Mossessian Architecture - Revit Training

This repository holds the support material for Mossessian Architecture's in-house Revit training programme.

The training site is published here:

[Open the Revit training website](https://pervasiveurbanism.github.io/Revit-Certified-User-Training/)

## What This Repository Contains

The material is organised as a lightweight course website for office-based Revit learning. It includes:

- The training schedule
- Session pages for each lesson
- Resource links for learners
- Mock test questions for certification-style practice
- Supporting notes and reference material

The current course is structured around short practical sessions, moving from Revit interface basics through modelling, documentation, families, schedules, coordination, and mock review.

## Editing the Training Content

Most course text lives in the `docs/` folder as Markdown files. These are the main files to edit when updating lesson notes, schedules, links, or resources.

Key files:

- `docs/index.md` - homepage text
- `docs/schedule.md` - course schedule
- `docs/resources.md` - learner resources
- `docs/session-*.md` - individual session pages
- `docs/mock-up-1.md` and `docs/mock-up-2.md` - mock tests

## Website Setup

The website is built with MkDocs using the `mkdocs-shadcn` theme.

To preview it locally:

```powershell
pip install -r requirements.txt
mkdocs serve
```

To check the site before publishing:

```powershell
mkdocs build --strict
```

Changes pushed to `main` are deployed to the public GitHub Pages site.
