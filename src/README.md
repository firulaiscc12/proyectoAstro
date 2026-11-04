# Curriculum

Web personal de currículum / portfolio hecha con [Astro](https://astro.build). Presenta mi experiencia, proyectos, formación y datos de contacto en una sola página, dividida en componentes con HTML y CSS básico.

## Secciones

- **Barra de menú y portada**: presentación inicial.
- **Experiencia**: trabajos y prácticas realizados.
- **Proyectos**: tarjetas con título, descripción, imagen y enlace.
- **Formación**: estudios cursados y en curso.
- **Sobre mí**: texto de presentación y tarjeta personal.
- **Contacto**: datos de contacto y pie de página.

## Estructura del proyecto

```text
/
├── public/                  # favicon
├── src/
│   ├── assets/              # imágenes
│   ├── components/          # un componente por parte de cada sección
│   ├── data/                # contenido en JSON
│   │   ├── experiencia.json
│   │   ├── formacion.json
│   │   └── proyectos.json
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro      # página principal que une todos los componentes
├── astro.config.mjs
└── package.json
```

## Tecnologías

- Astro
- HTML y CSS (estilos dentro de cada componente con `<style>`)
- Datos en archivos JSON

## Cómo ejecutarlo

Necesitas Node.js 22.12.0 o superior.

```sh
npm install
npm run dev
```

Después abre `http://localhost:4321` en el navegador.

## Comandos

| Comando           | Acción                                        |
| :---------------- | :-------------------------------------------- |
| `npm install`     | Instala las dependencias                      |
| `npm run dev`     | Arranca el servidor local en `localhost:4321` |
| `npm run build`   | Genera la web final en `./dist/`              |
| `npm run preview` | Previsualiza la build en local                |

## Autor

Dani — estudiante de 2.º de Desarrollo de Aplicaciones Web (Santa Joaquina de Vedruna).