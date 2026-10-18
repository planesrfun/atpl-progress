# ATPL Collection Monitor

Public, read-only status dashboard for an offline ATPL study question-collection workflow.

**Live site:** https://planesrfun.github.io/atpl-progress/

The site reads only a generated, sanitized `status.json` containing aggregate counts, group labels, question IDs and ETA/status metadata. It contains no question text, answers, explanations, login credentials or private source repositories. Publication is handled by an independent process on the authenticated collector machine, and updates may take a short time to appear due to GitHub Pages build/cache latency.
