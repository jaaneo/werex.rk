---
title: "Tailwind CSS v4: lo nuevo que deberías saber"
description: "Tailwind v4 cambió su motor y la forma de configurar el proyecto. Repasamos los cambios clave."
pubDate: 2026-06-19
author: "Werex"
tags: ["css", "tailwind"]
---

Tailwind CSS v4 trajo un cambio grande: el motor ahora está escrito sobre una nueva arquitectura (Oxide) mucho más rápida, y la configuración pasó de `tailwind.config.js` a directivas dentro del propio CSS.

## Lo más relevante

- **Configuración en CSS.** Ya no necesitas (en la mayoría de los casos) un archivo de configuración JS; basta con `@import "tailwindcss";` y directivas como `@plugin` o `@theme`.
- **Más velocidad.** Builds e incremental rebuilds notablemente más rápidos.
- **Mejor integración con Vite.** El plugin `@tailwindcss/vite` simplifica la integración en proyectos como Astro, Vite o SvelteKit.

Si vienes de Tailwind v3, vale la pena revisar la guía oficial de migración antes de actualizar un proyecto grande.
