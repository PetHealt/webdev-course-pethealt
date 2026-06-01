# Lección 4 — Introducción a CSS

## Introducción (1 min)

Hola, bienvenidos de nuevo al curso de Fundamentos de Desarrollo Web.

En las lecciones anteriores aprendiste a construir la estructura de una página web con HTML.

Pero seguro notaste que todo se veía muy simple: texto negro sobre fondo blanco, sin color, sin estilo.

Hoy cambia eso. En esta lección aprenderás CSS, el lenguaje que le da vida visual a tus páginas web.

Verás cómo cambiar colores, tamaños de texto y conectar CSS con tu HTML.

Abre el JDoodle de esta lección y empecemos.

<br>

---

## Desarrollo (8 min)

### ¿Qué es CSS y cómo se escribe?

CSS funciona con una sintaxis muy clara. Toda regla CSS tiene esta forma:

```css
selector {
  propiedad: valor;
}
```

- El **selector** indica a qué elemento HTML quieres aplicar el estilo.
- La **propiedad** es qué aspecto quieres cambiar.
- El **valor** es cómo quieres cambiarlo.

Por ejemplo, para que todos los párrafos tengan texto azul:

```css
p {
  color: blue;
}
```

<br>

### ¿Cómo conectar CSS con HTML?

En este curso trabajamos siempre con **dos archivos separados**:

- `index.html` — contiene la estructura y el contenido.
- `styles.css` — contiene todos los estilos.

Para conectarlos, se usa la etiqueta `<link>` dentro del `<head>` del HTML:

```html
<head>
  <title>Mi página</title>
  <link rel="stylesheet" href="styles.css">
</head>
```

Esta línea le dice al navegador: "busca el archivo `styles.css` y aplica todos sus estilos a esta página".

A partir de ahora, **todo el CSS lo escribiremos en `styles.css`**, nunca dentro del HTML.

<br>

### Cambiar colores

La propiedad `color` cambia el color del texto:

```css
h1 {
  color: red;
}
```

La propiedad `background-color` cambia el color de fondo:

```css
body {
  background-color: lightblue;
}
```

Puedes usar nombres de colores en inglés como `red`, `blue`, `green`, `orange`, `white`, `black`, o también códigos hexadecimales como `#ff5733`.

<br>

### Cambiar el tamaño y la fuente del texto

Con `font-size` controlas el tamaño del texto:

```css
p {
  font-size: 18px;
}
```

Con `font-family` cambias el tipo de letra:

```css
body {
  font-family: Arial, sans-serif;
}
```

<br>

### Ejemplo completo

**`index.html`**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Mi página con estilo</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1>Mi página con estilo</h1>
    <p>Este párrafo ahora tiene un estilo definido con CSS.</p>
  </body>
</html>
```

**`styles.css`**

```css
body {
  background-color: #f0f8ff;
  font-family: Arial, sans-serif;
}

h1 {
  color: darkblue;
  font-size: 36px;
}

p {
  color: #333333;
  font-size: 16px;
}
```

Fíjate cómo el HTML queda limpio y el CSS vive completamente en su propio archivo. Eso hace que el código sea más fácil de mantener y organizar.

<br>

---

## Práctica (1 min)

**🏆 Reto 4: Dale color a tu página**

Abre el JDoodle de esta lección. Verás dos archivos: `index.html` y `styles.css`.

Escribe en `styles.css`:

1. Un color de fondo a la página con `background-color`.
2. Un color diferente al título `<h1>`.
3. Un tamaño de fuente distinto al de los párrafos con `font-size`.

Presiona **Execute** y observa la transformación.

<br>

---

## Cierre (30 seg)

Muy bien hecho.

Hoy aprendiste la sintaxis de CSS, cómo conectarlo con HTML y cómo usar propiedades básicas como `color`, `background-color`, `font-size` y `font-family`.

Ya puedes transformar una página simple en algo visualmente atractivo.

En la siguiente lección aprenderás a controlar los espacios, bordes y el centrado de los elementos para que tu página tenga una apariencia aún más profesional.

¡Nos vemos en la siguiente clase!

<br>

---

> **Equipo PetHealt** · Universidad Peruana de Ciencias Aplicadas
> Ingeniería de Software · 1ASI0730 Aplicaciones Web · 202520