# Lección 7 — Consejos y Próximos Pasos

## Introducción (30 seg)

Hola, bienvenidos a la última lección del curso de Fundamentos de Desarrollo Web.

Llegaste hasta aquí y eso ya dice mucho de ti.

En esta lección no vamos a aprender código nuevo. En cambio, vamos a hablar de algo igualmente importante: cómo seguir mejorando, qué errores evitar y dónde encontrar recursos para continuar aprendiendo por tu cuenta.

<br>

---

## Desarrollo (4 min)

### Buenas prácticas que debes recordar siempre

**1. Usa nombres descriptivos en tus clases**

En lugar de:

```html
<div class="caja1">
```

Usa:

```html
<div class="tarjeta-perfil">
```

Los nombres descriptivos hacen que tu código sea más fácil de entender, tanto para ti como para otras personas.

<br>

**2. Siempre incluye el atributo `alt` en las imágenes**

```html
<img src="foto.jpg" alt="Foto de perfil de Ana">
```

El `alt` es importante para la accesibilidad. Ayuda a personas con discapacidad visual que usan lectores de pantalla, y también aparece si la imagen no carga.

<br>

**3. Indenta tu código correctamente**

Un código bien indentado es fácil de leer:

```html
<body>
  <div class="perfil">
    <h1>Mi nombre</h1>
    <p>Mi descripción</p>
  </div>
</body>
```

Usa espacios o tabulaciones consistentes. Tu código te lo agradecerá en el futuro.

<br>

**4. Valida tu HTML**

Antes de compartir una página, verifica que tu HTML esté bien escrito usando la herramienta oficial:

🔗 [validator.w3.org](https://validator.w3.org)

Pega tu código o ingresa la URL de tu página y el validador te dirá si hay errores.

<br>

**5. Lee los errores con calma**

Cuando algo no se vea como esperabas, no entres en pánico.

Revisa si:
- Cerraste todas las etiquetas correctamente.
- El nombre del archivo CSS coincide con el que pusiste en `href`.
- Las comillas de los atributos están bien escritas.

El 90% de los problemas en HTML y CSS son pequeños errores de escritura.

<br>

### Errores comunes a evitar

| Error | Ejemplo incorrecto | Corrección |
|---|---|---|
| Olvidar cerrar una etiqueta | `<h1>Hola` | `<h1>Hola</h1>` |
| Escribir mal un nombre de propiedad | `colour: red;` | `color: red;` |
| Olvidar el punto y coma en CSS | `color: red` | `color: red;` |
| No incluir `alt` en imágenes | `<img src="foto.jpg">` | `<img src="foto.jpg" alt="...">` |

<br>

### ¿Por dónde seguir aprendiendo?

Completar este curso es solo el inicio. Aquí tienes los mejores recursos gratuitos para continuar:

**Documentación oficial:**
- [MDN Web Docs en Español](https://developer.mozilla.org/es/) — La referencia más completa de HTML, CSS y JavaScript. Es el recurso que usan los profesionales.

**Cursos interactivos gratuitos:**
- [freeCodeCamp — Responsive Web Design](https://www.freecodecamp.org/learn/2022/responsive-web-design/) — Aprende a hacer páginas que se adapten a celular y computadora.
- [The Odin Project](https://www.theodinproject.com/) — Un camino completo para aprender desarrollo web desde cero.

**Practica construyendo:**
- Recrea páginas web que te gusten.
- Crea páginas para tu equipo, tu clase o tus proyectos personales.
- Cada página que construyas te hará mejor desarrollador o desarrolladora.

<br>

---

## Cierre (30 seg)

Llegaste al final del curso y eso es algo de lo que debes estar muy orgulloso u orgullosa.

En estas siete lecciones aprendiste qué es el desarrollo web, la estructura de HTML, los elementos más comunes, CSS y cómo aplicar estilos profesionales. Y lo más importante: construiste tu propia página web.

Este es exactamente el mismo punto de partida desde donde comenzaron miles de desarrolladores que hoy trabajan en las empresas de tecnología más importantes del mundo.

Sigue practicando, sigue construyendo. El límite es tu imaginación.

🔗 **Comparte tu proyecto final:** no olvides enviar el enlace de tu página de perfil usando el formulario de la lección.

¡Hasta la próxima, y mucho éxito en tu camino como desarrollador o desarrolladora web!

<br>

---

> **Equipo PetHealt** · Universidad Peruana de Ciencias Aplicadas
> Ingeniería de Software · 1ASI0730 Aplicaciones Web · 202520