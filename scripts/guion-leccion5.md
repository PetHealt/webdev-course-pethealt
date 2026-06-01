# Lección 5 — Estilo Simple: Colores, Bordes y Centrado

## Introducción (1 min)

Hola, bienvenidos de nuevo al curso de Fundamentos de Desarrollo Web.

En la lección anterior aprendiste los conceptos básicos de CSS: colores, fuentes y cómo conectar CSS con HTML.

Hoy vamos un paso más adelante. Aprenderás a controlar los espacios alrededor de los elementos, a agregar bordes y a centrar contenido en pantalla.

Estas herramientas son las que hacen que una página pase de verse amateur a verse realmente profesional.

Abre el JDoodle de esta lección y continuemos.

<br>

---

## Desarrollo (6 min)

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

También puedes redondear las esquinas del borde con `border-radius`:

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

Puedes controlar cada lado por separado:

```css
p {
  padding-top: 10px;
  padding-right: 20px;
  padding-bottom: 10px;
  padding-left: 20px;
}
```

O en una sola línea (arriba, derecha, abajo, izquierda):

```css
p {
  padding: 10px 20px 10px 20px;
}
```

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

Esto le dice al navegador: "arriba y abajo no hay margen, pero a los lados que se distribuya automáticamente", lo que centra el bloque en la página.

<br>

### Ejemplo completo

**`index.html`**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Mi tarjeta</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <div class="tarjeta">
      <h1>Mi tarjeta</h1>
      <p>Esta es una tarjeta centrada con bordes redondeados y espaciado.</p>
    </div>
  </body>
</html>
```

**`styles.css`**

```css
body {
  background-color: #f4f4f4;
  font-family: Arial, sans-serif;
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

Observa cómo el HTML queda limpio y los estilos viven completamente en `styles.css`. El `<div>` con clase `tarjeta` agrupa el contenido y le da una presentación limpia y profesional.

<br>

---

## Práctica (1 min)

**🏆 Reto 5: Tu tarjeta de presentación**

Abre el JDoodle de esta lección. Verás dos archivos: `index.html` y `styles.css`.

En `index.html` crea un `<div class="tarjeta">` con tu contenido.
En `styles.css` aplica:

1. Un `<div>` centrado con `margin: 0 auto` y un `width` definido.
2. Un borde con `border-radius` para esquinas redondeadas.
3. `padding` suficiente para que el contenido tenga espacio interior.

Presiona **Execute** y verifica que la tarjeta se vea centrada y con buen espaciado.

<br>

---

## Cierre (30 seg)

Excelente trabajo.

Hoy aprendiste a centrar contenido con `text-align`, a agregar bordes con `border` y `border-radius`, y a controlar el espaciado con `padding` y `margin`.

Estas propiedades son fundamentales en cualquier diseño web y las usarás constantemente.

En la siguiente lección combinarás todo lo aprendido para construir tu página de perfil personal completa.

¡Nos vemos en la siguiente clase!

<br>

---

> **Equipo PetHealt** · Universidad Peruana de Ciencias Aplicadas
> Ingeniería de Software · 1ASI0730 Aplicaciones Web · 202520