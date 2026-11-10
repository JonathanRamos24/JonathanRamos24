# ESCUELA SUPERIOR POLITÉCNICA DEL LITORAL
## FACULTAD DE INGENIERÍA EN ELECTRICIDAD Y COMPUTACIÓN

**Fecha:** 9 de noviembre de 2026  
**Materia:** Desarrollo de Aplicaciones Web y Móviles (SOFG1006)  
**Proyecto:** Proyecto 01: Identidad digital del desarrollador (Fase 1: Análisis)  
**Estudiante:** Ramos Macías Jonathan David  

---

## 1. Análisis

Antes de armar mi perfil revisé cómo otros desarrolladores se presentan en GitHub. Escogí tres perfiles de la lista *awesome-github-profile-readme* [1] que tienen estilos bastante distintos entre sí: uno minimalista, uno muy corto y uno cargado de imágenes.

### 1.1 Perfiles de referencia

#### Tabla 1: Comparación de perfiles de GitHub

| Criterio | Nate Moore ([natemoo-re](https://github.com/natemoo-re)) | Gift Egwuenu ([lauragift21](https://github.com/lauragift21)) | Waylon Walker ([WaylonWalker](https://github.com/WaylonWalker)) |
| :--- | :--- | :--- | :--- |
| **Presentación** | En 10 segundos se entiende quién es: Design Engineer en Sentry y cocreador de Astro. Lo dice en el segundo párrafo con enlaces. | Muy clara: nombre en el título y "software engineer and developer advocate" en la primera línea. | El nombre está dentro de una imagen (banner). Hay que leer el párrafo para saber que escribe sobre Python y data engineering. |
| **Estructura** | Título, una frase destacada, tres párrafos, botón de sponsor y una tabla con la música que escucha. Pocas secciones. | Título centrado, fila de enlaces, dos párrafos y una lista corta de contacto. Es el más corto de los tres. | Banner, íconos de redes, saludo, "Boy Scout Rule", "My Digital Garden", seguidores y stargazers. Muchas secciones y poca jerarquía. |
| **Habilidades** | No hay lista; se deducen de lo que ha hecho (Astro, Microsite, herramientas CLI). Son verificables porque enlaza los repos. | No las muestra. Solo menciona sitios accesibles y comunidad. | En texto: **python** y **javascript** en negrita dentro de un párrafo. No usa insignias. |
| **Proyectos** | Fija astro, clack, microsite, compiler, ultrahtml y micromorph. En el README los describe dentro del texto. | Fija 6 repos (talleres y recursos), pero el README no habla de ninguno. | Fija markata-py, devtainer, find-kedro, entre otros. El README no los describe, solo enlaza a su blog. |
| **Contacto** | Casi no hay: solo el enlace de sponsor. | Lo mejor del perfil: Website, X, LinkedIn, YouTube arriba y correo al final. | Íconos de dev.to, Twitter, Instagram, LinkedIn y Buy me a coffee al inicio. |
| **Accesibilidad y móvil** | Las imágenes de "Now Playing" no tienen texto alternativo y dependen de un servicio externo (status.nmoo.dev). El texto se lee bien en móvil. | Al ser solo texto se lee bien en cualquier pantalla y no depende de nada externo. | Los íconos de redes no tienen texto alternativo, varias imágenes vienen de su página y una imagen mide 800 px de ancho. Además el enlace `[waylonwalker.com](waylonwalker.com)` está mal escrito y no abre la página. |

**Lo que me llevo:** la claridad de lauragift21 en la presentación y el contacto, y la forma de natemoo-re de demostrar habilidades con proyectos reales en lugar de una lista de logos. De WaylonWalker aprendí lo que no quiero: depender de imágenes externas y llenar el perfil de secciones que no dicen nada del desarrollador.

### 1.2 Repositorios de referencia

Revisé un repositorio fijado de cada perfil con la API de GitHub.

#### Tabla 2: Revisión de repositorios fijados

| Criterio | [withastro/astro](https://github.com/withastro/astro) | [bombshell-dev/clack](https://github.com/bombshell-dev/clack) | [WaylonWalker/markata-py](https://github.com/WaylonWalker/markata-py) |
| :--- | :--- | :--- | :--- |
| **Descripción, topics y demo** | "The web framework for content-driven websites", 11 topics y enlace a astro.build. | "Effortlessly build beautiful command-line apps", 6 topics y enlace a su documentación. | Descripción larga, 4 topics y enlace a markata.dev. |
| **README** | Banner, insignias, Install, Documentation, Support, Contributing y una tabla con todos los paquetes. | Casi solo el logo; la explicación está en el README de cada paquete. | QuickStart, instalación, un GIF que muestra cómo crear un blog, motivación y galería de ejemplos. |
| **Licencia y .gitignore** | Sí tiene LICENSE (MIT según su insignia) y .gitignore. | Sí tiene LICENSE y .gitignore. | Licencia MIT y .gitignore, además de CHANGELOG y CODE_OF_CONDUCT. |
| **Commits** | Varios por día. Mensajes en imperativo con el número del PR: "Fix static build skipping pages…". | Varios por semana y con Commits Convencionales: `fix(prompts): handle trailing backslash…`. | Poco frecuentes (meses entre algunos). Mezcla `docs:` y `chore(python):` con "Bump version". |
| **Issues, PR, ramas y releases** | 148 abiertos, más de 11 000 PR, unas 390 ramas, release astro@7.4.8. | 93 abiertos, unos 410 PR, 33 ramas, release @clack/prompts@1.9.0. | 22 abiertos, unos 130 PR, 54 ramas, release v0.11.0.dev11. |
| **Carpetas** | Ordenadas: packages, examples, scripts, configs. | packages y examples. | markata, docs, tests y static. |

### 1.3 Mis propios repositorios

Apliqué la misma revisión a mis repositorios públicos. El problema principal es que mis proyectos más importantes (aLata, Doxi, SOAC y Brokeate) están en repositorios privados porque son de empresa o de clientes, así que en el perfil voy a enlazar a sus demos y tiendas.

#### Tabla 3: Estado de mis repositorios públicos

| Repositorio | Descripción y topics | README | Licencia | Commits | Qué le falta |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Proyecto_DAWM_2 | No | Sí, completo | Sí | Mensajes descriptivos, algunos con `docs:` | Descripción, topics y enlace a GitHub Pages en el "About". |
| Proyecto_Analizador_Lexico_LP | No | Solo el título | No | Descriptivos | Descripción, README con uso y licencia. |
| Proyecto-EDD-Grupo-10 | No | Solo el título | No | Solo "Initial commit" | Prácticamente todo. |
| ProyectoPOO | No | No tiene | No | "Proyecto Completo" | README, .gitignore (subió .vscode) y mensajes claros. |
| Proyecto-Base-de-Datos- | No | No tiene | No | "Cambios nuevos" | README y mensajes que digan qué cambió. |

### 1.4 Requisitos de mi perfil

**Requisitos funcionales**

- **RF1.** Mostrar mi nombre, que estudio Computación en la ESPOL y que trabajo como desarrollador full stack en Dox S.A.
- **RF2.** Tener una sección corta "Sobre mí".
- **RF3.** Mostrar mis habilidades agrupadas (IA, backend, frontend y herramientas), solo las que he usado en proyectos.
- **RF4.** Mostrar mis proyectos destacados con nombre, problema que resuelve, tecnologías, funcionalidades y enlaces.
- **RF5.** Mostrar mi experiencia laboral y académica.
- **RF6.** Tener los canales de contacto a la vista: correo, LinkedIn y portafolio.

**Requisitos no funcionales**

- **RNF1. Legibilidad:** que en las primeras tres líneas se entienda quién soy y qué hago.
- **RNF2. Formato:** escrito solo con Markdown, sin HTML ni CSS.
- **RNF3. Accesibilidad:** sin imágenes con información importante; si hay una imagen, debe tener texto alternativo.
- **RNF4. Móvil:** tablas de pocas columnas y nada que obligue a hacer scroll horizontal.
- **RNF5. Mantenibilidad:** secciones independientes para poder actualizar una sin tocar las demás, con un commit por cambio.
- **RNF6. Veracidad:** todo lo que diga debe poder comprobarse con un enlace.

---

## Referencias

[1] Abhisheknaiidu. (s.f.). *awesome-github-profile-readme*. GitHub. https://github.com/abhisheknaiidu/awesome-github-profile-readme
