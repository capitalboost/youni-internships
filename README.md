# Youni — 20 Internships

Landing page pentru programul **Youni — 20 Internships**: 20 de adolescenți conduc Youni Choice (Student Path SRL) timp de un an, cu un obiectiv de 1.000.000€. Doar 5 locuri deschise publicului larg.

Pagină statică, self-contained (`index.html`), aplicare prin formular HubSpot (modal).

## Deploy (GitHub Pages)
1. Settings → Pages → Source: `main` / root.
2. După ce Pages e activ, actualizează în `index.html` tag-urile `og:url` / `og:image` / `twitter:image` (caută `TODO(deploy)`) cu URL-ul real (ex. `https://capitalboost.github.io/youni-internships/`) și re-validează în Facebook Sharing Debugger.

## Local
Servește pe http (formularul HubSpot nu se randează pe `file://`):
```
python -m http.server 8000
# http://localhost:8000/
```
