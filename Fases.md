# Evidencia de Fases de Desarrollo - Proyecto 01: Portafolio de Identidad Digital

**Desarrollador:** Luis Alejandro Mendoza Placencia  
**Usuario de GitHub:** [luis86129](https://github.com/luis86129)  
**Asignatura:** Desarrollo de Aplicaciones Web y Móviles (DAWM)  
**Institución:** Escuela Superior Politécnica del Litoral (ESPOL)  
**URL de despliegue (GitHub Pages):** `https://luis86129.github.io/luis86129/`

---
## 📍 Fase 1: Analisis

### 1.1 Análisis Comparativo de Perfiles de Referencia
A partir de la lista curada en *Abhisheknaiidu/awesome-github-profile-readme*, se seleccionaron 3 categorías y perfiles representativos para evaluar patrones de visualización, estructura, accesibilidad y experiencia de usuario:

| Criterio de Análisis | Perfil 1: Categoría Minimalistic (*Sindre Sorhus / Gift Egwuenu*) | Perfil 2: Categoría Dynamic Realtime (*Anurag Hazra / DenverCoder1*) | Perfil 3: Categoría Game Mode (*Kavish Hukmani / Tim Burgan*) |
| :--- | :--- | :--- | :--- |
| **Presentación (primeros 10s)** | Inmediata y concisa. Se comprende el rol y propósito del desarrollador mediante texto enriquecido y jerarquía limpia. | Altamente dinámica. Capta la atención al instante mediante tarjetas de estadísticas en tiempo real y gráficos SVG. | Visual e interactiva. Presenta banners animados, estética retro/gaming y estructuras tipo portafolio. |
| **Estructura y Jerarquía** | Lineal y directa: Saludo → Breve bio → Proyectos destacados → Canales de contacto. | Modular por bloques: Banner → Wakatime/GitHub Stats → Tech Stack → Social Links. | Compleja y personalizada: Header interactivo → Bio estructurada → Projects Grid → Badges. |
| **Habilidades** | Listas de texto plano formateadas con Markdown o viñetas simples. | Insignias vectoriales dinámicas con la API de *Shields.io* e iconos de *Simple Icons*. | Insignias personalizadas con animaciones en SVG o elementos gráficos estilo retro. |
| **Proyectos** | Lista organizada de repositorios fijados (*pinned repos*) con descripciones textuales. | Tarjetas embebidas de repositorios con contadores automáticos de *stars* y *forks*. | Fichas detalladas con capturas, GIFs demostrativos y enlaces a demos o despliegues. |
| **Contacto** | Correo o sitio web mediante hipervínculos sutiles al final del documento. | Badges interactivos tipo botón con hipervínculos a redes profesionales (LinkedIn, Twitter). | Botones estilizados con colores corporativos e iconos de contacto directos. |
| **Accesibilidad y Lectura en Móvil** | **Alta.** 100% de compatibilidad en móviles y lectores de pantalla al no depender de servidores externos. | **Media.** Las tarjetas externas SVG (*github-readme-stats*) pueden fallar si hay latencia de red. | **Media-Baja.** El peso de animaciones SVG y GIFs puede demorar la carga en conexiones móviles. |

### 1.2 Requisitos Funcionales y No Funcionales

- **Requisitos Funcionales:**
  - Exponer la información académica relevante del estudiante (Carrera: Ingeniería en Computación en ESPOL) resguardando datos personales sensibles (teléfono, cédula o dirección exacta).
  - Incluir una sección dedicada a **Proyectos** con al menos 2 trabajos prácticos, detallando descripción, tecnologías y enlace a repositorio.
  - Incluir una sección de **Tecnologías y Herramientas** aprendidas en el curso y su aplicación práctica.
  - Proveer canales formales de contacto profesional.

- **Requisitos No Funcionales:**
  - **Accesibilidad y Portabilidad:** Uso de Markdown estándar y maquetación responsiva compatible con GitHub Pages y navegadores móviles.
  - **Mantenibilidad:** Historial de cambios registrado mediante la convención de *Conventional Commits*.

---

## 📍 Fase 2: Diseño y Planificación

### 2.1 Esquema Visual del `README.md`
La arquitectura de la información se organizó de la siguiente manera:
1. **Encabezado y Presentación Profesional:** Saludo, nombre, rol y universidad.
2. **Sobre Mí:** Enfoque técnico y áreas de interés.
3. **Tecnologías y Herramientas Aprendidas:** Tabla técnica categorizada con aplicaciones en proyectos del curso.
4. **Proyectos Destacados (Fichas Técnicas):** Tres repositorios con problemas resueltos, stack técnico y enlaces.
5. **Canales de Contacto:** Enlaces directos a perfiles profesionales.

### 2.2 Estrategia de Versionado (*Conventional Commits*)
Para garantizar que la evolución del perfil quede respaldada en el historial de Git, se definieron los siguientes mensajes estandarizados:

```bash
docs: inicializa estructura base de README.md y Fases.md
feat: agrega seccion de presentacion academica y sobre mi
feat: incorpora tabla de tecnologias aprendidas y su aplicacion en DAWM
feat: incluye fichas tecnicas de los 3 proyectos destacados con repositorios
fix: corrige hipervinculos de repositorios y valida marcado Markdown
docs: actualiza URLs de despliegue en GitHub Pages
