# Science's Women

## Tabla de contenidos

1. [Descripción del proyecto](#1-descripción-del-proyecto)
2. [Objetivos](#2-objetivos)
3. [Roadmap](#3-roadmap)
4. [Stack tecnológico](#4-stack-tecnológico)
5. [Instalación y ejecución](#5-instalación-y-ejecución)
6. [Estructura del proyecto](#6-estructura-del-proyecto)
7. [Contribución](#7-contribución)

## 1. Descripción del proyecto

Science's women es un proyecto dedicado a visibilizar a mujeres que han destacado en el mundo de la ciencia a lo largo de la historia y en la actualidad. Es un proyecto en desarrollo contínuo, que irá de menos a más, empezando con un código solo basado en HTML y CSS, y que irán sumando otros lenguajes de programación, librerías y frameworks, añadiendo bases de datos,... Esta idea nació viendo una publicación de Facebook del Telecentro de Luiña (Ibias, Asturias), de una noticia del día internacional de la mujer y la niña en la ciencia, que se celebra el 11 de febrero. A partir de ese día empezó la idea de unir pasiones como son la historia, la ciencia y la programación web.

## 2. Objetivos

- **Visibilización**: Proporcionar referentes femeninos en ciencia mediante contenido accesible.
- **Evolución técnica**: Implementar un enfoque de desarrollo iterativo, incorporando progresivamente nuevas tecnologías y patrones de arquitectura.
- **Calidad de código**: Aplicar buenas prácticas de desarrollo: versionado con Git, diseño responsive, accesibilidad web (WCAG), testing y documentación técnica.

## 3. Roadmap

### Fase 1: Maquetación estática (Actual)
- HTML5 semántico y CSS3
- Diseño responsive
- Accesibilidad: semántica HTML, contraste de colores, navegación por teclado, etiquetas ARIA

### Fase 2: Interactividad
- JavaScript vanilla para funcionalidades de búsqueda y filtrado
- Componentes reutilizables y manipulación del DOM

### Fase 3: Framework frontend
- Migración a framework React con TypeScript
- Arquitectura de componentes
- Gestión de estado con librerías especializadas (Redux, Zustand, etc.)

### Fase 4: Backend y API
- Implementación de servidor (Node.js/Express)
- API RESTful para servir contenido dinámico
- Autenticación y autorización (si aplica)

### Fase 5: Base de datos y despliegue
- Modelado de datos e implementación de base de datos (PostgreSQL, MongoDB, etc.)
- CI/CD pipeline
- Despliegue en producción (Vercel, Netlify, AWS, etc.)

## 4. Stack tecnológico

### Lenguajes y estándares
- **HTML5**: Estructura semántica del documento
- **CSS3**: Estilos, layout (Flexbox/Grid), animaciones y diseño responsive

### Herramientas de desarrollo
- **Git**: Control de versiones distribuido
- **GitHub**: Repositorio remoto y gestión de issues/PRs
- **Visual Studio Code**: Editor de código fuente

### Gestión de proyecto (opcional)
- **Figma**: Diseño de interfaces y prototipado
- **Jira**: Seguimiento de tareas y sprints

## 5. Instalación y ejecución

### Requisitos previos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Git (para clonar el repositorio)
- Node.js y npm (opcional, para servidor de desarrollo)

### Ejecución local

1. **Clonar el repositorio**:
   ```bash
   git clone <repository-url>
   cd "Science's women"
   ```

2. **Opción A: Abrir directamente**:
   ```bash
   # Abre index.html directamente en el navegador
   ```

## 6. Estructura del proyecto

```
Science's women/
├── assets/
│   └── images/
│       └── women/          # Imágenes de perfil de las científicas
├── css/
│   ├── colors.css          # Variables y paleta de colores
│   ├── common.css          # Estilos globales y resets
│   ├── flip-card.css       # Estilos del componente tarjeta
│   ├── footer.css          # Estilos del footer
│   ├── header.css          # Estilos del header
│   ├── section.css         # Estilos de secciones
│   └── styles.css          # Archivo principal de estilos (imports)
├── index.html              # Punto de entrada de la aplicación
└── README.md               # Documentación del proyecto
```

## 7. Contribución

### Proceso de contribución

1. **Reportar issues**: Abre un issue describiendo el problema o mejora propuesta
2. **Fork y rama**: Haz fork del repositorio y crea una rama descriptiva (`git checkout -b feature/nueva-funcionalidad`)
3. **Desarrollo**: Implementa los cambios siguiendo las convenciones del proyecto
4. **Commit**: Realiza commits descriptivos siguiendo convenciones de mensajes (p. ej., Conventional Commits)
5. **Pull Request**: Envía un PR con descripción clara de los cambios y referencias a issues relacionados

### Guías de estilo
- Usar indentación consistente (espacios o tabs según estándar del proyecto)
- Comentar código complejo
- Mantener accesibilidad y semántica HTML
- Asegurar compatibilidad cross-browser
