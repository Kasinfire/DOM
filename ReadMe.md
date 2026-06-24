# DOM

Colección de proyectos pequeños hechos con JavaScript puro (Vanilla JS) para practicar manipulación del DOM: creación dinámica de elementos, eventos, posicionamiento, y manejo de formularios.

## 🗁 Proyectos

### ⛈ Caja de Comentarios

Una pequeño lugar donde los usuarios dejan comentarios que aparecen como nubes flotantes distribuidas aleatoriamente por la pantalla.

**¿Qué hace?**
- El usuario llena un formulario con su nombre y un comentario.
- Al enviar, se genera dinámicamente una "nube" (`<div>`) con el comentario.
- La nube se posiciona en una ubicación aleatoria de la pantalla, evitando superponerse con el formulario.
- Las nubes flotan con una animación suave (`floatCloud`).

**Conceptos de DOM utilizados:**
- `document.createElement()` y `appendChild()` para crear nubes dinámicamente.
- `getBoundingClientRect()` para detectar la posición del formulario y evitar que las nubes se sobrepongan.
- Manipulación de estilos en línea (`style.left`, `style.top`).
- Validación de formulario antes de procesar datos.
- Posicionamiento aleatorio con reintentos (`do...while`) para evitar colisiones.

**Archivos:**
```
caja-comentarios/
├── index.html
├── theme.css
├── cajaComentarios.js
└── assets/
```

---

### 🗝 Generador de Contraseñas

*(Próximamente)*

---

###  ?

*(Próximamente)*

---

## Tecnologías

- HTML5
- CSS3 (variables CSS, animaciones, media queries)
- JavaScript (Vanilla, sin frameworks)

## ₊˚⊹♡ Autor

[Kasinfire](https://github.com/Kasinfire)
