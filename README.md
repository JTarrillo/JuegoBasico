## Flujo del Juego "Corredor Infinito"

- **Inicio del Juego:**
  - El juego comienza con el menú de inicio mostrado.
  - El jugador espera a que el juego comience presionando la tecla correspondiente (en este caso, "X").

- **Validación de Inicio:**
  - Si el jugador presiona la tecla para iniciar el juego, el estado del juego cambia a "Juego en Curso".
  - Si no se ha iniciado el juego y el juego no ha terminado, se muestra el menú de inicio.

- **Juego en Curso:**
  - El fondo y los objetos del juego comienzan a moverse en la pantalla.
  - El jugador controla al personaje y puede realizar saltos presionando la tecla "Espacio".
  - Se actualiza continuamente la posición del jugador y de los obstáculos en el juego.

- **Colisión con Obstáculos:**
  - Si el jugador colisiona con un obstáculo, el estado del juego cambia a "Game Over".
  - Se muestra el menú de fin de juego con la opción de reiniciar el juego presionando la tecla "X".

- **Reinicio del Juego:**
  - Si el jugador decide reiniciar el juego presionando la tecla "X" después de que el juego haya terminado, el estado del juego vuelve a "Inicio".
  - Se restablecen todas las posiciones de los objetos y se reinicia el juego desde el principio.

- **Respuesta del Juego:**
  - Durante todo el proceso, se actualiza la interfaz de usuario para reflejar el estado actual del juego.
  - Se muestran mensajes de inicio, fin de juego y reinicio según corresponda.
  - Se manejan errores, como colisiones con obstáculos, mostrando el menú de fin de juego y permitiendo al jugador reiniciar el juego si lo desea.
