# Simple One Page Resume

A clean, compact one-page resume template built in LaTeX.

[`resume.pdf`](./resume.pdf) is included in this repo as a rendered example of the template.

## Overview

This template is designed for a modern technical resume that stays readable, ATS-friendly, and easy to customize. The layout keeps everything on a single page with clear section dividers, compact spacing, and simple macros for adding new entries.

## What's Included

- `main.tex` - the full resume template
- `resume.pdf` - example output generated from the template
- `LICENSE` - MIT license

## Template Highlights

- Single-page layout optimized for concise resumes
- Clear sections for `About Me`, `Experience`, `Projects`, `Education`, and `Skills`
- Font Awesome icons for contact details and links
- Reusable LaTeX commands for resume entries and bullet lists
- Works well in Overleaf or a local LaTeX setup

## Getting Started

### Option 1: Use in Overleaf

1. Create a new Overleaf project.
2. Upload `main.tex`.
3. Upload any additional assets if you add them later.
4. Compile the document.
5. Edit the placeholder content with your own experience, projects, education, and skills.

### Option 2: Build Locally

Make sure you have a LaTeX distribution installed, such as TeX Live or MiKTeX.

Compile with:

```bash
pdflatex main.tex
```

If your setup requires multiple passes for links or layout consistency, run it twice.

## Customizing the Resume

Most edits happen directly in [`main.tex`](./main.tex):

- Update the header with your name, email, phone, links, and location
- Replace the About Me summary with a role-targeted introduction
- Fill in Experience and Projects using the existing resume entry macros
- Add your education details
- Tailor the Skills section to the role you are applying for

The template defines helper commands near the top of the file for section entries and bullet formatting, which makes it easy to keep styling consistent as you add or remove content.

## Notes

- The template currently uses `letterpaper`
- Icons are provided through `fontawesome5`
- The layout is tuned for a concise, one-page format, so trimming content is usually better than shrinking font sizes further

## Credit

- This is adapted from https://github.com/harshibar/resume

## License

This project is licensed under the MIT License. See [`LICENSE`](./LICENSE) for details.
