# iDual Scanner – GitHub Pages Seiten (Support / Marketing / Datenschutz)

Dieses Paket enthält fertige Markdown-Seiten für GitHub Pages, die du als:

- **Marketing-URL** (Landing Page)
- **Support-URL**
- **Datenschutz-URL**

in App Store Connect verwenden kannst.

## Inhalt

- `docs/index.md` → Marketing / Landing Page
- `docs/support.md` → Support
- `docs/privacy.md` → Datenschutz

## GitHub Pages aktivieren

1. GitHub → **Settings** → **Pages**
2. **Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/docs`
3. Speichern. Danach zeigt GitHub dir die URL der Seite an.

## App Store Connect Zuordnung

- Marketing-URL: `.../` (zeigt `index.md`)
- Support-URL: `.../support` (oder `.../support.html`)
- Datenschutz-URL: `.../privacy` (oder `.../privacy.html`)

Hinweis: Je nach Pages-Theme/Setup können Endungen variieren. Standardmäßig funktionieren die Seiten auch mit `.html`.
