# Rediseño de Pantalla de Login (Estilo Gradient)

Se ha actualizado la interfaz para que coincida con la imagen de referencia, aplicando un estilo moderno con gradientes y elementos redondeados.

## Cambios realizados

### Recursos Visuales
- **Fondo de Pantalla**: Creado [bg_main_gradient.xml](file:///C:/juice%20lub/papoi/app/src/main/res/drawable/bg_main_gradient.xml) con un gradiente de Azul a Rojo pasando por Púrpura.
- **Entradas de Texto**: Actualizado [bg_rounded_edittext.xml](file:///C:/juice%20lub/papoi/app/src/main/res/drawable/bg_rounded_edittext.xml) a un estilo transparente con borde blanco y esquinas tipo cápsula.
- **Botón**: Actualizado [bg_rounded_button.xml](file:///C:/juice%20lub/papoi/app/src/main/res/drawable/bg_rounded_button.xml) a color blanco sólido con esquinas tipo cápsula.
- **Iconos**:
    - **Usuario**: Actualizado a un icono blanco con silueta circular.
    - **Redes Sociales**: Se crearon iconos circulares para **Facebook** y **LinkedIn** (reemplazando Instagram para coincidir con la imagen).

### Interfaz de Usuario (XML)
- [activity_main.xml](file:///C:/juice%20lub/papoi/app/src/main/res/layout/activity_main.xml):
    - Se aplicó el fondo gradiente.
    - Se cambió el color de los textos y hints a blanco.
    - El botón ahora tiene texto en color azul y fondo blanco.
    - Se ajustaron los espaciados y tamaños para reflejar fielmente la referencia.

### Lógica
- La lógica en [MainActivity.kt](file:///C:/juice%20lub/papoi/app/src/main/java/com/example/papoi/MainActivity.kt) se mantiene intacta, validando los campos y mostrando el Toast de éxito.

## Verificación
- Compilación exitosa.
- Verificación visual de los colores y formas según la imagen proporcionada.
