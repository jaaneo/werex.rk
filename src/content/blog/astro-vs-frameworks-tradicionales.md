---
title: "Astro vs. frameworks tradicionales: ¿por qué cada vez más devs lo eligen?"
description: "Un vistazo a por qué Astro se ha vuelto popular para sitios de contenido como blogs y landing pages."
pubDate: 2026-06-17
author: "Werex"
tags: ["astro", "frontend", "javascript"]
---

Astro propone un modelo distinto al de frameworks como Next.js o Nuxt: por defecto **no envía JavaScript al cliente**, a menos que tú lo pidas explícitamente con `client:` directives.

## Ventajas principales

1. **Rendimiento por defecto.** HTML estático, sin hidratación innecesaria.
2. **Islas de interactividad.** Puedes mezclar componentes de React, Vue o Svelte solo donde se necesiten.
3. **Content collections.** Manejo de contenido tipado (Markdown/MDX) con validación vía Zod, ideal para blogs como este.

## ¿Cuándo no usarlo?

Si tu aplicación es altamente interactiva de punta a punta (un dashboard complejo, por ejemplo), un framework SPA tradicional puede ajustarse mejor. Pero para blogs, documentación y sitios de marketing, Astro suele ser una excelente opción.
