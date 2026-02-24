# Proyecto web “Vía Mariana”

[![Astro](https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build/)
[![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://www.netlify.com/)
[![Sketch](https://img.shields.io/badge/Sketch-F7B500?style=for-the-badge&logo=sketch&logoColor=white)](https://www.sketch.com/)

Proyecto web desarrollado en el contexto de las prácticas no laborales del certificado de profesionalidad **IFCD0110**. El objetivo es crear la web del proyecto **Vía Mariana**, siguiendo un flujo de trabajo guiado y utilizando herramientas y tecnologías modernas para diseño, maquetación y despliegue.

---

## Objetivos del proyecto

- Diseñar y maquetar la web del proyecto Vía Mariana (Home, Vía Mariana, Ruta, Patrimonio, Proyecto, Contacto).
- Aplicar un **kit de UI** común a todos los wireframes definidos por el equipo.
- Practicar un flujo de trabajo basado en:
  - Notion para organización, documentación y Kanban.
  - GitHub para control de versiones y revisión de código.
  - Astro + Netlify para desarrollo y despliegue estático.

---

## Tecnologías previstas

- **Astro**: framework para generación de sitios estáticos y componentes modernos.
- **HTML / CSS**: estructura y estilos base, siguiendo la guía de diseño del proyecto.
- **Sketch**: diseño de UI y prototipos visuales (wireframes y maquetas).
- **Netlify**: despliegue continuo y hosting del sitio.
- **Git / GitHub**: control de versiones, ramas de feature y Pull Requests.

---

## Flujo de trabajo

### Organización del proyecto

- **Notion**
  - Página “Vía Mariana – Documentación”: información del proyecto, acuerdos, actas, archivos incrustados.
  - Página “Vía Mariana – Diseño UI”: kit de UI, referencias de diseño y enlaces a Sketch.
  - Base de datos “Tareas Vía Mariana”: Kanban con estados `Pendiente`, `En curso`, `En revisión`, `Hecho`.

- **Sketch**
  - Diseño de elementos de UI y secciones.
  - [Ver el diseño UI](https://sketch.com/s/942353ed-d8a1-434a-a536-ae6919726686)

- **GitHub**
  - Rama principal protegida (`main`).
  - Desarrollo en ramas de feature: `feature/ui-home`, `feature/page-ruta`, etc.
  - Cambios integrados mediante Pull Requests revisados por el tutor.

### Fases del trabajo

1. **Definición y diseño**
   - Investigación y contenidos.
   - Wireframes de todas las páginas.
   - Creación y aplicación del kit de UI sobre los wireframes.

2. **Maquetación con Astro**
   - Configuración del proyecto Astro.
   - Implementación de layout base y componentes reutilizables.
   - Integración de contenidos definitivos.

3. **Responsive, accesibilidad y SEO básico**
   - Ajustes para móvil y tablet.
   - Alt en imágenes, jerarquía de encabezados, contraste, títulos y metadescripciones.

4. **Pruebas, documentación y despliegue**
   - Tests manuales en distintos navegadores.
   - Documentación del proyecto (estructura, tecnologías, decisiones).
   - Despliegue en Netlify.

---

## Estructura inicial del repositorio

La estructura puede evolucionar, pero el punto de partida previsto es:

```bash
/
├─ public/              # Recursos estáticos (imágenes, etc.)
├─ src/
│  ├─ components/       # Componentes compartidos (header, footer, cards, etc.)
│  ├─ layouts/          # Layouts generales de página
│  ├─ pages/            # Páginas del sitio (Astro)
│  └─ styles/           # Hojas de estilo globales / parciales
├─ README.md
└─ astro.config.mjs
