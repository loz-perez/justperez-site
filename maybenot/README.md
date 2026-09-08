# MaybeNot

La idea ligeramente equivocada pero ligeramente mejor.

Single-file app (un solo `index.html`) que llama directo a la API de xAI (grok-4.6). Sin build, sin frameworks, sin backend. Preguntá cualquier cosa y MaybeNot te responde con una idea que se desvía del consejo obvio hacia algo un poco mejor.

## Funcionalidades

- Voz / persona seleccionable: MaybeNot (clásico), Poeta, Cínico, Entusiasta.
- Historial persistente en `localStorage` (últimos 40 mensajes).
- Compartir respuestas (Web Share API nativa o copia al portapapeles).
- Copiar y regenerar respuestas.
- Configuración de endpoint, API key, modelo y temperatura en un panel.

## Uso

Abrí `index.html` en el navegador, configurá tu API key de xAI en ⚙️ Configuración, y preguntá.

## Notas

- La API key queda guardada solo en tu `localStorage` (o hardcodeada en el default si la compilás así) — no va al servidor.
- Corre en la web en https://justperez.uk/maybenot/