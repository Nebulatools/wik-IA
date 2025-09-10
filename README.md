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

## Microsoft - Copilot

Modelos disponibles
Estos son los modelos que Copilot pone hoy a tu alcance:

gpt-4: modelo premium de última generación, optimizado para comprensión de contexto extenso y generación de código complejo. Requiere suscripción Copilot Pro o empresarial y consume solicitudes a mayor velocidad que el modelo base.

gpt-3.5-turbo: modelo base gratuito para chat y completado de código; ofrece buena velocidad y precisión en tareas generales. Cuando agotas tu cuota premium, Copilot retrocede automáticamente a este modelo para que no interrumpas tu flujo.

Copilot está preparando próximamente variantes especializadas (por ejemplo, GPT-4o y GPT-4o-code) con contextos ampliados y capacidades multimodales.

Herramientas y extensiones
Estas integraciones y plugins potencian la sinergia con los modelos de Copilot:

Extensiones de Copilot para GitHub Marketplace

Integran herramientas de tu stack (Sentry, Jira, Datadog, AWS…) directamente en Copilot Chat.

SDK y CLI propios para crear, probar y depurar tu propia extensión usando su API (github.com/features/copilot/extensions)3.

Plugins oficiales de IDE

VS Code, Visual Studio, JetBrains (IntelliJ, PyCharm…), Vim/Neovim, Xcode, GitHub.com y GitHub Mobile.

Añaden completado de código, Copilot Chat y panel de historial sin salir de tu entorno de desarrollo.

Copilot CLI

Cliente de línea de comandos (community-driven) que invoca Copilot Chat o sugerencias de código desde tu terminal.

Repositorio: github.com/microsoft/copilot-cli..

Azure OpenAI VS Code Extension

Conecta tu suscripción de Azure OpenAI para llamar a GPT-3.5, GPT-4 y otros modelos directamente en VS Code.

Ideal si combinas APIs propias con sugerencias contextuales de Copilot.

Copilot Labs (experimental)

Funciones tempranas como explicación de fragmentos de código, tests automáticos y refactorizaciones sugeridas.

Repositorios de ejemplo y snippets

Ejemplos de Copilot Extensions: github.com/github-copilot/extensions (casos de uso, plantillas, flujos de trabajo).

Packs de snippets y atajos en VS Code para invocar comandos de Copilot con teclas rápidas.

Más allá de lo básico
Además de lo anterior, podrías explorar:

Ajustes finos con parámetros de temperatura, top_p o max_tokens para controlar creatividad y longitud.

Herramientas de monitoreo de uso y calidad de sugerencias dentro de Visual Studio (badges y paneles de consumo de solicitudes).

Próximas extensiones de Copilot orientadas a visión por computadora y audio.

## X.AI - Grok

Modelos Disponibles
Utilicé una tabla para compararlos de manera clara:

ModeloDescripción PrincipalContexto Máximo (Tokens)Modalidades/Funciones PrincipalesAcceso DisponibleGrok 4 (incluyendo Grok 4-0709 y Grok 4 Heavy)El modelo más inteligente del mundo, con uso nativo de herramientas, búsqueda en tiempo real y razonamiento avanzado. Grok 4 Heavy es una versión más potente con sistema multi-agente para tareas complejas.256,000Razonamiento, llamadas a funciones, salidas estructuradas, búsqueda en tiempo real, voces hiperrealistas, procesamiento de PDFs grandes.Gratuito para todos los usuarios en modo "Auto" o "Expert" en grok.com, apps de iOS/Android, y X (anteriormente Twitter). Disponible vía API para desarrolladores. Grok 4 Heavy solo en el plan SuperGrok Heavy (suscripción paga). Acceso premium para suscriptores SuperGrok y Premium+ en X.Grok 3Modelo de lenguaje general con capacidades de razonamiento.131,072Procesamiento de texto, razonamiento general.Gratuito con cuotas limitadas en grok.com, apps de iOS/Android y X. Acceso ilimitado en planes pagos como SuperGrok. Disponible vía API. Modo de voz en apps móviles.Grok 3 MiniVersión ligera y eficiente de Grok 3 para tareas generales.131,072Procesamiento de texto básico.Similar a Grok 3: gratuito con límites, o ilimitado en planes pagos. Disponible vía API.Grok Code Fast 1Modelo rápido y económico especializado en codificación agentic (autónoma). Excelente para tareas de programación full-stack en lenguajes como TypeScript, Python, Java, Rust, C++ y Go.256,000Codificación agentic, llamadas a funciones, salidas estructuradas, razonamiento rápido y de bajo costo.Disponible vía API (precios: $0.20 / 1M tokens de entrada, $1.50 / 1M de salida, $0.02 / 1M cacheados). Integrado temporalmente de forma gratuita en plataformas como GitHub Copilot, Cursor, Cline, opencode, Windsurf, Roo Code y Kilo Code.Grok 2 Image 1212Modelo especializado en generación de imágenes.No especificadoGeneración de imágenes a partir de texto o inputs multimodales.Disponible vía API (precios por imagen generada). Integrado en Grok para usuarios en grok.com y apps.Grok for GovernmentSuite de productos de IA de frontera adaptados para clientes del gobierno de EE.UU.Varía por modeloRazonamiento avanzado, adaptado para usos gubernamentales.Exclusivo para agencias del gobierno de EE.UU. (disponible vía contrato con el Departamento de Defensa o programación GSA). No público.Grok-1Modelo base anterior, liberado como open-source para experimentación.No especificado (versión inicial)Carga y ejecución de pesos del modelo para investigación.Descargable gratuitamente desde GitHub (repositorio oficial). No es un modelo en vivo, sino pesos y código para ejecución local.

Notas generales sobre modelos:

Todos los modelos tienen un corte de conocimiento hasta noviembre de 2024 (excepto actualizaciones en tiempo real vía búsqueda).
Acceso principal: En grok.com, apps de Grok/X para iOS/Android, y X.com. Grok 4 es ahora gratuito globalmente con límites generosos temporales.
Suscripciones: SuperGrok (para grok.com) ofrece cuotas más altas y acceso a versiones premium como Grok 4 Heavy. Para precios, visita https://x.ai/grok. Para Premium+ en X, consulta https://help.x.com/en/using-x/x-premium.
Actualizaciones: xAI lanza versiones con aliases como "-latest" para actualizaciones automáticas o fechas específicas (ej: Grok 4-0709 para la versión de julio 2025).

Tools o Extensiones para Expandir y Sinergizar con los Modelos
xAI no ofrece una amplia gama de plugins o herramientas CLI propietarias más allá de su API principal, pero hay integraciones y recursos que mejoran la sinergia con los modelos. Estos ayudan a desarrolladores a integrar Grok en apps, codificación y más. No invento información; me baso en datos oficiales.

xAI API:

La principal herramienta para integrar cualquier modelo Grok en aplicaciones personalizadas. Soporta llamadas a funciones, salidas estructuradas, caching de prompts para reducir costos, y multimodalidad (texto + imágenes).
Sinergia: Permite construir apps, bots o agentes con Grok. Por ejemplo, integra con plataformas de codificación para autocompletado o generación de código.
Acceso: Crea una clave en https://console.x.ai/. Documentación detallada en https://docs.x.ai/ (incluye guías como "Grok Code Prompt Engineering" para optimizar prompts en codificación).
Precios: Varían por modelo (ej: Grok Code Fast 1 es económico). Límites de tasa por defecto aumentados recientemente debido a la demanda. No hay detalles específicos de precios aquí; consulta el sitio para tu cuenta.


Integraciones con Plataformas de Codificación:

Grok Code Fast 1 se integra directamente con herramientas como GitHub Copilot, Cursor, Cline, opencode, Windsurf, Roo Code y Kilo Code. Esto permite usar Grok para codificación agentic en entornos de desarrollo reales (ej: autocompletado, depuración).
Sinergia: Expande Grok a flujos de trabajo de programación, haciendo "sinergia" con editores de código. Inicialmente gratuito por tiempo limitado en estas plataformas.


Repositorios en GitHub:

grok-1: Repositorio oficial con código JAX para cargar y ejecutar los pesos open-source de Grok-1. Incluye ejemplos para experimentación local.

Sinergia: Útil para investigadores o devs que quieran modificar o entrenar sobre un modelo base. No es para producción, pero expande el ecosistema open-source.


Otros repos: xAI comparte tweaks y transparencias en GitHub (ej: ajustes a prompts de Grok 4), pero no hay repos adicionales oficiales para herramientas CLI o addons. Puedes forkear grok-1 para proyectos personalizados.


Otras Extensiones y Sinergias:

Documentación para Desarrolladores: En https://docs.x.ai/, incluye guías para integración API, manejo de tokens y mejores prácticas. Útil para addons en coding (ej: prompts optimizados para Grok Code).
Asociaciones: Colaboraciones como con Kalshi (para mercados de predicción) o Oracle Cloud Infrastructure (para hosting de modelos en la nube). Grok se integra con búsquedas avanzadas en X.
Funciones Internas en Apps: En las apps de Grok, hay herramientas como procesamiento de PDFs (explicar/quote secciones), generación de imágenes y voz multimodal. No son "plugins" externos, pero expanden el uso.
No hay CLI Oficial: No se menciona ninguna herramienta CLI propietaria. Puedes usar la API con librerías como Python's requests o SDKs de terceros para scripts CLI personalizados.
Addons para Coding: A través de las integraciones mencionadas (ej: GitHub Copilot), actúa como addon en VS Code u otros IDEs. No hay plugins adicionales de xAI.




## Listado Resumido de IA's

OpenAI

```
(web) ChatGPT: https://chatgpt.com/
(cli) Codex: npm install -g @openai/codex
```

Microsoft

```
(web) Copilot: https://copilot.microsoft.com/
(cli) Github Copilot: npm install -g @githubnext/github-copilot-cli
```

X.AI

```
(web) Grok: https://grok.com/
(cli) ...
```

