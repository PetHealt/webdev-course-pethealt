# Lección 2 — Estructura HTML Básica

## Introducción (1 min)

Hola, bienvenidos de nuevo al curso de Fundamentos de Desarrollo Web.

En la lección anterior aprendiste qué son HTML y CSS y cómo trabajan juntos para crear páginas web.

Hoy vamos a dar el primer paso real: escribir código HTML.

Aprenderás cuál es la estructura básica que todo documento HTML debe tener, y entenderás qué significa cada parte. Al final de esta lección tendrás tu primera página web funcionando.

Abre el JDoodle de esta lección y sigamos juntos.

<br>

---

## Desarrollo (6 min)

### La estructura básica de HTML

Todo documento HTML tiene una estructura fija que siempre se repite. Esta es:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Mi primera página</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <!-- aquí va el contenido visible -->
  </body>
</html>
```

En este curso trabajaremos siempre con **dos archivos separados**: `index.html` para el contenido y `styles.css` para los estilos. La etiqueta `<link>` en el `<head>` es la que los conecta. Por ahora `styles.css` estará vacío, pero lo iremos llenando a partir de la lección 4.

Puede parecer mucho al principio, pero vamos parte por parte.

<br>

### 1. `<!DOCTYPE html>`

```html
<!DOCTYPE html>
```

Esta línea le indica al navegador que el documento está escrito en HTML moderno.

Siempre debe ser la primera línea de cualquier archivo HTML.

No es una etiqueta como las demás. Es una declaración, una instrucción especial para el navegador.

<br>

### 2. La etiqueta `<html>`

```html
<html>
  ...
</html>
```

Todo el contenido de la página va dentro de esta etiqueta.

Es como la caja grande que contiene todo lo demás.

Nota que tiene una etiqueta de apertura `<html>` y una de cierre `</html>`. La barra `/` indica que es el cierre.

<br>

### 3. La etiqueta `<head>`

```html
<head>
  <title>Mi primera página</title>
</head>
```

El `<head>` contiene información sobre la página que el navegador necesita pero que el usuario no ve directamente.

Aquí se coloca el título de la pestaña del navegador con la etiqueta `<title>`.

<br>

### 4. La etiqueta `<body>`

```html
<body>
  <!-- aquí va el contenido visible -->
</body>
```

El `<body>` es donde va todo el contenido que el usuario sí puede ver en pantalla: textos, imágenes, botones, etc.

Es el cuerpo de la página.

<br>

### ¿Cómo funcionan las etiquetas?

En HTML, casi todos los elementos se abren y se cierran:

```html
<h1>Este es un título</h1>
<p>Este es un párrafo.</p>
```

La etiqueta de apertura indica dónde empieza el elemento.
La etiqueta de cierre, con la barra `/`, indica dónde termina.

El texto entre ambas es el contenido que se mostrará en pantalla.

<br>

### Los comentarios

```html
<!-- Esto es un comentario -->
```

Los comentarios son notas que escribimos en el código para explicarlo.
El navegador los ignora completamente y no los muestra en pantalla.

Son muy útiles para recordar qué hace cada parte del código.

<br>

---

## Práctica (1 min)

**🏆 Reto 2: Tu primera página completa**

Abre el JDoodle de esta lección y escribe la estructura básica de HTML.

Luego, dentro del `<body>`, agrega esta línea:

```html
<h1>Hola, soy [tu nombre]</h1>
```

Presiona **Execute** y verifica que aparezca tu nombre como título en la página.

Si lo lograste, ¡felicitaciones! Ya tienes tu primera página web funcionando.

<br>

---

## Cierre (30 seg)

Muy bien hecho.

Hoy aprendiste la estructura fundamental de todo documento HTML: `<!DOCTYPE html>`, `<html>`, `<head>` y `<body>`. También viste cómo funcionan las etiquetas y qué son los comentarios.

Esta estructura es la base de cualquier página web, por más grande o pequeña que sea.

En la siguiente lección aprenderás a agregar títulos, párrafos, listas, imágenes y enlaces para enriquecer tu página.

¡Nos vemos en la siguiente clase!

<br>

---

> **Equipo PetHealt** · Universidad Peruana de Ciencias Aplicadas
> Ingeniería de Software · 1ASI0730 Aplicaciones Web · 202520