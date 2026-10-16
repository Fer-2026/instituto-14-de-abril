# Instituto Cooperativo 14 de Abril: maquetación web

Sitio estático de 10 vistas para el **Instituto Cooperativo 14 de Abril** (Salta): Educación Secundaria, turno mañana, 1.º a 5.º año, orientación en Ciencias Naturales.

- **Sitio en vivo:** https://Fer-2026.github.io/instituto-14-de-abril/
- **Repositorio:** https://github.com/Fer-2026/instituto-14-de-abril
- **Redes:** [Facebook](https://share.google/0eQSeQQhdelOzPzhW)

## Tecnologías
HTML5, Bootstrap 5.3 (CDN), CSS propio (`css/styles.css`), JavaScript mínimo (`js/main.js`), Prettier, Lighthouse.

## Estructura
```
index.html ... contacto.html   10 vistas
css/  js/  img/                recursos
docs/accesibilidad-lighthouse.md
```

## Vistas
1. [Inicio](index.html)
2. [Institucional](institucional.html)
3. [Propuesta educativa](propuesta-educativa.html)
4. [Plan de estudios](plan-de-estudios.html)
5. [Ciencias Naturales](ciencias-naturales.html)
6. [Inscripción](inscripcion.html)
7. [Equipo docente](docentes.html)
8. [Agenda 2026](agenda.html)
9. [Galería](galeria.html)
10. [Contacto](contacto.html)

## Flujo de trabajo
1. `git init` y estructura base.
2. Rama `feature/maquetacion`.
3. Maquetación + Bootstrap.
4. Prettier (`npm run format`) y auditoría: ver [docs/accesibilidad-lighthouse.md](docs/accesibilidad-lighthouse.md).
5. Push y Pull Request a `main`.
6. Merge.
7. Deploy en GitHub Pages (Settings, Pages, rama `main`, carpeta `/root`).

## Uso local
```
npm install
npm run format
```
Abrí `index.html` en el navegador (o usá Live Server).

## Fuentes y aclaraciones
- Datos del instituto (dirección, teléfonos, correos, título de Bachiller en Ciencias Naturales): sitios públicos, documentos del instituto y su perfil de Instagram. Confirmar que estén vigentes.
- Agenda: PDF institucional 2026 del instituto.
- **Los nombres del equipo docente son ficticios** (solo para la maqueta).
- Las fotos son marcadores: usar solo imágenes con autorización del instituto.

