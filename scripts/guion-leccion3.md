# Lección 3 — Elementos HTML Comunes

## Introducción (1 min)

Hola, bienvenidos de nuevo al curso de Fundamentos de Desarrollo Web.

En la lección anterior aprendiste la estructura básica de HTML y cómo funcionan las etiquetas.

Hoy vamos a enriquecer esa estructura. Aprenderás a usar los elementos más comunes del HTML: encabezados, párrafos, listas, imágenes y enlaces.

Con estos elementos podrás construir páginas web con contenido real y variado.

Abre el JDoodle de esta lección y comencemos.

<br>

---

## Desarrollo (8 min)

### Encabezados

Los encabezados son títulos y subtítulos. En HTML existen seis niveles, del `<h1>` al `<h6>`.

```html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
<h3>Sección más pequeña</h3>
```

`<h1>` es el más grande e importante. `<h6>` es el más pequeño.

Piensa en ellos como los títulos de un libro: el título del libro sería `<h1>`, los capítulos serían `<h2>`, y las secciones dentro de cada capítulo serían `<h3>`.

<br>

### Párrafos

Para escribir texto normal en una página, usamos la etiqueta `<p>`:

```html
<p>Este es un párrafo de texto.</p>
<p>Este es otro párrafo separado.</p>
```

Cada `<p>` genera un bloque de texto con espacio automático antes y después.

<br>

### Listas

HTML tiene dos tipos de listas.

**Lista sin orden** — `<ul>` (unordered list):

```html
<ul>
  <li>Fútbol</li>
  <li>Música</li>
  <li>Programación</li>
</ul>
```

Muestra los elementos con viñetas (puntos).

**Lista ordenada** — `<ol>` (ordered list):

```html
<ol>
  <li>Primero</li>
  <li>Segundo</li>
  <li>Tercero</li>
</ol>
```

Muestra los elementos numerados automáticamente.

En ambos casos, cada elemento de la lista va dentro de una etiqueta `<li>`.

<br>

### Imágenes

Para mostrar una imagen usamos la etiqueta `<img>`:

```html
<img src="foto.jpg" alt="Una descripción de la imagen">
```

Esta etiqueta tiene dos atributos importantes:

- `src` indica la ruta o URL de la imagen.
- `alt` es una descripción de texto alternativo. Aparece si la imagen no carga y es importante para la accesibilidad.

A diferencia de otras etiquetas, `<img>` no tiene etiqueta de cierre. Se cierra sola.

**Ejemplo con una imagen de internet:**

```html
<img src="https://via.placeholder.com/300" alt="Imagen de ejemplo">
```

<br>

### Enlaces

Los enlaces permiten navegar a otras páginas. Se crean con la etiqueta `<a>`:

```html
<a href="https://www.google.com">Ir a Google</a>
```

El atributo `href` indica la dirección a la que lleva el enlace.
El texto entre las etiquetas es lo que el usuario ve y puede hacer clic.

Para que el enlace abra en una pestaña nueva, agrega `target="_blank"`:

```html
<a href="https://www.google.com" target="_blank">Abrir Google en nueva pestaña</a>
```

<br>

---

## Práctica (1 min)

**🏆 Reto 3: Página de mis intereses**

Abre el JDoodle de esta lección y crea una página que tenga:

1. Un encabezado `<h1>` con tu nombre.
2. Un párrafo `<p>` describiendo quién eres.
3. Una lista `<ul>` con tres cosas que te gusten.
4. Un enlace `<a>` a tu red social o sitio favorito.

Presiona **Execute** y verifica que todo aparezca correctamente.

<br>

---

## Cierre (30 seg)

Excelente trabajo.

Hoy aprendiste a usar los elementos HTML más comunes: encabezados `<h1>`–`<h6>`, párrafos `<p>`, listas `<ul>` y `<ol>`, imágenes `<img>` y enlaces `<a>`.

Con estos elementos ya puedes construir páginas con contenido real.

En la siguiente lección le daremos estilo a todo esto usando CSS para que tu página se vea profesional y con color.

¡Nos vemos en la siguiente clase!

<br>

---

> **Equipo PetHealt** · Universidad Peruana de Ciencias Aplicadas
> Ingeniería de Software · 1ASI0730 Aplicaciones Web · 202520