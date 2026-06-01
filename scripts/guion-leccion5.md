# Lección 5 — Estilo Simple: Tipografía, Bordes y Centrado

## Introducción (1 min)

Hola, bienvenidos de nuevo al curso de Fundamentos de Desarrollo Web.

En la lección anterior aprendiste los conceptos básicos de CSS: colores y cómo conectar CSS con HTML.

Hoy vamos un paso más adelante. Aprenderás a cambiar la tipografía de tu página, a controlar los espacios alrededor de los elementos, a agregar bordes y a centrar contenido en pantalla.

Estas herramientas son las que hacen que una página pase de verse amateur a verse realmente profesional.

Abre el JDoodle de esta lección y continuemos.

<br>

---

## Desarrollo (8 min)

### Tipografía con fuentes del sistema

La forma más sencilla de cambiar la letra es con `font-family`, usando fuentes que ya tiene instaladas el sistema operativo:

```css
body {
  font-family: Arial, sans-serif;
}
```

Siempre se escribe más de una fuente separadas por coma. Si el navegador no tiene la primera, usa la siguiente. `sans-serif` es un tipo genérico que garantiza que siempre habrá una fuente disponible.

Algunas fuentes del sistema populares:

```css
font-family: Arial, sans-serif;
font-family: Georgia, serif;
font-family: 'Courier New', monospace;
font-family: Verdana, sans-serif;
```

<br>

### Tipografía con Google Fonts

Google Fonts permite usar cientos de fuentes gratuitas y modernas directamente desde internet. Solo necesitas agregar un `<link>` en el `<head>` de tu HTML.

**Paso 1:** Ve a [fonts.google.com](https://fonts.google.com), elige una fuente y copia el `<link>` que te dan.

**Paso 2:** Pégalo en el `<head>` de tu `index.html`, antes del link a `styles.css`:

```html
<head>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
```

**Paso 3:** Úsala en `styles.css` igual que cualquier otra fuente:

```css
body {
  font-family: 'Poppins', sans-serif;
}
```

El nombre de la fuente debe ir entre comillas si tiene más de una palabra, como `'Poppins'` o `'Open Sans'`.

<br>

### Centrar texto

La forma más sencilla de centrar texto es con la propiedad `text-align`:

```css
h1 {
  text-align: center;
}
```

Los valores posibles son `center`, `left`, `right` y `justify`.

<br>

### Bordes

Con la propiedad `border` puedes agregar un borde alrededor de cualquier elemento:

```css
p {
  border: 2px solid black;
}
```

Esta propiedad tiene tres partes:

- `2px` — el grosor del borde.
- `solid` — el estilo (puede ser `solid`, `dashed` o `dotted`).
- `black` — el color del borde.

También puedes redondear las esquinas con `border-radius`:

```css
p {
  border: 2px solid black;
  border-radius: 10px;
}
```

<br>

### Padding: espacio interior

El `padding` es el espacio entre el contenido de un elemento y su borde.

```css
p {
  padding: 10px;
}
```

Piensa en él como el relleno interno. Le da aire al contenido para que no quede pegado al borde.

<br>

### Margin: espacio exterior

El `margin` es el espacio entre el elemento y los demás elementos que lo rodean.

```css
p {
  margin: 20px;
}
```

Si quieres centrar un bloque horizontalmente, puedes usar:

```css
div {
  margin: 0 auto;
  width: 600px;
}
```

Esto le dice al navegador: "a los lados que se distribuya automáticamente", lo que centra el bloque en la página.

<br>

### Ejemplo completo

**`index.html`**

```html
<!DOCTYPE html>
<html>
  <head>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <title>Mi tarjeta</title>
  </head>
  <body>
    <div class="tarjeta">
      <h1>Mi tarjeta</h1>
      <p>Una tarjeta centrada con fuente de Google Fonts, bordes redondeados y espaciado.</p>
    </div>
  </body>
</html>
```

**`styles.css`**

```css
body {
  background-color: #f4f4f4;
  font-family: 'Poppins', sans-serif;
}

.tarjeta {
  background-color: white;
  border: 2px solid #cccccc;
  border-radius: 12px;
  padding: 20px;
  margin: 30px auto;
  width: 500px;
  text-align: center;
}

h1 {
  color: #333333;
}

p {
  color: #666666;
  font-size: 16px;
}
```

Observa cómo el HTML queda limpio y los estilos viven completamente en `styles.css`.

<br>

---

## Práctica (1 min)

**🏆 Reto 5: Tu tarjeta de presentación**

Abre el JDoodle de esta lección. Verás dos archivos: `index.html` y `styles.css`.

En `index.html` crea un `<div class="tarjeta">` con tu contenido.
En `styles.css` aplica:

1. Una fuente de Google Fonts que te guste.
2. Un borde con `border-radius` para esquinas redondeadas.
3. `padding` suficiente para que el contenido tenga espacio interior.
4. Centra la tarjeta con `margin: 0 auto` y un `width` definido.

Presiona **Execute** y verifica que la tarjeta se vea centrada y con buena tipografía.

<br>

---

## Cierre (30 seg)

Excelente trabajo.

Hoy aprendiste a cambiar tipografías con fuentes del sistema y con Google Fonts, a agregar bordes con `border` y `border-radius`, y a controlar el espaciado con `padding` y `margin`.

Estas propiedades son fundamentales en cualquier diseño web y las usarás constantemente.

En la siguiente lección combinarás todo lo aprendido para construir tu página de perfil personal completa.

¡Nos vemos en la siguiente clase!

<br>

---

> **Equipo PetHealt** · Universidad Peruana de Ciencias Aplicadas
> Ingeniería de Software · 1ASI0730 Aplicaciones Web · 202520