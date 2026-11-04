# Psicología de la decisión — skill para Claude y Codex

Te ayuda a probar versiones distintas de un mismo anuncio usando atajos mentales de la decisión (prueba social, anclaje, pérdida, reciprocidad y otros), con un límite ético: nada de urgencia, escasez ni testimonios inventados.

Es una skill: una carpeta con instrucciones que tu agente (Claude o Codex) lee cuando se la pedís. No trae programas ni se conecta a nada, y funciona en la carpeta de cualquier proyecto.

## Cómo instalarla

1. Descargá **[el ZIP](https://github.com/dbarrado/psicologia-de-la-decision/archive/refs/heads/main.zip)** y descomprimilo. Adentro hay una carpeta `psicologia-de-la-decision-main`, y dentro de ella otra carpeta llamada exactamente `psicologia-de-la-decision`: esa es la skill. Si Windows al extraer agrega una carpeta más, usá igual la que se llama `psicologia-de-la-decision` (no la que termina en `-main`).
2. Copiá la carpeta `psicologia-de-la-decision` entera dentro de la carpeta de tu proyecto, en `.claude/skills` si usás Claude, o en `.agents/skills` si usás Codex. Tiene que quedar así: `tu-proyecto/.claude/skills/psicologia-de-la-decision`. Si `.claude`, `.agents` o `skills` no existen, creálas con esos nombres exactos (la que empieza con punto puede estar oculta: en el Explorador de Windows, «Vista» → «Mostrar» → «Elementos ocultos»; en Mac, Cmd + Mayús + punto).
3. Cerrá y abrí una sesión nueva en esa carpeta.

También podés pedirle al agente que la instale por vos:

> Mi objetivo es usar la skill psicologia-de-la-decision en este proyecto. Instalala como skill de este proyecto desde https://github.com/dbarrado/psicologia-de-la-decision y decime dónde quedó.

## Cómo usarla

Pedile, sin nombrar archivos:

> Mi objetivo es probar versiones de un mismo anuncio. Escribí cuatro versiones del título usando prueba social, aversión a la pérdida, anclaje y exceso de opciones. Para cada una decime qué tendría que ser verdad para poder usarla. No uses urgencia ni escasez inventadas y no inventes testimonios.

## Qué no hace

No inventa frases de clientes, cifras ni testimonios, no usa urgencia ni escasez falsas, y no toca ninguna cuenta de anuncios: entrega borradores en la conversación para que los revises vos.

## Autoría y licencia

Strategic IA. Licencia MIT (ver el archivo LICENSE).
