# Revit Certified User Training

A structured Revit Certified User training programme with lesson plans, exercises, BIM workflows, and certification preparation materials.

## Documentation Site

This repository uses MkDocs with the `mkdocs-shadcn` theme for the in-house Revit user training support site.

Local preview:

```powershell
pip install -r requirements.txt
mkdocs serve
```

Build:

```powershell
mkdocs build --strict
```

The GitHub Actions workflow in `.github/workflows/pages.yml` builds and deploys the MkDocs site to GitHub Pages when changes are pushed to `main`.

## Lesson Structure

- `mkdocs.yml` configures the documentation site.
- `docs/` contains the support site pages.
- `docs/schedule.md` is the editable course schedule.
- `lessons/` contains the lesson content.
- `templates/lesson-template.md` is the starting point for each new lesson.
- `assets/` can hold screenshots, diagrams, sample images, and supporting media.

## Suggested Learning Path

1. Revit interface and navigation
2. Project setup and templates
3. Levels and grids
4. Walls, doors, windows, and basic modeling
5. Floors, ceilings, roofs, and stairs
6. Views, sheets, annotations, and dimensions
7. Families and parameters
8. Schedules and quantities
9. Collaboration, worksharing, and model coordination
10. Exporting, documentation, and presentation

## Adding a Lesson

1. Copy `templates/lesson-template.md`.
2. Save it in `lessons/` with a clear number and title, for example `02-levels-and-grids.md`.
3. Add screenshots or support files to `assets/`.
4. Commit the new lesson to Git.

## Notes

Large Revit project files are ignored by default because they can make a Git repository heavy. If you want to include sample `.rvt` or `.rfa` files later, consider using Git LFS.
