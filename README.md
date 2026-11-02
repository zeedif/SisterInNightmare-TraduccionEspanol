# Sister In Nightmare - Traducción al Español

Traducción al español de *Sister In Nightmare* (RPG Maker MZ). Toma la traducción de Pinypon (Horchata Scans) y la adapta a la versión 1.01 del juego.

## Instalación

Extrae el zip de [Releases](../../releases/latest) en la carpeta del juego, donde está `Game.exe`, reemplazando los archivos existentes.

## Historial

1. **Estado base**: archivos originales (japonés, v1.01) que toca la traducción.
2. **Traducción de Horchata Scans v1.0**: el parche tal cual, con el formato alineado al del editor para que el diff muestre solo lo traducido.
3. **Ajustes a la v1.01**: la traducción se hizo sobre la v1.0 y pisaba tres eventos comunes que la v1.01 cambió.
   - `data/CommonEvents.json`: eventos comunes 53, 58 y 103 con la lógica de la v1.01. No tienen texto.
   - `data/System.json`: el título de la ventana indica 1.01 y se traducen los términos del sistema que seguían en japonés.
   - `js/plugins.js`: se traducen dos textos de plugin que seguían en japonés (aviso de guardado y efectos de filtro).

## Agradecimientos

- **Traducción:** [Pinypon](https://tradusquare.es/proyectos/sister-in-nightmare-cinco-noches-en-el-convento-18/) (Horchata Scans, TraduSquare), hecha con Translator++.
- **Juego:** Now, en [itch.io](https://kuga-517.itch.io/sister-in-nightmare) y [DLsite](https://www.dlsite.com/maniax/work/=/product_id/RJ01673017.html).
