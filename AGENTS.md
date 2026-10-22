# AGENTS.md

- Plain static site, no framework and no build step. Netlify publishes `public/` (see `netlify.toml`).
- Everything lives in `public/index.html`: inline `<style>`, inline `<script>` (self-assessment test with score 0–27), content in Russian.
- Images are hotlinked from static.tildacdn.com. If they are ever moved locally, put them in `public/img/`.
- Contact CTAs go to WhatsApp (wa.me) and tel: links; there are no forms or backend.
- Keep edits small and in the same inline style; don't introduce a bundler unless asked.
