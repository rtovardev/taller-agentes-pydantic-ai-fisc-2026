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

El notebook es la práctica guiada. Conserva el recorrido principal y añade extensiones opcionales para inspeccionar mensajes, limitar solicitudes, crear un clasificador con una tool local y probarlo con casos normales y ambiguos. También incluye un ejemplo opcional de writer/reviewer.

En el proyecto final puedes construir un extractor de acuerdos, un asistente sobre una guía corta, un clasificador de incidencias o una idea propia. Define entrada, salida, una capacidad útil y un caso difícil. Una ejecución reproducible y la revisión de un caso ambiguo son la meta inicial; una interfaz es opcional. El ejemplo de MART que se conversa durante la charla es un caso de diseño ficticio, no una demo funcional incluida aquí.

## Proyecto local con OpenCode

El Colab termina con una ruta para continuar desde tu computadora. Necesitas Node.js/npm, Python y uv. Instala Node.js/npm y uv con sus guías oficiales antes de empezar:

```sh
npm install -g opencode-ai
uv init mi-agente
cd mi-agente
uv add pydantic-ai
npx skills add pydantic/skills
opencode
```

Al instalar skills, selecciona Pydantic AI, OpenCode y el alcance del proyecto. En OpenCode elige en `/models` una opción marcada como Free disponible en tu sesión, usa `/init` y revisa el `AGENTS.md` generado. Las opciones gratuitas dependen de la sesión y pueden cambiar. La clave del proveedor para ejecutar tu programa Python se configura por separado. Consulta la [guía oficial de OpenCode](https://opencode.ai/docs/), la [instalación de uv](https://docs.astral.sh/uv/getting-started/installation/) y las [skills de Pydantic AI](https://pydantic.dev/docs/ai/overview/coding-agent-skills/).

## Después del taller

Repite el caso que falló, anota el resultado esperado y mejora una sola parte del agente. Consulta la [documentación de Pydantic AI](https://pydantic.dev/docs/ai/overview/), sus [patrones de varios agentes](https://pydantic.dev/docs/ai/guides/multi-agent-applications/) y la [skill oficial para coding agents](https://pydantic.dev/docs/ai/overview/coding-agent-skills/).

## Uso

Puedes descargar, ejecutar y modificar el notebook para tu estudio personal. El brief puede descargarse y consultarse. La republicación, distribución de versiones modificadas y el uso de estos materiales en otra charla o curso requieren autorización expresa de Ricardo Tovar. Lee [AVISO-DE-USO.md](AVISO-DE-USO.md).
