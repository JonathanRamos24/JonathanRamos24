# ESCUELA SUPERIOR POLITÉCNICA DEL LITORAL
## FACULTAD DE INGENIERÍA EN ELECTRICIDAD Y COMPUTACIÓN

**Fecha:** 9 de noviembre de 2026  
**Materia:** Desarrollo de Aplicaciones Web y Móviles (SOFG1006)  
**Proyecto:** Proyecto 01: Identidad digital del desarrollador (Fase 2: Planificación y Diseño)  
**Estudiante:** Ramos Macías Jonathan David  

---

## 2. Planificación y Diseño

### 2.1 Estructura del README

Con lo que salió del análisis, el perfil va a tener seis secciones en este orden. Dejé fuera "Áreas de interés" porque se repetía con "Sobre mí".

#### Tabla 4: Secciones del perfil

| # | Sección | Para qué sirve | Formato |
| :--- | :--- | :--- | :--- |
| 1 | Presentación | Que en una línea se sepa quién soy (RF1, RNF1). | Título y una línea de texto. |
| 2 | Sobre mí | Contar qué hago y qué tipo de proyectos construyo (RF2). | Un párrafo corto. |
| 3 | Habilidades y tecnologías | Mostrar con qué trabajo (RF3). | Lista por grupos, en texto y sin insignias. |
| 4 | Proyectos destacados | Mostrar lo que he construido (RF4). | Una ficha por proyecto. |
| 5 | Experiencia | Trabajo y estudios (RF5). | Lista. |
| 6 | Contacto | Que sea fácil escribirme (RF6). | Lista de enlaces. |

### 2.2 Diseño del contenido

| Sección | Qué incluir | Qué evitar | Enlaces |
| :--- | :--- | :--- | :--- |
| Presentación | Nombre, carrera y trabajo actual. | Frases genéricas ("apasionado por la tecnología"). | ESPOL y Dox S.A. |
| Sobre mí | Qué tipo de sistemas he hecho. | Contar mi vida o poner datos personales. | Ninguno. |
| Habilidades | Solo lo que usé en proyectos reales. | Insignias de colores e imágenes externas (problema visto en WaylonWalker). | Ninguno. |
| Proyectos | Las fichas de abajo. | Proyectos sin terminar o sin forma de comprobarlos. | Demo o tienda de cada uno. |
| Experiencia | Empresa, cargo, años y qué hago. | Cursos sin relación. | Dox S.A. |
| Contacto | Correo, LinkedIn y portafolio. | Teléfono o WhatsApp (por spam). | Los tres. |

Para la lectura rápida: títulos de nivel 2 por sección, listas en lugar de párrafos largos, la tecnología en *cursiva* debajo de cada proyecto y nada de imágenes para información importante (RNF3).

### 2.3 Fichas de proyectos destacados

Mis proyectos principales están en repositorios privados (son de la empresa o de clientes), por eso en "Repositorio" pongo eso y enlazo a la demo o a la tienda.

#### Tabla 5: Fichas de proyectos

| Campo | aLata | Doxi | Brokeate | SOAC |
| :--- | :--- | :--- | :--- | :--- |
| **Problema** | Los estudiantes universitarios no tienen cómo compartir el carro con alguien que va por su misma ruta. | Los negocios no alcanzan a responder a sus clientes en todos los canales. | Invertir sin asesoría cuesta y es difícil saber qué perfil de riesgo tienes. | Un consultorio odontológico llevaba pacientes, citas y facturas por separado. |
| **Tecnologías** | React Native, Node.js, PostgreSQL, Redis, Socket.io | Node.js, React, PostgreSQL, Redis, API de Claude, API de Meta, Twilio, Stripe | React Native, FastAPI, Supabase, LangGraph | React, TypeScript, Node.js, PostgreSQL, Docker |
| **Funcionalidades** | Carpooling en todo Ecuador; el pasajero sube solo en paradas de la ruta; avisa cuando aparece alguien por tu camino. | Agentes de IA que atienden, agendan citas y venden por WhatsApp, Instagram, Messenger y web; pasan la conversación a una persona cuando hace falta. | Arma un portafolio según tu perfil de riesgo; un asesor humano aprueba cada propuesta; ganó el Agentic Scale Hackathon. | Historia clínica con odontograma, agenda, cotizaciones, inventario y facturación electrónica del SRI. |
| **Repositorio** | Privado | Privado | Privado | Privado |
| **Demo** | [alata-ec.com](https://alata-ec.com), Google Play y App Store | [ai-bots.us](https://ai-bots.us) | [Devpost](https://devpost.com/software/brokeate) | No tiene (uso interno del consultorio) |

### 2.4 Estrategia de commits

Voy a seguir Commits Convencionales [1], con un commit por sección para que el historial muestre cómo se armó el perfil:

1. `docs: agrega análisis de perfiles y repositorios de referencia` (Fase 1)
2. `docs: agrega estructura y fichas de proyectos del perfil` (Fase 2)
3. `feat: agrega presentación y sección sobre mí` (Fase 3)
4. `feat: agrega habilidades y tecnologías`
5. `feat: agrega proyectos destacados con enlaces a demos`
6. `feat: agrega experiencia y contacto`
7. `docs: agrega enlace del sitio publicado` (Fase 4)

---

## Referencias

[1] Commits Convencionales. (s.f.). *Commits Convencionales 1.0.0-beta.2*. https://www.conventionalcommits.org/es/v1.0.0-beta.2/
