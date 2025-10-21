## ¿Qué es el objeto window ?

El objeto window es el objeto global del navegador.
Representa la ventana del navegador o el marco (frame) en el que se carga una página web.
Todos los demás objetos del BOM (Browser Object Model), como document, history, location, navigator, y screen, son propiedades del objeto window.

## Principal uso:
Permite controlar y manipular la ventana del navegador, mostrar mensajes emergentes, manejar temporizadores, redirigir a otras páginas, abrir nuevas ventanas, entre otras acciones.

## Principales propiedades de window
Propiedad	Descripción
- window.document	Hace referencia al objeto document, que representa el contenido HTML.
- window.location	Permite acceder o cambiar la URL actual del navegador.
- window.history	Permite navegar hacia adelante o atrás en el historial del navegador.
- window.navigator	Contiene información del navegador del usuario.
- window.screen	Proporciona información sobre la pantalla del usuario.
- window.innerWidth y window.innerHeight	Indican el tamaño interior de la ventana del navegador.
- window.localStorage y window.sessionStorage	Permiten almacenar datos localmente en el navegador.
## Principales métodos de window
- Método	Descripción
- window.alert()	Muestra un cuadro de alerta con un mensaje.
- window.confirm()	Muestra un cuadro de confirmación con opciones Aceptar/Cancelar.
- window.prompt()	Muestra un cuadro para ingresar texto.
- window.open()	Abre una nueva ventana o pestaña del navegador.
- window.close()	Cierra la ventana actual (si fue abierta mediante window.open).
- window.setTimeout()	Ejecuta una función después de un tiempo determinado.
- window.setInterval()	Ejecuta una función repetidamente cada cierto intervalo.