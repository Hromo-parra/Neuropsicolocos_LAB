# Neuropsicolocos LAB

Open Computational Neuroscience Laboratory for AI, Neurophysiology, Scientific Simulation and Teaching.

## Módulo inicial

**Laboratorio interactivo de atención** con interfaz oscura tipo neuro-laboratorio.

### Teorías incluidas

- Broadbent
- Treisman
- Kahneman
- Posner
- Stroop

## Uso docente

Diseñado para clases presenciales o en línea, como apoyo visual para explicar atención selectiva, interferencia cognitiva y control ejecutivo.

## Ejecución local

```bash
npm install
npm run dev
```

## Build y preview

```bash
npm run build
npm run preview
```

## Deploy en GitHub Pages (Vite)

1. Ejecuta `npm run build` para generar `dist/`.
2. Publica el contenido de `dist/` en GitHub Pages (rama `gh-pages` o Pages desde Actions).
3. Esta app ya incluye `base: '/Neuropsicolocos_LAB/'` en `vite.config.ts` para servir correctamente desde Pages.
   - Si cambias el nombre del repositorio, ajusta ese `base`.
