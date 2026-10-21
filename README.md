# Boceto Orquestal

Boceteador orquestal que funciona en el navegador, sin instalar nada. Piano roll, pistas ilimitadas, instrumentos sintetizados con Web Audio, mezclador con reverb, detección de acordes y exportación a MIDI y WAV.

## Qué incluye

- Piano roll con lápiz, selección, borrador y mano
- Plantilla de orquesta de 15 pistas y vista de orquesta con todas las pistas apiladas
- Rangos reales por instrumento, velocidad por nota y reguladores de crescendo y diminuendo
- Escalas resaltadas, acordes detectados, cambios de tempo y de compás, marcadores de sección
- Teclado en pantalla y del ordenador para grabar en vivo, metrónomo y cuenta previa
- Importación de MIDI y exportación a MIDI y WAV (dentro de un .zip), más guardado del proyecto en .json
- Guardado automático en el navegador y funcionamiento sin conexión

## Publicar con GitHub Pages

1. En el repositorio, entra a **Settings > Pages**.
2. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
3. Espera uno o dos minutos. La página queda en `https://jjzamo.github.io/boceto-orquestal/`.

## Guardarla en el iPhone

1. Abre la dirección anterior en **Safari**.
2. Toca el botón de compartir y elige **Añadir a pantalla de inicio**.
3. Ábrela desde el ícono: corre a pantalla completa y sigue funcionando sin conexión.

Consejos para el iPhone: sube el volumen y desactiva el modo silencio para oír el audio.

## Uso en el teléfono

- **Arriba:** menú de la obra (título, tempo, compás, tonalidad, cuadrícula, bucle, archivo), pista activa y transporte. El botón ⏮ vuelve al inicio; si está sonando, empieza de nuevo desde ahí.
- **Abajo:** Lápiz, Selección, Borrar, Edición (copiar, transponer, dinámicas, vista) y Ajustes (pista, armonía, pieza).
- **Gestos en el piano roll:**
  - Un dedo dibuja, mueve y alarga notas.
  - Dos dedos desplazan la vista; pellizca para acercar o alejar.
  - Toque largo sobre una nota la agrega a la selección.
  - Doble toque sobre una nota la borra.
- Con notas seleccionadas aparece una barra con -8va, -1, +1, +8va, Duplicar y Borrar.

## Archivos

- `index.html`: toda la aplicación
- `manifest.webmanifest` e `icon-*.png`: datos e íconos de la app web
- `sw.js`: caché para usarla sin conexión
