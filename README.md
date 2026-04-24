# Excursion I — 2026 Jeju Conference on Mathematical Finance

Participant information page for the Saturday afternoon excursion.

> 🌐 **Live**: https://*[GitHub username]*.github.io/*[repository name]*/

## 📄 Contents

Single-page HTML with:
- Route overview with interactive map (Leaflet + OSRM)
- Full schedule with stop-by-stop notes
- "Choose Your Pace" guidance (Relax / Light / Full)
- Detailed descriptions of Hallim Park and Hyeopjae Beach
- Dining information (Podo Hotel lunch, Galchi-wang dinner)
- Practical info: what to bring, dietary needs, accessibility, rain backup
- Registration instructions

## 🚀 Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g., `jmf2026-excursion`)
2. Upload all files in this folder to the repository root
3. Go to **Settings → Pages**
4. Under **Source**, choose `Deploy from a branch`
5. Select `main` branch, `/ (root)` folder, and save
6. Your page will be live at `https://[username].github.io/[repo-name]/` within 1–2 minutes

## 📝 Customization

Before publishing, update the following in `index.html`:

- **Contact email**: search for `jmf2026jeju@gmail.com` and replace with the actual organizing committee email
- **Registration deadline**: search for `May 20, 2026` and adjust if needed
- **Bus capacity**: search for `40 registrants` and adjust if needed

## 🔧 Technical Notes

- Static HTML/CSS/JS only — no build step needed
- External dependencies (loaded via CDN at runtime):
  - Google Fonts (Inter typeface)
  - Leaflet.js for the interactive map
  - CartoDB Positron tiles for map imagery
  - OSRM public API for road-based routing
- Works offline except for the map (falls back gracefully with a message)

## 📜 License

Internal conference material. Free to distribute within the conference community.

---

Prepared by the organizing committee · 2026 Jeju Conference on Mathematical Finance
