# utilidadesVSCode

## Ediciones y tips básicos

- Mover líneas: `Alt + ↑ / ↓`.
- Comentar líneas: `Ctrl + Ç`.
- Comentar código seleccionado o crear comentario en la posición del cursor: `Shift + Alt + A`.
- Crear archivo: en una ruta inexistente `Ctrl + Click` y VSCode ofrecerá crear el archivo.
- Ir a la definición: `Ctrl + click` o `F12`.
- Ver definición sin salir del archivo: `Shift + F12`.
- Borrar líneas: `Ctrl + Shift + K`.
- Seleccionar todas las coincidencias de un texto en el archivo: `Ctrl + Shift + L`.
- Deshacer cambios: `Ctrl + Z`.
- Rehacer cambios: `Ctrl + Shift + Z` o `Ctrl + Y`.
- Mostrar y ocultar barra lateral: `Ctrl + B`.
- Entrar en Zen mode: `Ctrl + K Z`.
- Salir del Zen mode: `F11`.
- Buscar archivos: `Ctrl + P`.
- Mostrar y ocultar terminal: `Ctrl + Ñ`.
- Crear nueva terminal: `Ctrl + Alt + O`.
- Dividir terminal: `Ctrl + Shift + 5`.
- Navegar entre terminales divididas: `Alt + ← / →`.
- Abrir paleta de comandos: `Ctrl + Shift + P` o `F1`.
- Envolver código: con código seleccionado abrir la paleta de comandos y buscar `wrap with abbreviation` y escribir con lo que queramos envolver (acepta emmet).
- Abrir ventana shortcuts: `Ctrl + K Ctrl + S`.
- Cerrar ventana: `Ctrl + W`.
- Cerrar todas: `Ctrl + K Ctrl + W`.
- Reabrir pestaña anterior: `Ctrl + Shift + T`.
- Cambiar a la pestaña siguiente: `Ctrl + TAB`.
- Cambiar a la pestaña anterior: `Ctrl + Shift + TAB`.
- Crear nueva división: `Ctrl + número de divisiones + 1`.
- Navegar a división: `Ctrl + número de división`.

## Multi cursores y edición rápida

- Clonar líneas: `Shift + Alt + ↑ / ↓`.
- Multi cursor básico: `Ctrl + Shift + Alt + ↑ / ↓`.
- Multi cursor en un punto concreto: `Alt + Click`.
- Seleccionar palabras: `Ctrl + Shift + ← / →`.
- Seleccionar fila desde el principio: `Shift + Fin`.
- Seleccionar fila desde el final: `Shift + Inicio`.
- Seleccionar desde el cursos hasta el principio del documento: `Ctrl + Shift + Inicio`.
- Seleccionar desde el cursos hasta el final del documento: `Ctrl + Shift + Fin`.
- Lowercase: `Ctrl + Alt + X`.
- Uppercase: `Ctrl + Shift + X`.
- Siguiente ocurrencia: `Ctrl + D`.
- Mover cursor a la siguiente ocurrencia: `Ctrl + F3`.
- Mover cursor a la anterior ocurrencia: `Ctrl + Shift + F3`.

## Definiciones y Snippets

- Ver definicion: `Ctrl + P @` o `Ctrl + Shift + O`.
- Ver definiciones agrupadas: `Ctrl + P @:` o `Ctrl + Shift + O :`.
- Ir a una línea: `Ctrl + P : número de línea` o `Ctrl + G`.
- Preview Markdown: `Ctrl + Shift + P` o `F1` y poner `Markdown Open Preview` o `Markdown Open Preview to the side`, este último permite ver los cambios en tiempo real.
- Reemplazar símbolo: para cambiarlo de forma local, con lo que queramos cambiar seleccionamos, pulsamos `F2`. Para cambiarlo de forma global, hacerlo en el archivo principal.
- Crear snippets: `Ctrl + Shift + P` y poner `Configure User Snippets` y elegir el lenguaje para el que queramos crear el snippet. El snippet está compuesto por varias partes:
  - Nombre del snippet.
  - `prefix`: cadena con el que se mostrará el snippet.
  - `body`: el código que será introducido. Se pueden meter variables con `$` más un índice. Se le puede dar valores por defecto a las variables con `${índice:valor}`. Una vez introducido el snippet se podrá navegar entre las variables con `TAB` en el orden que se le haya puesto. Si no tiene variables, el cursor se pondrá al final del código introducido.
  - `descripction`: es opcional, sirve para indicar la funcionalidad del snippet.
