# María Limpieza del Hogar

Landing page with a requirements form, generated from Brotea's
`landing-astro` template.

## Template placeholders (replaced by the new-project skill)
- `Maria Landing Empresa Limpieza` — human-readable project name
- `maria-landing-empresa-limpieza` — kebab-case slug (also the repo name)
- `Maria Landing Empresa Limpieza` — one-sentence idea/description
- `project-slug-placeholder` — same slug, used in machine-validated name
  fields (package.json) where leading underscores are illegal

## Configuration
- `PUBLIC_REQUIREMENTS_ENDPOINT` — URL that receives the form's JSON POST
  (`{project, source, submitted_by, content}` → requirements table).
  Without it the form politely refuses to submit.

## Commands
- `npm install` · `npm run dev` · `npm run build` (output in `dist/`)
