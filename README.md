# ARGES — AI Vision Ecosystem for the Visually Impaired

> Forging Light. Empowering Sight.

## About
ARGES is a five-layer AI vision ecosystem — smart glasses for the visually impaired. This repo contains the **website** (landing page, admin dashboard, and 3D scroll experience).

## Pages
| Page | URL | Description |
|------|-----|-------------|
| **Landing** | `/` | Product showcase with live 3D glasses model (Three.js) |
| **How It Works** | `/3d.html` | Scroll-driven 3D animation showing the 5-step AI pipeline |
| **Admin Dashboard** | `/admin.html` | Control panel for managing users, devices, and system health |

## Tech
- **Three.js** (WebGL) — 3D model rendering with Meshopt compression
- **Spatial UI** — visionOS-style glass panels, parallax depth, 3D tilt
- **Google Fonts** — Bricolage Grotesque, Hanken Grotesk, Instrument Serif, JetBrains Mono
- **No framework** — vanilla HTML/CSS/JS (ready for Next.js port)

## 3D Model
- Source: Meshy AI (Mythic Smart Glasses)
- Compressed: 10.5 MB → 1.1 MB (meshopt + texture resize)
- Format: GLB (glTF binary)

## Deploy
```bash
# Netlify Drop
# Drag this folder to https://app.netlify.com/drop

# OR CLI
netlify deploy --prod --dir=.
```

## License
© 2026 ARGES Team · Thiagarajar Polytechnic College, Salem
