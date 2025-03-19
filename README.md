Este proyecto es una aplicación web simple para organizar un **Amigo Secreto**, permitiendo a los usuarios agregar nombres y luego sortear aleatoriamente un participante.

##Características
- Agregar nombres a una lista validando que no estén vacíos.
- Mostrar los nombres agregados en una lista.
- Seleccionar un nombre al azar y mostrarlo como el amigo secreto.

Tecnologías Utilizadas
- **HTML** → Para la estructura de la página.
- **JavaScript** → Para la lógica de agregar nombres y sortear.

## Estructura del Proyecto
📁 AmigoSecreto
│── 📁 assets       # Contiene imágenes utilizadas en la página
│── 📄 index.html   # Estructura principal del sitio web
│── 📄 style.css    # Archivo de estilos para la página
│── 📄 app.js       # Lógica del juego en JavaScript
│── 📄 README.md    # Documentación del proyecto
```

## Uso
1. Escribe un nombre en el campo de entrada.
2. Haz clic en **Añadir** para agregarlo a la lista.
3. Repite el proceso hasta agregar todos los participantes.
4. Presiona **Sortear amigo** para elegir uno al azar.
5. Se mostrará el amigo secreto seleccionado.

## Funciones Principales
### `agregarAmigo()`
- Obtiene el nombre ingresado en el input.
- Valida que el nombre no esté vacío.
- Agrega el nombre al arreglo y lo muestra en la lista.

### `sortearAmigo()`
- Verifica que haya al menos un nombre en la lista.
- Selecciona aleatoriamente un nombre del arreglo.
- Muestra el resultado en la pantalla.

## Captura de Pantalla
*(Agrega una imagen aquí si es necesario)*

## Licencia
Este proyecto es de código abierto y está disponible bajo la licencia MIT.

