# LYSI Academy

LYSI Academy is the internal learning platform for LYSI developers and delivery teams.

## Current training

- **EDI & Orderful Integration** — 30 modules across six tracks, module checks, a final exam, and a certificate.

## Adding a future training

1. Add its catalog metadata to the `COURSES` array in `index.html`.
2. Give the course a unique `id`, title, description, status, and view.
3. Keep each course’s progress under a course-specific storage key so existing learner progress remains intact.
4. Register the course view in `go(id)` and give it its own curriculum, exam, and certificate metadata.
5. Change `status` from `soon` to `available` only after the complete course has been tested.

The current EDI progress keys are intentionally unchanged to preserve existing learner data.

## Deployment

GitHub Pages publishes `index.html` from the repository’s `main` branch.

Production URL:

`https://mustaphalysi.github.io/lysi-edi-academy/`

Google OAuth Authorized JavaScript origin:

`https://mustaphalysi.github.io`
