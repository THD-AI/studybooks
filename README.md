# THD AI – course studybooks

Self-contained HTML studybooks for the AIN-B courses, published with GitHub Pages:

**https://thd-ai.github.io/studybooks/**

Each studybook is a single HTML file with all styling and figures embedded, so it
loads once and then reads fine on a phone, offline, or from a local copy.

## Contents

| Semester | Course | Page |
| --- | --- | --- |
| SS26 | Autonomous Robotics | [`ss26/autonomous-robotics/`](ss26/autonomous-robotics/) |
| SS26 | Algorithms & Data Structures | [`ss26/algorithms-and-data-structures/`](ss26/algorithms-and-data-structures/) |
| SS26 | Database Engineering | [`ss26/databases/`](ss26/databases/) |
| SS26 | Operating Systems & Networks | [`ss26/operating-systems-and-networks/`](ss26/operating-systems-and-networks/) |
| SS26 | Generative AI with Transformers I | [`ss26/generative-ai-1/`](ss26/generative-ai-1/) |
| SS26 | Generative AI with Transformers II | [`ss26/generative-ai-2/`](ss26/generative-ai-2/) |
| SS26 | Human Factors & HMI | [`ss26/human-machine-interaction/`](ss26/human-machine-interaction/) |

Courses that have one also ship a condensed `cheatsheet.html` in the same folder.

## Layout

```
index.html              landing page with course navigation
.nojekyll               serve files as-is, no Jekyll processing
ss26/<course>/index.html   the studybook
ss26/<course>/cheatsheet.html
```

Adding a later semester means adding a `ws26/`, `ss27/`, ... folder next to
`ss26/` and a card on the landing page. Nothing else has to change.

## Scope and sources

These are personal study notes written from the lecture material of each course.
They summarise and reorganise that material for revision; they are not official
course documents and are not endorsed by the university or the lecturers.

The underlying lecture slides, exercise sheets and past exam papers are **not**
published in this repository. A few citation links inside the studybooks point at
those PDFs by relative path, so they resolve only in the local course folder, not
on the published site.

## Contribute

Corrections and student-written explanations are welcome. Name the course and semester, explain the correction, and preserve source attribution. Read the [community guide](https://github.com/THD-AI/.github/blob/main/CONTRIBUTING.md), or ask in [Discussions](https://github.com/orgs/THD-AI/discussions).
