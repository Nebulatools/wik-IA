# WIKIA Interna de LLM's Actualizada (Sept. 9 2025)

Plantilla para consolidar información sobre herramientas de IA.

## OpenAI - ChatGPT

### Modelos disponibles (hoy)
- GPT-5 Thinking (este chat): modo con razonamiento profundo para tareas complejas. En la API existen tamaños `gpt-5`, `gpt-5-mini` y `gpt-5-nano`.
- Serie o (razonamiento): `o3` (y `o3-pro`) y `o4-mini` para pensar más tiempo antes de responder.
- Modelos open-weight de OpenAI (para correrlos/ajustarlos en tu propia infra): `gpt-oss-120b` y `gpt-oss-20b`.
- Nota: la disponibilidad exacta puede variar por plan/entorno; la guía de “Model selection” mantiene el estado más reciente.

### Herramientas integradas aquí contigo
- Web/browsing con citas: busco info actualizada, inserto carruseles de imágenes, tablas de productos, widgets de clima/bolsa/deportes y cito fuentes.
- Python (rápido) y Python visible: cálculos/ETL; y, cuando lo necesitas, tablas/plots/archivos descargables (sin internet, en sandbox).
- Canvas: documento/código en un lienzo lateral para iterar (p. ej., React de una sola página).
- Generación/edición de imágenes: crear o editar imágenes a partir de instrucciones.
- Automatizaciones: recordatorios y chequeos recurrentes (por ejemplo, “avísame cuando salga un modelo nuevo”).
- Lectores de Gmail, Google Calendar y Contacts (solo lectura) para extraer información cuando me lo pidas.
- File search: buscar dentro de archivos que me compartas.
- Shell/Container: tareas de consola en un entorno aislado.
- Memoria (opt-in): puedo “recordar” detalles de trabajo a largo plazo si me lo pides.

### Ecosistema oficial para ampliar capacidades (dev)
- OpenAI Agents SDK (JS/TS y Python): framework ligero para agentes, herramientas y workflows multi‑agente.
- SDKs oficiales:
  - Python (`openai`): cliente sync/async, tipado, ejemplos.
- Quickstarts y ejemplos (apps de referencia).
- Cookbook (recetas de integración y patrones).
- Catálogo/Docs de la plataforma: API, herramientas (función/tool calling, fine‑tuning, etc.).
- Modelos open‑weight (para self‑hosting/custom fine‑tuning): página oficial con enlaces a GitHub/Hugging Face.

### Add‑ons útiles (no oficiales) para coding
- OpenAI Codex — coding agent para VS Code (extensión de Marketplace).
- `vscode-openai` (integración general en el editor).



## Listado Resumido de IA's

OpenAI

```
(web) ChatGPT: https://chatgpt.com/
(cli) Codex: npm install -g @openai/codex
```
