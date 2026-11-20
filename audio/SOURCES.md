# Créditos de audio

Los archivos se sirven desde esta carpeta; la página no depende de servicios de audio externos.

## Efectos de interfaz y de juego

Tomados de la carpeta de Google Drive **«efectos de sonido Arq multi»** del equipo. Cada archivo publicado es un fragmento recortado, con fundido de salida y volumen igualado; los originales siguen en Drive.

| Archivo | Uso | Original en Drive |
|---|---|---|
| `ui-click.mp3` | Clic en botones | Efectos UI / Click / dragon-studio-mouse-click-sfx-444806 |
| `ui-nav.mp3` | Clic en enlaces | Efectos UI / Click / photos-click-409642 |
| `ui-date.mp3` | Cambio de fecha | Transiciones / freesound_community-whoosh-click01-92153 |
| `ui-timeline.mp3` | Avance de la línea del tiempo | Efectos UI / juniorsoundays-ui-sound-70-527837 |
| `ui-open.mp3` | Abrir secciones desplegables | Transiciones / whoosh Johan 2 |
| `ui-info.mp3` | Paneles informativos | Efectos UI / u_3ay6aijdt2-bell1-445873 |
| `ui-map.mp3` | Iniciar recorridos y pruebas | Transiciones / whoosh Johan |
| `ui-adventure.mp3` | Abrir un mundo o empezar partida | Transiciones / dragon-studio-cinematic-flashback-transition-463199 |
| `game-gain.mp3` | Acierto, captura limpia | Efectos UI / Correcto y error / correcto 4 |
| `game-combo.mp3` | Sube la racha | Efectos UI / Correcto y error / dragon-studio-game-show-correct-tick-sound-416167 |
| `game-loss.mp3` | Error, racha perdida | Efectos UI / Correcto y error / error |
| `game-warn.mp3` | Recurso escaso, últimos segundos | Efectos juego / Alarmas / freesound_community-alarm-26718 |
| `game-alarm.mp3` | Apagón e incendios | Efectos juego / Alarmas / dennish18-biohazard-alarm-143105 |
| `game-win.mp3` | Puente completado | Efectos UI / Victory / victory retro |
| `game-victory.mp3` | Resultado final | Efectos UI / Victory / real victory |
| `game-carbon.mp3` | Atrapar carbón (Mantén la red) | Efectos juego / Calentamiento global y trash / spinopel-portable-diesel-generator-381912 |
| `game-gas.mp3` | Atrapar gas (Mantén la red) | Efectos juego / Calentamiento global y trash / freesound_community-gas-pump-29700 |
| `game-launch.mp3` | Lanzar carga en tren, barco o avión | Efectos juego / Calentamiento global y trash / freesound_community-big-motor-90117 |
| `game-launch-road.mp3` | Lanzar carga por carretera | Efectos juego / Calentamiento global y trash / spinopel-petrol-scooter-393079 |

Los nombres con formato `autor-titulo-número` corresponden al formato de descarga de Pixabay; confirma en cada página su licencia antes de publicar. Los archivos renombrados por el equipo (correcto, error, victory, whoosh Johan) necesitan la misma comprobación.

## Ambientes

- `ambience-wind-birds.ogg` — “Gentle breeze and birds singing”, ezwa. Dominio público mundial. [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Gentle_breeze_and_birds_singing.ogg)
- `ambience-city.ogg` — “Sunday in the city street noise3”, cori. Dominio público mundial. [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Sunday_in_the_city_street_noise3.ogg)
- `ambience-industrial.mp3` — bucle normalizado de «industrial ambient 2» (Drive · Efectos juego / Calentamiento global y trash). Ambiente del mundo Industria.
- `ambience-forest.mp3` — “Forest Ambience”, TinyWorlds. CC0. [OpenGameArt](https://opengameart.org/content/forest-ambience)
- `ambience-farm.ogg` — grabación de recinto avícola, Monika Widzicka / Work With Sounds. CC BY 4.0. [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:WWS_Poultryenclosure.ogg) · [Licencia](https://creativecommons.org/licenses/by/4.0/)

## Música de las secciones

Pistas aportadas por el equipo para identificar cada sección. Se reproducen en bucle por el canal **Música** al entrar en la sección y reemplazan la armonía sintetizada mientras suenan. Al abrir un minijuego se detienen y suena la pista del mundo; al volver a la ruta, vuelve la de **Minijuegos**.

- `section-inicio.mp3` — Inicio
- `section-explorador.mp3` — Explorador climático
- `section-linea-del-tiempo.mp3` — Línea del tiempo
- `section-historia.mp3` — Historia del clima
- `section-factores.mp3` — Factores
- `section-minijuegos.mp3` — Minijuegos (solo en la ruta, nunca sobre un mundo abierto)
- `section-fuentes.mp3` — Fuentes y metodología

La página **Acerca del proyecto** conserva la armonía sintetizada: no vino una pista propia para ella.

## Música de los minijuegos

Pistas aportadas por el equipo del proyecto; se reproducen en bucle por el canal **Música** al abrir cada mundo y reemplazan la armonía sintetizada mientras suenan. Su volumen se iguala en código (factor `track.gain` en `AudioProvider.tsx`, medido en LUFS).

- `music-manten-la-red.mp3` — Mantén la red (Energía)
- `music-puente-de-materiales.mp3` — Puente de materiales (Industria)
- `music-carga-entre-ciudades.mp3` — Carga entre ciudades (Transporte)
- `music-guardabosques.mp3` — Guardabosques (Bosques)
- `music-finca-equilibrada.mp3` — Finca equilibrada (Agricultura)

Antes de publicar el sitio, confirma y anota aquí el autor y la licencia de cada pista.
