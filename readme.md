# 🎨 Introducción a CSS

¡Bienvenido a este repositorio de **Introducción a CSS**! 🚀

Este proyecto está diseñado para ayudarte a comprender los conceptos básicos de CSS (Cascading Style Sheets) y cómo aplicarlos para mejorar la presentación de tus páginas web. Aquí encontrarás ejemplos prácticos y explicaciones teóricas para que puedas comenzar a estilizar tus propios sitios web de manera efectiva.

---

## 📚 ¿Qué es CSS?

CSS es un lenguaje de hojas de estilo que permite definir la apariencia y el formato de los documentos HTML. Gracias a CSS, puedes separar el contenido (HTML) de la presentación (colores, fuentes, márgenes, etc.), facilitando el mantenimiento y la reutilización del código.

---

## 🧩 Temas tratados en este repositorio

A continuación, se describen los principales conceptos de CSS que se abordan en este proyecto:

### 1. **Selectores** 🔎
- **Selectores de tipo**: Seleccionan todos los elementos de un tipo específico, por ejemplo, `section` o `p`.
- **Selectores de clase**: Seleccionan elementos con una clase específica, por ejemplo, `.importante`.
- **Selectores de ID**: Seleccionan un elemento con un ID específico, por ejemplo, `#principal`.
- **Selectores combinados**: Permiten seleccionar elementos según su relación en el DOM, como `main section p` (descendientes), `main > section > p` (hijos directos), `p ~ span` (hermanos generales) y `p + span` (hermano adyacente).

### 2. **Colores y Esquemas de Color** 🎨
- Uso de colores por nombre (`red`, `blue`, `green`, `deeppink`, `pink`).
- Uso de valores RGB (`rgb(37, 152, 163)`).
- Uso de la función `light-dark()` y la propiedad `color-scheme` para soportar temas claro/oscuro.

### 3. **Especificidad y Cascada** 🏗️
- Ejemplo de cómo los selectores más específicos (ID, clase, tipo) pueden sobrescribir estilos menos específicos.
- Comentarios sobre la importancia de la cascada y el orden de los estilos.

### 4. **Comentarios en CSS** 💬
- Uso de comentarios para documentar o desactivar reglas CSS temporalmente.

---

## 📝 Ejemplo de código

```css
section.importante {
  color: green;
}

#principal {
  color: red;
}

p ~ span {
  color: deeppink;
}
```

---

## 🚦 ¿Cómo usar este repositorio?

1. Abre el archivo `index.html` en tu navegador para ver los estilos aplicados.
2. Modifica el archivo `css/style.css` para experimentar con diferentes reglas y selectores.
3. Observa cómo cambian los estilos en la página y prueba combinaciones nuevas.

---

## 📖 Recursos recomendados

- [MDN Web Docs: CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [CSS Tricks](https://css-tricks.com/)

---

¡Explora, experimenta y aprende CSS! 💡✨
