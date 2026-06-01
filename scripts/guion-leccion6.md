# Lección 6 — Proyecto: Tu Página de Perfil Personal

## Introducción (1 min)

Hola, bienvenidos de nuevo al curso de Fundamentos de Desarrollo Web.

Llegó el momento que estuvimos construyendo desde la primera lección.

Hoy vas a crear tu propia página de perfil personal. Una página real, con tu información, tu estilo y tu toque personal.

Vamos a combinar todo lo que aprendiste: la estructura HTML, los elementos de contenido y los estilos CSS.

Al terminar tendrás algo que puedes mostrar a tus amigos y familia, y de lo que puedes sentirte orgulloso o orgullosa.

Abre el JDoodle de esta lección y construyamos juntos.

<br>

---

## Desarrollo (12 min)

### Planificando la página

Antes de escribir código, pensemos en qué secciones tendrá nuestra página de perfil:

1. **Encabezado** — tu nombre y una foto.
2. **Sobre mí** — una breve descripción de quién eres.
3. **Mis intereses** — una lista de cosas que te gustan.
4. **Mis enlaces** — links a tus redes sociales o sitios favoritos.

Organizar el contenido antes de programar es una buena práctica que los desarrolladores usan siempre.

<br>

### Paso 1: `index.html`

Empezamos con la estructura HTML, ya vinculada a `styles.css`:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Mi Perfil</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>

    <div class="perfil">

      <div class="encabezado">
        <img src="https://via.placeholder.com/120" alt="Mi foto">
        <h1>Tu Nombre</h1>
        <p class="subtitulo">Estudiante · Apasionado/a de la tecnología</p>
      </div>

      <div class="seccion">
        <h2>Sobre mí</h2>
        <p>Escribe aquí una descripción breve sobre ti, tus estudios o lo que te apasiona.</p>
      </div>

      <div class="seccion">
        <h2>Mis intereses</h2>
        <ul>
          <li>Interés 1</li>
          <li>Interés 2</li>
          <li>Interés 3</li>
        </ul>
      </div>

      <div class="seccion">
        <h2>Mis enlaces</h2>
        <a href="https://github.com" target="_blank">GitHub</a>
        <a href="https://youtube.com" target="_blank">YouTube</a>
      </div>

    </div>

  </body>
</html>
```

<br>

### Paso 2: `styles.css`

Ahora todo el estilo va en el archivo separado `styles.css`:

```css
body {
  background-color: #eef2f7;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 20px;
}

.perfil {
  background-color: white;
  border-radius: 16px;
  padding: 30px;
  max-width: 600px;
  margin: 0 auto;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.encabezado {
  text-align: center;
  margin-bottom: 30px;
}

.encabezado img {
  border-radius: 50%;
  border: 4px solid #4a90d9;
  width: 120px;
  height: 120px;
}

.encabezado h1 {
  color: #222222;
  margin: 10px 0 5px;
}

.subtitulo {
  color: #888888;
  font-size: 14px;
}

.seccion {
  margin-bottom: 25px;
}

.seccion h2 {
  color: #4a90d9;
  border-bottom: 2px solid #eef2f7;
  padding-bottom: 5px;
}

.seccion ul {
  padding-left: 20px;
}

.seccion li {
  margin-bottom: 6px;
  color: #444444;
}

.seccion a {
  display: inline-block;
  margin-right: 10px;
  padding: 8px 16px;
  background-color: #4a90d9;
  color: white;
  border-radius: 8px;
  text-decoration: none;
  font-size: 14px;
}

.seccion a:hover {
  background-color: #2a70b9;
}
```

<br>

### Paso 3: Personaliza tu página

Ahora que tienes la base, personalízala:

- Cambia el nombre, la descripción y los intereses por los tuyos.
- Reemplaza la imagen placeholder por una URL de tu foto real si tienes una.
- Cambia los colores usando valores hexadecimales que te gusten.
- Agrega más secciones si quieres, como "Mis proyectos" o "Mis habilidades".

Recuerda: esta es **tu** página. Hazla tuya.

<br>

---

## Práctica (2 min)

**🏆 Reto 6: Publica tu perfil**

Abre el JDoodle de esta lección con el starter file del proyecto.

Completa todos los TODOs:

1. Reemplaza los textos de ejemplo con tu información real.
2. Elige colores que te representen.
3. Agrega al menos 4 intereses en la lista.
4. Incluye 2 o más enlaces reales.

Presiona **Execute** y muestra el resultado.

Cuando estés satisfecho o satisfecha con tu página, **guarda el proyecto en JDoodle** y comparte el enlace con tus compañeros.

<br>

---

## Cierre (30 seg)

¡Felicitaciones!

Hoy construiste tu primera página web personal combinando HTML y CSS.

Eso es exactamente lo que hacen los desarrolladores web en el mundo real: planifican el contenido, construyen la estructura con HTML y le dan estilo con CSS.

En la última lección veremos buenas prácticas y recursos para que puedas seguir aprendiendo y mejorando por tu cuenta.

¡Nos vemos en la clase final!

<br>

---

> **Equipo PetHealt** · Universidad Peruana de Ciencias Aplicadas
> Ingeniería de Software · 1ASI0730 Aplicaciones Web · 202520