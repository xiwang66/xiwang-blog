# Agent Notes

- This repo is a simple static site. The deployable content lives under `public/`.
- Deployment happens through GitHub Actions to Cloudflare Pages on pushes to `main`.
- Prefer direct edits to `public/index.html`, `public/style.css`, and `public/posts/` instead of introducing a framework without a deliberate migration.
- Keep scratch files, Finder artifacts, and local experiments out of Git.
- If a change affects deployment behavior, also review `.github/workflows/deploy.yml`.
