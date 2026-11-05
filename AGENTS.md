# Agent rules for stefan-taferner.github.io

## Never publish
- Phone number, home address, personal email
- Grades, GPA, test scores (GMAT, TOEFL, HSK numeric scores), salary, visa status, date of birth
- Anything in `private/`: keep it in `.gitignore` and never commit or upload it
- Do not invent facts. Everything on the site must trace to the CV or to files Stefan provided for content

## Ask me first
- Before any `git push` or any change on GitHub (create repo, Pages settings, force push, rename)
- Before deleting or overwriting a file
- Before linking `cv.pdf` from the live page (the PDF may still contain phone, email, GPA, or scores)
- Before adding a contact email to the page

## Style
- Plain HTML and CSS, clean and minimal
- Columbia blue accent (`#B9D9EB`), darker navy for text and contrast (`#1D4F91`, `#002B5C`)
- Streamlined sticky top navigation with in-page anchors
- Professional but approachable, with a light Austria touch (Alpine line, Vienna context from the CV)
- Portfolio, if added later, as a gallery page that links to each project
- Writing: humanized and natural. No em dashes or en dashes in visible text (use colons, commas, or periods). No semicolons. Bullets never end with a period
- Self-contained site. No JS frameworks. Minimal JS only if needed

## When you finish
- Tell me what you changed and what you skipped
- List every file that would be pushed, excluding `private/`
- Flag any personal data still inside `cv.pdf` so I can decide whether to link it or supply a redacted copy
