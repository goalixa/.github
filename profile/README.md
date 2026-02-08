# Goalixa

Goalixa is a fully open-source goal and productivity platform built to help people plan, execute, and measure their work.

## What it includes
- Goals, subgoals, and weekly goals with projects and tasks
- Time tracking per task, calendar view, and weekly reports
- Habits with streaks and summaries
- Daily planning, todos, and reminders

## Architecture
- `Goalixa-app`: Flask app (Python) with PostgreSQL and a 3-layer architecture
- `goalixa-auth`: standalone auth service with JWT, Google OAuth, and Prometheus metrics
- `goalixa-pwa`: installable PWA shell (vanilla JS) that unifies Landing/Auth/App
- `goalixa-landing`: static landing page
- `k8s`: Kubernetes manifests, API gateway, and PostgreSQL

## Tech stack
Python, Flask, PostgreSQL, JWT, OAuth, vanilla JS, PWA, Docker, Kubernetes, Nginx.

## Open-source
Goalixa is fully open source. Contributions, issues, and feedback are welcome.
