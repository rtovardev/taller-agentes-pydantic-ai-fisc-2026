# Taller FISC: construye agentes de IA con Pydantic AI

**Jueves 24 de septiembre de 2026 · 1:00–3:00 p. m. · Ricardo Tovar**

Este repositorio contiene los recursos para participar en el taller: un Google Colab ejecutable y un brief PDF de cuatro páginas. Necesitas conocer lo básico de Python, una cuenta Google y una clave propia de Google AI Studio. El uso de la API puede estar sujeto a las cuotas y condiciones de tu cuenta.

## Empieza aquí

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rtovardev/taller-agentes-pydantic-ai-fisc-2026/blob/main/Taller_Agentes_Pydantic_AI_FISC_2026.ipynb)

1. Abre el notebook con el botón de arriba.
2. Guarda tu clave de Google AI Studio en **Colab Secrets** con el nombre `GOOGLE_API_KEY` y activa el acceso del notebook. No pegues la clave en una celda.
3. Ejecuta las celdas en orden. El recorrido dura unos 40 minutos.
4. Descarga el [brief del taller](brief-taller-fisc.pdf) para repasar conceptos, comandos y opciones de proyecto.

## Qué aprenderás

- Distinguir agente, tool, MCP, skill y memoria.
- Crear un `Agent`, añadir una herramienta, validar una salida con Pydantic y continuar con historial de mensajes.
- Elegir entre un agente sencillo y un patrón de revisión cuando exista un criterio para medir la mejora.
- Dar a un coding agent un objetivo, límites y casos de aceptación para iniciar un proyecto local.

El notebook es la práctica guiada. En la parte final del taller puedes construir un extractor de acuerdos, un asistente sobre una guía corta o un clasificador de incidencias. Una ejecución reproducible y un caso ambiguo son una mejor meta inicial que una interfaz completa.

## Después del taller

Repite el caso que falló, anota el resultado esperado y mejora una sola parte del agente. Consulta la [documentación de Pydantic AI](https://pydantic.dev/docs/ai/overview/), sus [patrones de varios agentes](https://pydantic.dev/docs/ai/guides/multi-agent-applications/) y la [skill oficial para coding agents](https://pydantic.dev/docs/ai/overview/coding-agent-skills/).

## Uso

Puedes descargar, ejecutar y modificar el notebook para tu estudio personal. El brief puede descargarse y consultarse. La republicación, distribución de versiones modificadas y el uso de estos materiales en otra charla o curso requieren autorización expresa de Ricardo Tovar. Lee [AVISO-DE-USO.md](AVISO-DE-USO.md).
