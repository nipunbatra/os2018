# CS 301 · Operating Systems (2018)

Course website for CS 301 Operating Systems at IIT Gandhinagar, Semester I 2018–19, taught by Prof. Nipun Batra:
<https://nipunbatra.github.io/os2018/>

The site is a [Quarto](https://quarto.org) website in the same design as
[ES 667 Deep Learning](https://nipunbatra.github.io/dl-2026/). GitHub Actions
(`.github/workflows/quarto-publish.yml`) renders it into `_site/` and publishes it to GitHub Pages on every push to
`master`.

| File | Contents |
|---|---|
| `index.qmd` | Home: course facts, course record, module overview, questions, references, teaching assistants |
| `schedule.qmd` | Lectures: one row per lecture with slides and class recording |
| `assessment.qmd`, `_dates.qmd` | Grading, every dated event, quizzes, homework and the project |
| `assignments.qmd` | Homework sets and submission rules |
| `labs.qmd`, `labs/*.md` | Lab sheets |
| `resources.qmd`, `feedback.qmd`, `code/index.qmd` | Resources, student feedback, code used in class |
| `lectures/`, `hw/`, `exams/`, `labs/`, `code/` | Slides, homework, quiz papers, lab sheets and code |
| `lectures.qmd`, `projects.qmd`, `*/index.qmd` | Redirects from old URLs |
| `styles.scss`, `course.scss` | Shared theme (`styles.scss` is identical to dl-2026) and small additions |
| `rail.html`, `course-theme.html`, `course-tools.html` | Side rail, light and dark switch, footer, copy-link buttons and date handling |

Preview locally with `quarto preview`.
