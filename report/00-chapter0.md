<div align="center">

<p align="center"><img src="https://github.com/user-attachments/assets/246a4dfb-6dd5-4909-a472-6cdce8319986" width="300"/></p>

<p align="center">Universidad Peruana de Ciencias Aplicadas</p>

<p align="center">Carrera de Ingeniería de Software</p>

<p align="center"><strong>1ASI0729</strong></p>

<p align="center"><strong>Desarrollo de Aplicaciones Open Source</strong></p>

<p align="center">NRC</p>

<p align="center"><strong>11881</strong></p>

<p align="center"><strong>Informe del Trabajo Final</strong></p>

<p align="center">Docente</p>

<p align="center"><strong>Bautista Ubillús, Efraín Ricardo</strong></p>

<p align="center">Equipo</p>

<p align="center"><strong>SpotTrack</strong></p>

<p align="center">Proyecto</p>

<p align="center"><strong>SpotTrack</strong></p>

<p align="center"><strong>Integrantes</strong></p>

<table>
  <thead>
    <tr><th>Código</th><th>Apellidos y Nombres</th></tr>
  </thead>
  <tbody>
    <tr><td>u202411310</td><td>Azama Fukuda, Juan Pablo</td></tr>
    <tr><td>u202414928</td><td>Fernández Linares, Alvaro Sebastian</td></tr>
    <tr><td>u202410344</td><td>Espinoza Orrego, Valentino Andre</td></tr>
    <tr><td>u20241a860</td><td>Limache Coronel, Imanol Fabrizio</td></tr>
  </tbody>
</table>


<br>

<p align="center"><strong>Período 202610</strong></p>

<p align="center"><strong>Julio 2026</strong></p>

</div>

---

\newpage

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|--------|------|------|-----------------------------|
|1.0.0 | 25/04/26 | Azama, Espinoza, Fernández | Se realizaron todos los incisos realizados a Lean UX, Needfidining, UI/UX Design y DDD|
|2.0.0 | 10/05/26 | Azama, Espinoza, Fernández | Se completó el despliegue de la Landing Page en GitHub Pages con todas sus secciones (Hero, Features, Pricing, Contact, Footer). Se implementó el desarrollo frontend de la Web Application en Angular con Fake RESTful API (JSON Server desplegado en Azure), cubriendo los bounded contexts de Equipment, IoT Monitoring, Heatmap, Authentication, Maintenance, Analytics, Routines y Booking. Se documentó el Sprint 2 Planning, Aspect Leaders, Sprint Backlog, Development Evidence, Services Documentation y Software Deployment Evidence. Se aplicó la corrección de artefactos pendientes del Sprint 1, incluyendo diagrama ERD, diagrama de clases, Big Picture EventStorming, evidencias de colaboración y estandarización de entrevistas. Se incorporaron las secciones de Conclusiones y Recomendaciones para ambos sprints. |
|3.0.0 | 19/06/26 | Azama, Espinoza, Fernández | Se implementó el desarrollo backend de la Web Application con Spring Boot, conectando los servicios reales a las vistas Angular desarrolladas en el Sprint 2. Se desplegó una nueva versión de la Landing Page con mejoras de contenido y se actualizó el frontend con las correcciones pendientes del Sprint 2. Se realizaron entrevistas de validación con representantes de ambos segmentos objetivo (administradores y clientes de gimnasio). Se documentó el Sprint 3 Planning, Aspect Leaders, Sprint Backlog, Development Evidence, Validation Interviews y Software Deployment Evidence. Se incorporaron las Conclusiones y Recomendaciones del Sprint 3. |
|4.0.0 | 05/07/26 | Azama, Limache, Espinoza, Fernández | Se completó el modelo de negocio SaaS con la integración de Stripe (suscripción, pago y facturación de membresías), el onboarding multi-gimnasio y la ampliación de la red de sensores IoT junto con el Centro de Alertas unificado. Se incorporó al equipo Limache Coronel, Imanol Fabrizio para reforzar el desarrollo del sprint final. Se documentó el Sprint 4 Planning, Aspect Leaders, Sprint Backlog, Development Evidence, Execution Evidence, Services Documentation y Software Deployment Evidence, junto con los nuevos User Stories y Technical Stories del Capítulo III. Se desplegó la versión final de los tres productos digitales (Landing Page, Web Application y Backend API) en producción. |

---



## Project Report Collaboration Insights

URL del Repositorio spottrack-report: (https://github.com/SpotTrack-1ASI0729-2610-11881/spottrack-report.git)

Esta sección presenta los analíticos de colaboración y commits en GitHub del repositorio del Project Report (`spottrack-report`), evidenciando la participación de todos los miembros del equipo en la elaboración del informe a lo largo de las entregas, en coherencia con el Registro de Versiones del Informe. Los analíticos de colaboración de los repositorios de implementación (Landing Page, Web Application y Platform) se documentan en la sección *Team Collaboration Insights* de cada Sprint del Capítulo V.

**Sprints 1 y 2**

![](../assets/Insights/report.png)

**Sprint 3**

![](../assets/Insights/sprint3/report-insights.png)

**Sprint 4**

![](../assets/Insights/sprint4/report-insights.png)

---




<nav id="TOC">

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#startup-profile)
    - [1.1.1. Descripción de la Startup](#descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#solution-profile)
    - [1.2.1. Antecedentes y problemática](#antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#lean-ux-canvas)
  - [1.3. Segmentos objetivo](#segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation-analysis)
  - [2.1. Competidores](#competidores)
    - [2.1.1. Análisis competitivo](#análisis-competitivo-1)
    - [2.1.2. Estrategias y tácticas frente a competidores](#estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#entrevistas)
    - [2.2.1. Diseño de entrevistas](#diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#análisis-de-entrevistas)
  - [2.3. Needfinding](#needfinding)
    - [2.3.1. User Personas](#user-personas)
    - [2.3.2. User Task Matrix](#user-task-matrix)
    - [2.3.3. User Journey Mapping](#user-journey-mapping)
    - [2.3.4. Empathy Mapping](#empathy-mapping)
  - [2.4. Big Picture Event Storming](#big-picture-event-storming)
  - [2.5. Ubiquitous Language](#ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#user-stories)
  - [3.2. Impact Mapping](#impact-mapping)
  - [3.3. Product Backlog](#product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#style-guidelines)
    - [4.1.1. General Style Guidelines](#general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#web-style-guidelines)
  - [4.2. Information Architecture](#information-architecture)
    - [4.2.1. Organization Systems](#organization-systems-1)
    - [4.2.2. Labeling Systems](#labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#searching-systems)
    - [4.2.5. Navigation Systems](#navigation-systems)
  - [4.3. Landing Page UI Design](#landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#level-1-system-context)
    - [4.6.3. Software Architecture Container Diagrams](#level-2-containers)
    - [4.6.4. Software Architecture Component Diagrams](#level-3-components)
  - [4.7. Software Object-Oriented Design](#software-object-oriented-design)
    - [4.7.1. Class Diagrams](#class-diagrams)
  - [4.8. Database Design](#database-design)
    - [4.8.1. Database Diagrams](#database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation-deployment)
  - [5.1. Software Configuration Management](#software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#software-development-environment-configuration)
    - [5.1.2. Source Code Management](#source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#source-code-style-guide-conventions)
    - [5.1.4. Software Deployment Configuration](#software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#landing-page-services-applications-implementation)
    - [5.2.1. Sprint 1](#sprint-1)
      - [5.2.1.1. Sprint Planning 1](#sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog](#sprint-backlog)
      - [5.2.1.4. Development Evidence for Sprint Review](#development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#team-collaboration-insights-during-sprint)
    - [5.2.2. Sprint 2](#sprint-2)
      - [5.2.2.1. Sprint Planning 2](#sprint-planning-2)
      - [5.2.2.2. Aspect Leaders and Collaborators](#aspect-leaders-and-collaborators-1)
      - [5.2.2.3. Sprint Backlog](#sprint-backlog-1)
      - [5.2.2.4. Development Evidence for Sprint Review](#development-evidence-for-sprint-review-1)
      - [5.2.2.5. Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review-1)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review](#services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review](#software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint](#team-collaboration-insights-during-sprint-1)
    - [5.2.3. Sprint 3](#sprint-3)
      - [5.2.3.1. Sprint Planning 3](#sprint-planning-3)
      - [5.2.3.2. Aspect Leaders and Collaborators](#aspect-leaders-and-collaborators-2)
      - [5.2.3.3. Sprint Backlog 3](#sprint-backlog-3)
      - [5.2.3.4. Development Evidence for Sprint Review](#development-evidence-for-sprint-review-2)
      - [5.2.3.5. Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review-2)
      - [5.2.3.6. Services Documentation Evidence for Sprint Review](#services-documentation-for-sprint-review)
      - [5.2.3.7. Software Deployment Evidence for Sprint Review](#software-deployment-evidence-for-sprint-review-1)
      - [5.2.3.8. Team Collaboration Insights for Sprint Review](#team-collaboration-insights-for-sprint-review)
    - [5.2.4. Sprint 4](#sprint-4)
      - [5.2.4.1. Sprint Planning 4](#sprint-planning-4)
      - [5.2.4.2. Aspect Leaders and Collaborators](#aspect-leaders-and-collaborators-3)
      - [5.2.4.3. Sprint Backlog 4](#sprint-backlog-4)
      - [5.2.4.4. Development Evidence for Sprint Review](#development-evidence-for-sprint-review-3)
      - [5.2.4.5. Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review-3)
      - [5.2.4.6. Services Documentation Evidence for Sprint Review](#services-documentation-evidence-for-sprint-review-1)
      - [5.2.4.7. Software Deployment Evidence for Sprint Review](#software-deployment-evidence-for-sprint-review-2)
      - [5.2.4.8. Team Collaboration Insights during Sprint](#team-collaboration-insights-during-sprint-2)
  - [5.3. Validation Interviews](#validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#diseño-de-entrevistas-1)
    - [5.3.2. Registro de Entrevistas](#registro-de-entrevistas-1)
    - [5.3.3. Evaluaciones Según Heurísticas](#evaluaciones-según-heurísticas)
  - [5.4. Video About the Product](#video-about-the-product)
- [Conclusiones](#conclusiones-y-recomendaciones)
  - [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About the Team](#video-about-the-team)
- [Bibliografía](#bibliography)
- [Anexos](#annexes)
  - [Annex A: Videos de Exposiciones](#annex-a-videos-de-exposiciones)
  - [Annex B: Video unificado entrevistas](#annex-b-video-unificado-entrevistas)
  - [Annex C: Links importantes](#annex-c-link-importantes)
  - [Annex D: Credenciales de Demo](#annex-d-credenciales-de-demo)

</nav>




## Student Outcome
| Criterio específico                                                        | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Conclusiones                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| :------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Comunica oralmente con efectividad a diferentes rangos de audiencia.**   | **Azama Fukuda, Juan Pablo**<br>**AV1:** Dirigí las sesiones de sincronización del equipo, explicando la visión del proyecto y asignando responsabilidades para la estructuración inicial de Lean UX y la arquitectura de la Landing Page. Articulé las metas del Sprint Planning de manera clara para alinear el trabajo del equipo de desarrollo.<br>**TB1:** Lideré la reunión de Sprint 2 Planning, exponiendo ante el equipo la estrategia dual de trabajo: correcciones del Sprint 1 en paralelo al inicio del desarrollo del frontend Angular. Presenté la arquitectura de carpetas por Bounded Context (`auth/`, `heatmap/`, `equipment/`, `maintenance/`) y argumenté su alineación con el Domain-Driven Design previamente modelado. Expliqué asimismo el funcionamiento del JSON Server desplegado en Azure como Fake API compartida, articulando cómo una URL pública elimina problemas de integración entre entornos de desarrollo.<br>**AV2:** Lideré la reunión de Sprint 3 Planning, comunicando al equipo la estrategia de transición del Fake API al backend real en Spring Boot y coordinando los frentes de trabajo de backend, actualización del frontend y nueva versión de la Landing Page. Coordiné las sesiones de entrevistas de validación, explicando a los participantes de ambos segmentos (administradores y clientes de gimnasio) el propósito y alcance de la evaluación con un lenguaje accesible y libre de tecnicismos. Expuse los resultados de las entrevistas al equipo, adaptando el nivel de detalle técnico según el interlocutor para facilitar decisiones de mejora de producto.<br>**TB2:** Lideré la reunión de Sprint 4 Planning, comunicando al equipo la incorporación de un nuevo integrante (Limache Coronel, Imanol Fabrizio) tras la salida de dos miembros, y coordinando la reorganización de responsabilidades entre los frentes de Membership & Billing, Monitoring/Alertas, Mantenimiento/Analítica y Frontend/Landing Page. Expliqué ante el equipo la integración de Stripe como pasarela de pago externa y el diseño del modelo de suscripción SaaS, articulando cómo esta decisión desbloqueaba el resto del alcance del sprint final.<br><br>**Espinoza Orrego, Valentino Andre**<br>**AV1:** Expuse los resultados del análisis del problema, entrevistas y validación de la solución, adaptando el mensaje tanto para usuarios finales como para administradores de gimnasios. Expliqué el valor de la propuesta (mapas de calor, IoT y mantenimiento predictivo), facilitando la comprensión técnica y comercial según la <br>**TB1:** Participé en la explicación y validación de wireframes, mockups, user flows y prototipos de la aplicación web, comunicando de forma clara las decisiones de diseño y navegación tanto al equipo técnico como a usuarios relacionados con el proyecto. Además, durante la implementación de la landing page UI Design, adapté la explicación de funcionalidades y flujos según el tipo de audiencia, facilitando la comprensión de la propuesta visual y funcional del sistema.<br> **AV2:** Dirigí y ejecuté las entrevistas de validación con los usuarios del segmento objetivo, usando un lenguaje claro y empático para obtener retroalimentación directa sobre la aplicación (p. 26). Asimismo, comuniqué de forma fluida y oportuna los avances de los servicios web al resto del equipo en las reuniones síncronas, asegurando que todos comprendieran el funcionamiento técnico de la solución.<br> **TB2:** Coordiné con el equipo en las sesiones de revisión de código del backend para implementar los Bounded Contexts de Memberships y Analytics en Spring Boot. Asimismo, comuniqué de forma clara y oportuna las correcciones de la entrega anterior y de la documentación técnica en las reuniones síncronas, asegurando que todos comprendieran la reestructuración final antes del Release Review. <br><br>**Fernández Linares, Alvaro Sebastian**<br>**AV1:** Dirigí las sesiones de diseño y estructuración del frontend, sustentando las decisiones de Interfaz de Usuario (UI) ante el equipo de desarrollo. Expliqué de forma clara la aplicación de principios Lean UX y evaluaciones heurísticas, adaptando el lenguaje para asegurar la comprensión de los requerimientos de negocio de SpotTrack.<br>**TB1:** Durante las reuniones de planificación y sincronización del equipo, expuse la estrategia de desarrollo e integración para los Bounded Contexts asignados (`alerts`, `reservation`, `dashboard`) dentro de la WebApp. Argumenté la importancia de priorizar `reservation` como Core Domain de la solución y expliqué la estrategia de mitigación para las correcciones del Sprint 1, detallando además el flujo de navegación y redirección entre la Landing Page y la WebApp desplegada en Azure.<br> **AV2** Participé activamente en las reuniones de sincronización del equipo explicando los avances técnicos en la lógica de los servicios web, y debatí de forma abierta las mejoras necesarias para corregir los diagramas de arquitectura. Asimismo, apoyé en la conducción de las entrevistas de validación con los usuarios objetivo para escuchar y recopilar sus comentarios de primera mano. <br> **TB2:** Lideré la exposición técnica del Bounded Context de Membership & Billing durante las reuniones de Sprint 4 Planning, argumentando ante el equipo por qué el modelo de suscripción con Stripe era una precondición para el onboarding de gimnasios y no una funcionalidad aislada. Expliqué asimismo la incorporación de las preferencias de notificación y el endurecimiento de la autenticación (interceptor HTTP 401/403), facilitando que el resto del equipo comprendiera el impacto de estos cambios en los flujos de IAM ya existentes.<br><br>**Limache Coronel, Imanol Fabrizio**<br>**TB2:** Al incorporarme al equipo a mitad del Sprint 4, expliqué en las reuniones de sincronización mi propuesta de diseño para el Centro de Alertas unificado, sustentando ante el equipo por qué la ampliación de la red de sensores IoT (cámara y seguimiento de sesión) requería un módulo de alertas independiente del Bounded Context de Monitoring. Comuniqué también, en un lenguaje accesible para el resto del equipo, el flujo de asignación de técnicos de mantenimiento y el seguimiento en vivo de las sesiones de rutina, facilitando mi integración productiva pese a incorporarme sin contexto previo del proyecto. | Se logró establecer una comunicación oral efectiva que permitió articular con claridad la visión técnica y comercial de SpotTrack. A través de sesiones de planificación, exposiciones de arquitectura, validaciones con usuarios y sustentación de decisiones de diseño UI, el equipo demostró capacidad para adaptar el lenguaje a diferentes audiencias, tanto técnicas como administrativas y usuarios finales. Durante el TB1, esta competencia se fortaleció mediante la explicación de decisiones de arquitectura frontend, despliegue en Azure, integración mediante Fake APIs y organización basada en Domain-Driven Design, garantizando la alineación del equipo en los distintos frentes del Sprint 2. Durante el AV2, la comunicación oral evolucionó hacia la coordinación de entrevistas de validación con ambos segmentos objetivo y la presentación de resultados al equipo, demostrando la capacidad de traducir hallazgos de usuario en decisiones de mejora de producto comprensibles para audiencias técnicas y no técnicas. |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia.** | **Azama Fukuda, Juan Pablo**<br>**AV1:** Redacté y estructuré el documento *Sprint Planning 1*, documentando asignaciones de tareas y configuración del entorno de desarrollo. Desarrollé la arquitectura de información utilizando Markdown y jerarquías visuales para facilitar la lectura técnica.<br>**TB1:** Redacté el *Sprint 2 Planning*, la tabla de *Aspect Leaders* y el *Sprint Backlog*, documentando tareas CORR, SETUP, User Stories y Technical Stories con estimaciones, responsables y estados. Documenté además el pipeline CI/CD en GitHub Actions para el despliegue de la Landing Page y la WebApp, así como los endpoints del Mock API y las URLs de producción.<br>**AV2:** Redacté el *Sprint 3 Planning*, la tabla de *Aspect Leaders* y el *Sprint Backlog*, documentando las tareas de desarrollo backend, correcciones del Sprint 2, entrevistas de validación y nueva versión de la Landing Page con responsables y estados. Documenté los contratos REST del backend desplegado en Spring Boot, detallando rutas, métodos HTTP y ejemplos de respuesta para guiar la integración con el frontend Angular. Actualicé la sección de Conclusiones y Recomendaciones del informe, sintetizando los aprendizajes técnicos y de producto obtenidos a lo largo de los tres sprints del proyecto.<br>**TB2:** Redacté el *Sprint 4 Planning*, la tabla de *Aspect Leaders* y el *Sprint Backlog 4*, documentando el cambio en la composición del equipo y las tareas de integración de Stripe, monitoreo IoT, mantenimiento de técnicos y analítica financiera con responsables y estados. Documenté los nuevos endpoints REST del backend (Membership, Monitoring, Maintenance, Analytics) y actualicé las evidencias de despliegue final de los tres productos digitales en producción.<br><br>**Espinoza Orrego, Valentino Andre**<br>**AV1:** Documenté de manera estructurada el proceso de segmentación, entrevistas, user personas, journey maps y requerimientos. Elaboré entregables como el análisis competitivo y el glosario, asegurando claridad tanto para perfiles técnicos como de gestión. <br>**TB1:** Documenté y estructuré los wireflow diagrams, user flows y prototipos de la aplicación web para representar de manera clara la lógica de navegación y experiencia de usuario del proyecto. Asimismo, apoyé en la elaboración y organización de contenidos relacionados con el diseño e implementación de la landing page, asegurando una comunicación escrita comprensible tanto para el equipo de desarrollo como para stakeholders no técnicos. <br> **AV2:** Diseñé y documenté la lógica de los servicios web (Web Services) usando comentarios estructurados y buenas prácticas de codificación en el repositorio de GitHub. Adicionalmente, redacté de forma detallada el trabajo de responsabilidad social siguiendo el código de ética profesional, y dejé correcciones escritas y estructuradas durante la revisión del informe principal para garantizar su legibilidad técnica antes de la entrega <br> **TB2:** Dirigí el desarrollo, guion y locución de los videos About the Product y About the Team, adaptando el lenguaje técnico a un enfoque comercial y de retrospectiva transparente para el jurado. Además, coordiné los testimonios del equipo, usando una comunicación fluida para sintetizar los aprendizajes del ciclo de forma accesible para audiencias no técnicas. <br><br>**Fernández Linares, Alvaro Sebastian**<br>**AV1:** Redacté y estructuré la documentación de experiencia de usuario utilizando Markdown y jerarquías visuales. Elaboré artefactos de diseño como guiones de entrevistas, User Flows y Wireframes para servir como guía de implementación técnica.<br>**TB1:** Documenté la estructura e implementación de los Bounded Contexts (`alerts`, `reservation`, `dashboard`) dentro de la WebApp, detallando responsabilidades y componentes para asegurar la mantenibilidad del sistema. También redacté el reporte de correcciones del Sprint 1 y la documentación relacionada con el flujo de integración y despliegue entre la Landing Page y la infraestructura en Azure.<br> **AV2** Documenté y estructuré el código fuente de los Web Services en el repositorio de GitHub siguiendo las convenciones establecidas. Además, redacté e incorporé los cambios técnicos en los diagramas de clases UML y diagramas C4 en el informe principal, y registré de forma escrita los resúmenes y hallazgos clave obtenidos a partir de las entrevistas de validación. <br> **TB2:** Documenté el Bounded Context de Membership (agregado Membership, MembershipTier, BranchAccess), el flujo de onboarding de gimnasios con registro pendiente y pago inicial, la lista blanca de clientes y los endpoints de preferencias de notificación, dejando especificado el contrato REST correspondiente. Redacté además la documentación del interceptor global HTTP 401/403 y de las validaciones de autenticación reforzadas para el cierre del proyecto.<br><br>**Limache Coronel, Imanol Fabrizio**<br>**TB2:** Documenté el Bounded Context de Alerts (modelo de severidad, resolución de alertas) y su integración con los sensores de movimiento, cámara y seguimiento de sesión, dejando registrados los endpoints `/api/v1/alerts` en la tabla de servicios web. Redacté asimismo la documentación de la interfaz de asignación de técnicos de mantenimiento y del seguimiento de sesiones de rutina, apoyando con reportes escritos de mis pull requests durante la incorporación a mitad de ciclo. | La documentación elaborada destacó por su rigor profesional, precisión técnica y enfoque orientado al usuario. La combinación de diagramas arquitectónicos complejos (C4, DDD), artefactos UX (Journey Maps, Personas, User Flows y Wireframes) y documentación técnica permitió consolidar una única fuente de verdad para el proyecto. Durante el TB1, esta competencia se fortaleció mediante la documentación de pipelines CI/CD, despliegues en Azure, endpoints del Mock API y backlog técnico, evidenciando la capacidad del equipo para comunicar información técnica compleja de manera clara y comprensible para distintos tipos de audiencia. Durante el AV2, esta competencia se consolidó con la documentación del backend real en Spring Boot —incluyendo contratos REST, evidencias de integración y despliegue— y la síntesis de los aprendizajes de los tres sprints en las Conclusiones y Recomendaciones finales del informe, demostrando madurez en la comunicación escrita técnica y de producto a lo largo de todo el ciclo de desarrollo.                                                           |
