# Taller FISC: construye agentes de IA con Pydantic AI

**Jueves 24 de septiembre de 2026 · 1:00–3:00 p. m. · Ricardo Tovar**

Este repositorio contiene los recursos para participar en el taller: un Google Colab ejecutable, un brief PDF de cuatro páginas y un resumen de repaso en PDF. Necesitas conocer lo básico de Python, una cuenta Google y una clave propia de Google AI Studio. El uso de la API puede estar sujeto a las cuotas y condiciones de tu cuenta.

## Empieza aquí

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rtovardev/taller-agentes-pydantic-ai-fisc-2026/blob/main/Taller_Agentes_Pydantic_AI_FISC_2026.ipynb)

1. Abre el notebook con el botón de arriba.
2. Guarda tu clave de Google AI Studio en **Colab Secrets** con el nombre `GOOGLE_API_KEY` y activa el acceso del notebook. No pegues la clave en una celda.
3. Ejecuta las celdas en orden. El recorrido dura unos 40 minutos.
4. Descarga el [brief del taller](brief-taller-fisc.pdf) para repasar conceptos, comandos y opciones de proyecto.
5. Conserva el [resumen del taller](resumen.pdf) como mapa breve de conceptos y prácticas.

## Qué aprenderás

- Distinguir agente, tool, MCP, skill y memoria.
- Crear un `Agent`, añadir una herramienta, validar una salida con Pydantic y continuar con historial de mensajes.
- Elegir entre un agente sencillo y un patrón de revisión cuando exista un criterio para medir la mejora.
- Dar a un coding agent un objetivo, límites y casos de aceptación para iniciar un proyecto local.

El notebook es la práctica guiada. Conserva el recorrido principal y añade extensiones opcionales para inspeccionar mensajes, limitar solicitudes, crear un clasificador con una tool local y probarlo con casos normales y ambiguos. También incluye un ejemplo opcional de writer/reviewer. Las explicaciones amplían `BaseModel`, `async/await`, `tool_plain` frente a `tool`, contexto de ejecución, streaming e historial persistido. Los snippets de ampliación están marcados como opcionales.

En el proyecto final puedes construir un extractor de acuerdos, un asistente sobre una guía corta, un clasificador de incidencias o una idea propia. Define entrada, salida, una capacidad útil y un caso difícil. Una ejecución reproducible y la revisión de un caso ambiguo son la meta inicial; una interfaz es opcional.

## Construcción con OpenCode de escritorio

Abre la aplicación y selecciona la carpeta del proyecto. Describe el objetivo, la entrada, el contrato de salida y una herramienta que aporte datos. Pide primero un plan pequeño con Pydantic AI; después revisa la construcción y los resultados.

Ideas: extractor de acuerdos, guía de estudio, clasificador de incidencias o revisor de contenido. La entrega mínima es un agente ejecutable, un caso conocido y otro difícil, con una mejora pendiente. El facilitador acompañará la configuración del entorno durante la práctica. Consulta [OpenCode](https://opencode.ai/docs/) y [Pydantic AI](https://pydantic.dev/docs/ai/overview/).

## Después del taller

Repite el caso que falló, anota el resultado esperado y mejora una sola parte del agente. Consulta la [documentación de Pydantic AI](https://pydantic.dev/docs/ai/overview/), sus [patrones de varios agentes](https://pydantic.dev/docs/ai/guides/multi-agent-applications/) y la [skill oficial para coding agents](https://pydantic.dev/docs/ai/overview/coding-agent-skills/).

## Uso

Puedes descargar, ejecutar y modificar el notebook para tu estudio personal. El brief puede descargarse y consultarse. La republicación, distribución de versiones modificadas y el uso de estos materiales en otra charla o curso requieren autorización expresa de Ricardo Tovar. Lee [AVISO-DE-USO.md](AVISO-DE-USO.md).
