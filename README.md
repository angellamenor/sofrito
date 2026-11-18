# Sofrito

*Deja de seguir recetas y crea las tuyas con IA.*

Dicen que empiezas a ser mayor de verdad el día que ya no llamas a tus padres para preguntar cómo se hace un sofrito. Con la IA pasa lo mismo: el aprendizaje llega cuando dejas de seguir recetas ajenas y empiezas a crear las tuyas. Eso es humanizar la IA.

Proyecto gratuito y sin ánimo de lucro, hecho para ayudar a los docentes.

App del taller para docentes **Humanizar la IA**, de Ángel Luis González Serrano.

Los participantes dan voz con IA a alguien que vivió la erupción de La Palma de 2021, en tres pasos y desde el móvil:

1. **Crea**: el chatbot en https://partyrock.aws/ («Usar IA» → «Flow») a partir de una frase, con imagen del personaje.
2. **Afina**: el personaje capa a capa (generales, actitudinales, situacionales y aula), siguiendo La Cebolla Sónica. Empieza en blanco y se pueden cargar ejemplos. Genera el prompt listo para pegar.
3. **Evalúa**: dos evaluaciones. La automática revisa los ingredientes del prompt y sugiere qué añadir; la humana es una conversación de 5 minutos con temporizador y la rúbrica del Test de Turing de 6 criterios.

## Uso

Es una web instalable (PWA): se abre desde un enlace y se puede instalar como app con su icono en el móvil o en el ordenador. Al abrirla en el navegador pide instalarla: se trabaja siempre con la app instalada. Para usarla en el navegador (por ejemplo, para proyectarla) añade `#web` al final de la dirección. Una vez instalada, funciona también sin conexión. Cada vez que se abre muestra una animación de bienvenida (también se repite tocando el logo de Inicio).

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
