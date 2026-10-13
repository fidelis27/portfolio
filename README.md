# Thiago Fidelis — Portfolio

Personal portfolio of Thiago Fidelis, Senior Front-end Engineer (React, TypeScript, micro frontends).

- LinkedIn: https://www.linkedin.com/in/fidelis27/
- GitHub: https://github.com/fidelis27

## About this site

A single static page, `index.html`, with inline CSS and JavaScript. There is no build step and no dependencies.

- Bilingual content (English and Portuguese), switched client-side through `data-i18n` keys.
- Sections: hero, about, experience timeline, projects with case-study modals, AI-assisted engineering, recommendations (linked to LinkedIn), contact.

## Run locally

```bash
# any static server works
python3 -m http.server 8080
# then open http://localhost:8080
```

## Editing content

- Visible text lives in the HTML and in the translation dictionary near the end of `index.html`. Change both when you edit a string, otherwise the language toggle will overwrite it.
- Keep claims verifiable. Metrics are only added when they can be backed up.

## Related projects

- [`mfe-communication`](https://github.com/fidelis27/mfe-communication): micro-frontend platform with Module Federation and a versioned domain-event contract.
- [`secretaria-backend`](https://github.com/fidelis27/secretaria-backend): Go hexagonal API with OIDC authentication and scoped authorization.
