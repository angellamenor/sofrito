# Sofrito

*Tu receta para ser autónomo con la IA.*

Ser autónomo no es alquilar un piso ni ponerle internet: eres autónomo el día que sabes hacer un sofrito. Con la IA pasa igual: no eres autónomo por usarla, sino cuando sabes humanizarla.

App del taller para docentes **Humanizar la IA**, de Ángel Luis González Serrano.

Los participantes dan voz con IA a alguien que vivió la erupción de La Palma de 2021, en tres pasos y desde el móvil:

1. **Diseña tu personaje**: rasgos generales, actitudinales y situacionales. La app genera el prompt listo para copiar.
2. **Créalo en PartyRock**: pasos para convertir el prompt en una app de IA en https://partyrock.aws/.
3. **Pásale el Test de Turing**: 5 minutos de conversación con temporizador y una rúbrica de 6 criterios que da el porcentaje de humanidad y sugiere mejoras para el prompt.

## Uso

Es una web instalable (PWA): se abre desde un enlace y se puede instalar como app con su icono en el móvil o en el ordenador. Una vez abierta, funciona también sin conexión. La primera vez muestra una animación de bienvenida (se puede repetir tocando el logo de Inicio).

Archivos:

- `index.html`: la app completa.
- `manifest.webmanifest`: nombre, colores e iconos de la app instalada.
- `sw.js`: guarda la app para que abra rápido y funcione sin conexión.
- `icons/`: logo e iconos.

**Instalar:** en Android (Chrome) y en el ordenador (Chrome o Edge) aparece la opción de instalar; en iPhone, Safari → Compartir → Añadir a pantalla de inicio. La propia app lo explica en el botón «Instalar la app».

Si cambias la app, sube el número de versión de `CACHE` en `sw.js` para que los dispositivos reciban la actualización.

Para publicarla con GitHub Pages: *Settings → Pages → Deploy from a branch → main / (root)*. La dirección será `https://<usuario>.github.io/<repositorio>/`.

Los datos que escribe cada participante se guardan solo en su navegador.

## Contacto

angel.lamenor@gmail.com
