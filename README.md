# 🌸 OrquideaFit | Plataforma Frontend de Salud y Bienestar

![Estado](https://img.shields.io/badge/Estado-Completado-success)
![Tecnología](https://img.shields.io/badge/HTML5-Semántico-E34F26?logo=html5)
![Tecnología](https://img.shields.io/badge/CSS3-Animaciones-1572B6?logo=css3)
![Framework](https://img.shields.io/badge/Bootstrap-5.3-7952B3?logo=bootstrap)

**OrquideaFit** es una Landing Page interactiva diseñada para centralizar herramientas de bienestar holístico y fitness. El proyecto destaca por su rigor en el diseño de interfaces (UI/UX), accesibilidad web (WCAG) y una arquitectura CSS escalable basada en el diseño "Z-Pattern".

---

## 🚀 Funcionalidades Principales

El proyecto se divide en una metodología introductoria y tres herramientas interactivas aisladas visualmente para maximizar la experiencia de usuario:

1. **Calculadora de Inteligencia Metabólica (TDEE):** Formulario optimizado con estados de *focus* accesibles para calcular requerimientos calóricos basados en datos biométricos.
2. **Temporizador de Hipopresivos:** Interfaz limpia estilo *dashboard* con tipografía tabular (`tabular-nums`) para evitar vibraciones visuales durante el conteo, integrando barras de progreso semánticas.
3. **Registro de Actividad:** Módulo de historial que simula el ingreso de datos (CRUD visual), utilizando jerarquía de datos mediante insignias (`badges`) y estados interactivos en filas de tablas.

---

## 🛠️ Tecnologías y Prácticas de Ingeniería

Este proyecto fue desarrollado cumpliendo estrictos estándares web:

* **HTML5 Semántico:** Uso correcto de `<header>`, `<main>`, `<section>`, `<article>` y `<nav>` para garantizar una correcta indexación y lectura por tecnologías de asistencia.
* **Sistema de Diseño en CSS3:**
  * Uso intensivo de **Custom Properties (Variables)** para mantener consistencia estricta en la paleta de colores (Lilas, Rosas Vibrantes y Blancos Rotos).
  * **Animaciones y Transiciones Clave:** Implementación de `@keyframes` para elementos flotantes (Hero Section) y micro-interacciones suaves (`cubic-bezier`) en tarjetas y botones.
  * Sombras dinámicas (`drop-shadow` sobre imágenes PNG transparentes vs `box-shadow` en contenedores).
* **Framework Responsivo:** Integración de **Bootstrap 5.3** modificando sus variables por defecto para evitar diseños genéricos y forzar la identidad de marca de OrquideaFit.
* **Accesibilidad (A11y & WCAG AA):**
  * Contraste riguroso entre fondos oscuros y tipografías claras.
  * Estados de navegación accesibles por teclado (delineado de focus personalizado).
  * Uso de atributos `aria-label` y roles en formularios y temporizadores.

---

## 📂 Estructura del Proyecto

```text
/
├── index.html       # Estructura principal y maquetación semántica
├── styles.css       # Sistema de diseño, variables y animaciones
└── img/             # Assets estáticos (Logotipo, renders 3D optimizados, favicon)
    ├── logo-orquidea.png
    ├── favicon.png
    └── ...


Autora
Amanda
Estudiante de Ingeniería en Informática | INACAP (2026)

Desarrollado como proyecto evaluativo de Frontend, demostrando el dominio en la construcción de interfaces modernas, control de versiones mediante commits atómicos y aplicación de heurísticas de usabilidad.