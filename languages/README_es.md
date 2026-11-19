# TabCoffer

Español | [English](../README.md) | [中文](README_zh.md) | [日本語](README_ja.md) | [Deutsch](README_de.md) | [Français](README_fr.md)

Un gestor de sesiones de pestañas local-first. Guarda tus pestañas abiertas como un depósito con nombre y recupéralas con un clic.

> Chrome · Edge · Firefox · Manifest V3 · Local-first · No account · No tracking

---

## Free vs Pro

| Función | Gratis | Pro |
|---------|--------|-----|
| Sesiones guardadas | **3** | 100 |
| Pestañas por sesión | **20** | 200 |
| Guardar / restaurar con un clic | ✅ | ✅ |
| Renombrar, eliminar, ordenar | ✅ | ✅ |
| Exportar JSON | ✅ | ✅ |
| Buscar sesiones y pestañas | — | ✅ |
| Importar JSON (combinar, deduplicar) | — | ✅ |
| Restaurar: omitir duplicados / solo pestañas no abiertas | — | ✅ |

**Guardar, restaurar y exportar sesiones son gratis y están completos en funcionalidad — el único límite es 3 sesiones × 20 pestañas.** Pro sube los límites y añade búsqueda, importación y dos opciones de restauración precisa. La licencia es opcional; el plan gratuito nunca la pide.

---

## How to use

1. Abre las pestañas que quieres mantener juntas.
2. Haz clic en el icono de TabCoffer, escribe un nombre y pulsa **Guardar sesión**.
3. Cierra las pestañas: la sesión sigue en el depósito.
4. Más tarde, abre el popup y elige **Abrir en ventana nueva** o **Añadir a esta ventana**.

---

## Privacy

Las sesiones, títulos, direcciones e iconos permanecen en `chrome.storage.local` de este dispositivo. TabCoffer no lee contenido de páginas ni envía analítica. La única petición de red es la comprobación opcional de licencia al activar Pro, enviada a `api.annmax1983.com` con tu clave de licencia, un ID de instalación aleatorio y metadatos del navegador — nunca con tus sesiones.

---

## Source

> Este repositorio es para presentación del proyecto; el código fuente completo no se publica. Instala desde las tiendas oficiales.

---

## Licence

Get a licence: `https://annmax1983.com/checkout?plugin=tabcoffer`

Activate it: TabCoffer popup → ⚙ → enter the key.

Copyright © 2026 TabCoffer. All rights reserved. Closed source.
