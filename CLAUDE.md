# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands

```bash
npm run dev      # Start dev server at localhost:4321
npm run build    # Build production site to ./dist/
npm run preview  # Preview production build locally
```

## Architecture

This is an Astro 5 project using the standard Astro basics template.

**Key directories:**
- `src/pages/` - File-based routing (each .astro file becomes a route)
- `src/layouts/` - Reusable page layouts
- `src/components/` - Astro components
- `src/assets/` - Processed assets (images, SVGs)
- `public/` - Static assets served as-is

**TypeScript:** Uses Astro's strict TypeScript config. Type definitions auto-generated in `.astro/types.d.ts`.
