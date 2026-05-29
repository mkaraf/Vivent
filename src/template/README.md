# SanaDenta — Astro + Tailwind v4

Landing page převedená z TanStack Start do Astro.

## Instalace do existujícího projektu

1. Ujisti se, že máš nainstalovaný Tailwind CSS v4 přes oficiální Astro integraci:
   ```bash
   npx astro add tailwind
   ```
   (vybere `@tailwindcss/vite` plugin pro v4)

2. Zkopíruj obsah těchto složek do svého projektu:
   - `src/pages/index.astro`
   - `src/layouts/Layout.astro`
   - `src/components/Header.astro`
   - `src/components/Hero.astro`
   - `src/styles/global.css`
   - `src/assets/hero-family.jpg`
   - `src/assets/logo-tooth.png`

3. V `src/pages/index.astro` (a `Layout.astro`) je naimportováno `../styles/global.css`.

4. Fonty (Cormorant Garamond + Inter) se načítají z Google Fonts v `<head>` v `Layout.astro`.

5. Ikony jsou inline SVG (žádná závislost na `lucide-react`).

## Spuštění
```bash
npm run dev
```
