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

# Contenido

## Tabla de contenidos

- [Contenido](#contenido)
  - [Tabla de contenidos](#tabla-de-contenidos)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [Startup Profile](#startup-profile)
    - [Descripción de la Startup](#descripción-de-la-startup)
    - [Perfiles de integrantes del equipo](#perfiles-de-integrantes-del-equipo)
  - [Solution Profile](#solution-profile)
    - [Antecedentes y problemática](#antecedentes-y-problemática)
    - [Lean UX Process](#lean-ux-process)
      - [Lean UX Problem Statements](#lean-ux-problem-statements)
      - [Lean UX Assumptions](#lean-ux-assumptions)
      - [Lean UX Hypothesis Statements](#lean-ux-hypothesis-statements)
      - [Lean UX Canvas](#lean-ux-canvas)
- [Lean UX Canvas (v2)](#lean-ux-canvas-v2)
  - [1. Problema de Negocio (Business Problem)](#1-problema-de-negocio-business-problem)
  - [2. Resultados de Negocio (Business Outcomes)](#2-resultados-de-negocio-business-outcomes)
  - [3. Usuarios (Users)](#3-usuarios-users)
  - [4. Resultados y Beneficios del Usuario (User Outcomes \& Benefits)](#4-resultados-y-beneficios-del-usuario-user-outcomes--benefits)
  - [5. Soluciones (Solutions)](#5-soluciones-solutions)
  - [6. Hipótesis (Hypotheses)](#6-hipótesis-hypotheses)
  - [7. ¿Qué es lo más importante que necesitamos aprender primero?](#7-qué-es-lo-más-importante-que-necesitamos-aprender-primero)
  - [8. ¿Cuál es la menor cantidad de trabajo para aprender lo siguiente?](#8-cuál-es-la-menor-cantidad-de-trabajo-para-aprender-lo-siguiente)
  - [Segmentos objetivo](#segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [Competidores](#competidores)
    - [Análisis competitivo](#análisis-competitivo)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [Estrategias y tácticas frente a competidores](#estrategias-y-tácticas-frente-a-competidores)
  - [Entrevistas](#entrevistas)
    - [Diseño de entrevistas](#diseño-de-entrevistas)
    - [Registro de entrevistas](#registro-de-entrevistas)
    - [Entrevista 1: Julio Cardenas](#entrevista-1-julio-cardenas)
    - [Entrevista 2: Luis Romero](#entrevista-2-luis-romero)
    - [Entrevista 3: Percy Baraybar](#entrevista-3-percy-baraybar)
      - [Entrevistado 4: Joan Steffano Quispe Gamez](#entrevistado-4-joan-steffano-quispe-gamez)
      - [Entrevistado 5: Fabián Suárez](#entrevistado-5-fabián-suárez)
      - [Entrevistado 6](#entrevistado-6)
      - [Video unificado](#video-unificado)
    - [Análisis de entrevistas](#análisis-de-entrevistas)
    - [1st Segmento (Administradores y Gerentes de Operaciones de Gimnasios)](#1st-segmento-administradores-y-gerentes-de-operaciones-de-gimnasios)
      - [2nd Segmento (Clientes que frecuentan Gimnasios)](#2nd-segmento-clientes-que-frecuentan-gimnasios)
  - [Needfinding](#needfinding)
    - [User Personas](#user-personas)
    - [User Task Matrix](#user-task-matrix)
    - [User Journey Mapping](#user-journey-mapping)
    - [Empathy Mapping](#empathy-mapping)
  - [Big Picture Event Storming](#big-picture-event-storming)
  - [Ubiquitous Language](#ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [User Stories](#user-stories)
    - [3.1. Épicas del Proyecto](#31-épicas-del-proyecto)
  - [Impact Mapping](#impact-mapping)
  - [Product Backlog](#product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [Style Guidelines](#style-guidelines)
    - [General Style Guidelines](#general-style-guidelines)
    - [Web Style Guidelines](#web-style-guidelines)
  - [Information Architecture](#information-architecture)
    - [Organization Systems](#organization-systems)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [Labeling Systems](#labeling-systems)
    - [SEO Tags and Meta Tags](#seo-tags-and-meta-tags)
    - [Searching Systems](#searching-systems)
    - [Navigation Systems](#navigation-systems)
  - [Landing Page UI Design](#landing-page-ui-design)
    - [Landing Page Wireframe](#landing-page-wireframe)
    - [Landing Page Mock-up](#landing-page-mock-up)
  - [Web Applications UX/UI Design](#web-applications-uxui-design)
    - [Web Applications Wireframes](#web-applications-wireframes)
    - [Web Applications Wireflow Diagrams](#web-applications-wireflow-diagrams)
    - [Web Applications Mock-ups](#web-applications-mock-ups)
    - [Web Applications User Flow Diagrams](#web-applications-user-flow-diagrams)
  - [US04: Selección de planes de suscripción SaaS](#us04-selección-de-planes-de-suscripción-saas)
  - [US05: Envío de formulario de Contacto](#us05-envío-de-formulario-de-contacto)
  - [US06: Acceso al portal desde la navegación](#us06-acceso-al-portal-desde-la-navegación)
  - [US07: Inicio de sesión con validación JWT](#us07-inicio-de-sesión-con-validación-jwt)
  - [US08: Gestión de preferencias y perfil](#us08-gestión-de-preferencias-y-perfil)
  - [US09 y US10: Mapa de calor y filtros de equipamiento](#us09-y-us10-mapa-de-calor-y-filtros-de-equipamiento)
  - [US11: Cambio de sucursal para revisión de aforo](#us11-cambio-de-sucursal-para-revisión-de-aforo)
  - [US12: Notificaciones push de resolución de disponibilidad](#us12-notificaciones-push-de-resolución-de-disponibilidad)
  - [US13: Motor de sugerencia de rutinas alternativas](#us13-motor-de-sugerencia-de-rutinas-alternativas)
  - [US14: Filtrado de alternativas por grupo muscular](#us14-filtrado-de-alternativas-por-grupo-muscular)
  - [US15: Sistema de reserva exprés en horas pico](#us15-sistema-de-reserva-exprés-en-horas-pico)
  - [US16: Acumulación automática de horas de uso (EP08)](#us16-acumulación-automática-de-horas-de-uso-ep08)
  - [US17: Identificación de equipos subutilizados (EP05)](#us17-identificación-de-equipos-subutilizados-ep05)
  - [US18: Visualización de picos de estrés del local (EP05)](#us18-visualización-de-picos-de-estrés-del-local-ep05)
  - [US19 Exportación de analíticas de uso (Epic: EP05)](#us19-exportación-de-analíticas-de-uso-epic-ep05)
  - [US20 Monitoreo de estado de hardware Edge IoT (Epic\_ EP05)](#us20-monitoreo-de-estado-de-hardware-edge-iot-epic_-ep05)
  - [US21 Alerta predictiva de mantenimiento (Epic\_ EP06) CONFIGURAR UMBRAL](#us21-alerta-predictiva-de-mantenimiento-epic_-ep06-configurar-umbral)
  - [US22 Despacho automatizado de tickets técnicos (Epic\_ EP06)](#us22-despacho-automatizado-de-tickets-técnicos-epic_-ep06)
  - [US23 Notificación de restablecimiento a los usuarios (Epic\_ EP06)](#us23-notificación-de-restablecimiento-a-los-usuarios-epic_-ep06)
  - [US24 Calendario inteligente de bloqueos de reserva(Epic\_ EP04)](#us24-calendario-inteligente-de-bloqueos-de-reservaepic_-ep04)
  - [US25 Gestión de activos físicos y altas (Epic\_ EP07)](#us25-gestión-de-activos-físicos-y-altas-epic_-ep07)
  - [US28 Calculadora de impacto financiero por inactividad (Epic: EP08)](#us28-calculadora-de-impacto-financiero-por-inactividad-epic-ep08)
  - [US29 Analítica predictiva de compras e inversión (Epic\_ EP08)](#us29-analítica-predictiva-de-compras-e-inversión-epic_-ep08)
  - [Web Applications Prototyping](#web-applications-prototyping)
  - [Domain-Driven Software Architecture](#domain-driven-software-architecture)
    - [Design-Level Event Storming](#design-level-event-storming)
    - [Aggregates](#aggregates)
- [System Architecture (C4 Model)](#system-architecture-c4-model)
  - [Level 1: System Context](#level-1-system-context)
  - [Level 2: Containers](#level-2-containers)
    - [General Container View](#general-container-view)
    - [Bounded Contexts](#bounded-contexts)
  - [Level 3: Components](#level-3-components)
    - [1. Identity \& Access Management (IAM)](#1-identity--access-management-iam)
    - [2. Membership](#2-membership)
    - [3. Profiles \& Gym](#3-profiles--gym)
    - [4. Reservation](#4-reservation)
    - [5. Routines](#5-routines)
    - [6. Equipment \& IoT Sensor Ingestion](#6-equipment--iot-sensor-ingestion)
    - [7. Monitoring \& Alerts](#7-monitoring--alerts)
    - [8. Maintenance](#8-maintenance)
    - [9. Analytics \& Dashboards](#9-analytics--dashboards)
    - [10. Shared \& Configuration](#10-shared--configuration)
  - [Level 4: Dynamic Views (Aggregate Flows)](#level-4-dynamic-views-aggregate-flows)
    - [1. IAM \& User Flow](#1-iam--user-flow)
    - [2. Profiles \& Gym Flows](#2-profiles--gym-flows)
    - [3. Equipment \& Routine Flows](#3-equipment--routine-flows)
    - [4. Reservation \& Requests Flows](#4-reservation--requests-flows)
    - [5. Maintenance \& Technical Ticket Flows](#5-maintenance--technical-ticket-flows)
  - [Software Object-Oriented Design](#software-object-oriented-design)
    - [Class Diagrams](#class-diagrams)
  - [Database Design](#database-design)
    - [Database Diagrams](#database-diagrams)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [Software Configuration Management](#software-configuration-management)
    - [Software Development Environment Configuration](#software-development-environment-configuration)
    - [Source Code Management](#source-code-management)
    - [Source Code Style Guide \& Conventions](#source-code-style-guide--conventions)
    - [Software Deployment Configuration](#software-deployment-configuration)
  - [Landing Page, Services \& Applications Implementation](#landing-page-services--applications-implementation)
    - [Sprint 1](#sprint-1)
      - [Sprint Planning 1](#sprint-planning-1)
      - [Aspect Leaders and Collaborators](#aspect-leaders-and-collaborators)
    - [Sprint Backlog](#sprint-backlog)
      - [Development Evidence for Sprint Review](#development-evidence-for-sprint-review)
      - [Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review)
      - [Team Collaboration Insights during Sprint](#team-collaboration-insights-during-sprint)
    - [Sprint 2](#sprint-2)
      - [Sprint Planning 2](#sprint-planning-2)
      - [Aspect Leaders and Collaborators](#aspect-leaders-and-collaborators-1)
      - [Sprint Backlog](#sprint-backlog-1)
      - [Development Evidence for Sprint Review](#development-evidence-for-sprint-review-1)
      - [Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review-1)
      - [Services Documentation Evidence for Sprint Review](#services-documentation-evidence-for-sprint-review)
        - [Relación de Endpoints Documentados](#relación-de-endpoints-documentados)
        - [Evidencias de Interacción con la Documentación](#evidencias-de-interacción-con-la-documentación)
          - [Disponibilidad del Servicio](#disponibilidad-del-servicio)
          - [Interacción con Recurso Equipments](#interacción-con-recurso-equipments)
        - [Repositorio y Trazabilidad de Documentación](#repositorio-y-trazabilidad-de-documentación)
      - [Software Deployment Evidence for Sprint Review](#software-deployment-evidence-for-sprint-review)
      - [Team Collaboration Insights during Sprint](#team-collaboration-insights-during-sprint-1)
    - [Sprint 3](#sprint-3)
      - [Sprint Planning 3](#sprint-planning-3)
      - [Aspect Leaders and Collaborators](#aspect-leaders-and-collaborators-2)
      - [Sprint Backlog 3](#sprint-backlog-3)
      - [Development Evidence for Sprint Review](#development-evidence-for-sprint-review-2)
      - [Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review-2)
      - [Services Documentation for Sprint Review](#services-documentation-for-sprint-review)
        - [Bounded Context: IAM (Identity \& Access Management)](#bounded-context-iam-identity--access-management)
        - [Bounded Context: Gym (Gestión de Instalaciones)](#bounded-context-gym-gestión-de-instalaciones)
        - [Bounded Context: Equipment (Gestión de Activos)](#bounded-context-equipment-gestión-de-activos)
        - [Bounded Context: Maintenance (Mantenimiento)](#bounded-context-maintenance-mantenimiento)
        - [Bounded Context: Reservation (Reservas Exprés)](#bounded-context-reservation-reservas-exprés)
      - [Software Deployment Evidence for Sprint Review](#software-deployment-evidence-for-sprint-review-1)
      - [Team Collaboration Insights for Sprint Review](#team-collaboration-insights-for-sprint-review)
      - [Platform](#platform)
      - [Report](#report)
      - [Webapp](#webapp)
      - [Website](#website)
    - [Sprint 4](#sprint-4)
      - [Sprint Planning 4](#sprint-planning-4)
        - [Sprint 3 Retrospective — Individual Feedback](#sprint-3-retrospective--individual-feedback)
        - [Sprint 4 Retrospective Summary](#sprint-4-retrospective-summary)
      - [Aspect Leaders and Collaborators](#aspect-leaders-and-collaborators-3)
      - [Sprint Backlog 4](#sprint-backlog-4)
      - [Development Evidence for Sprint Review](#development-evidence-for-sprint-review-3)
      - [Execution Evidence for Sprint Review](#execution-evidence-for-sprint-review-3)
      - [Services Documentation Evidence for Sprint Review](#services-documentation-evidence-for-sprint-review-1)
        - [Bounded Context: Membership (Suscripción y Facturación)](#bounded-context-membership-suscripción-y-facturación)
        - [Bounded Context: Monitoring (Sensores IoT y Anomalías)](#bounded-context-monitoring-sensores-iot-y-anomalías)
        - [Bounded Context: Analytics \& Maintenance (Técnicos, Cotizaciones y ROI)](#bounded-context-analytics--maintenance-técnicos-cotizaciones-y-roi)
        - [Bounded Context: IAM y Alertas](#bounded-context-iam-y-alertas)
      - [Software Deployment Evidence for Sprint Review](#software-deployment-evidence-for-sprint-review-2)
      - [Team Collaboration Insights during Sprint](#team-collaboration-insights-during-sprint-2)
      - [Platform](#platform-1)
      - [Report](#report-1)
      - [Webapp](#webapp-1)
      - [Website](#website-1)
  - [Validation Interviews](#validation-interviews)
    - [Diseño de Entrevistas](#diseño-de-entrevistas-1)
    - [Registro de Entrevistas](#registro-de-entrevistas-1)
      - [Video unificado](#video-unificado-1)
    - [Evaluaciones Según Heurísticas](#evaluaciones-según-heurísticas)
  - [Video About the Product](#video-about-the-product)
  - [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
    - [Conclusiones](#conclusiones)
      - [Sprint 1](#sprint-1-1)
      - [Sprint 2](#sprint-2-1)
      - [Sprint 3](#sprint-3-1)
      - [Sprint 4](#sprint-4-1)
    - [Recomendaciones](#recomendaciones)
      - [Sprint 1](#sprint-1-2)
      - [Sprint 2](#sprint-2-2)
      - [Sprint 3](#sprint-3-2)
      - [Sprint 4](#sprint-4-2)
  - [Bibliography](#bibliography)
  - [Annexes](#annexes)
    - [Annex A : Videos de Exposiciones](#annex-a--videos-de-exposiciones)
    - [Annex B : Video unificado entrevistas](#annex-b--video-unificado-entrevistas)
    - [Annex C : Link importantes](#annex-c--link-importantes)
    - [Annex D : Credenciales de Demo](#annex-d--credenciales-de-demo)
  

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

**Sprints 1 y 2**

*Report*

![](../assets/Insights/report.png)

*Website*

![](../assets/Insights/website.png)

*Web Application*

![](../assets/Insights/webapp.png)

**Sprint 3**

*Report*

![](../assets/Insights/sprint3/report-insights.png)

*Website*

![](../assets/Insights/sprint3/website-insights.png)

*Web Application*

![](../assets/Insights/sprint3/webapp-insights.png)

*Platform*

![](../assets/Insights/sprint3/platform-insights.png)

**Sprint 4**

*Report*

![](../assets/Insights/sprint4/report-insights.png)

*Website*

![](../assets/Insights/sprint4/website-insights.png)

*Web Application*

![](../assets/Insights/sprint4/webapp-insights.png)

*Platform*

![](../assets/Insights/sprint4/platform-insights.png)

---

## Student Outcome
| Criterio específico                                                        | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Conclusiones                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| :------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Comunica oralmente con efectividad a diferentes rangos de audiencia.**   | **Azama Fukuda, Juan Pablo**<br>**AV1:** Dirigí las sesiones de sincronización del equipo, explicando la visión del proyecto y asignando responsabilidades para la estructuración inicial de Lean UX y la arquitectura de la Landing Page. Articulé las metas del Sprint Planning de manera clara para alinear el trabajo del equipo de desarrollo.<br>**TB1:** Lideré la reunión de Sprint 2 Planning, exponiendo ante el equipo la estrategia dual de trabajo: correcciones del Sprint 1 en paralelo al inicio del desarrollo del frontend Angular. Presenté la arquitectura de carpetas por Bounded Context (`auth/`, `heatmap/`, `equipment/`, `maintenance/`) y argumenté su alineación con el Domain-Driven Design previamente modelado. Expliqué asimismo el funcionamiento del JSON Server desplegado en Azure como Fake API compartida, articulando cómo una URL pública elimina problemas de integración entre entornos de desarrollo.<br>**AV2:** Lideré la reunión de Sprint 3 Planning, comunicando al equipo la estrategia de transición del Fake API al backend real en Spring Boot y coordinando los frentes de trabajo de backend, actualización del frontend y nueva versión de la Landing Page. Coordiné las sesiones de entrevistas de validación, explicando a los participantes de ambos segmentos (administradores y clientes de gimnasio) el propósito y alcance de la evaluación con un lenguaje accesible y libre de tecnicismos. Expuse los resultados de las entrevistas al equipo, adaptando el nivel de detalle técnico según el interlocutor para facilitar decisiones de mejora de producto.<br>**TB2:** Lideré la reunión de Sprint 4 Planning, comunicando al equipo la incorporación de un nuevo integrante (Limache Coronel, Imanol Fabrizio) tras la salida de dos miembros, y coordinando la reorganización de responsabilidades entre los frentes de Membership & Billing, Monitoring/Alertas, Mantenimiento/Analítica y Frontend/Landing Page. Expliqué ante el equipo la integración de Stripe como pasarela de pago externa y el diseño del modelo de suscripción SaaS, articulando cómo esta decisión desbloqueaba el resto del alcance del sprint final.<br><br>**Espinoza Orrego, Valentino Andre**<br>**AV1:** Expuse los resultados del análisis del problema, entrevistas y validación de la solución, adaptando el mensaje tanto para usuarios finales como para administradores de gimnasios. Expliqué el valor de la propuesta (mapas de calor, IoT y mantenimiento predictivo), facilitando la comprensión técnica y comercial según la <br>**TB1:** Participé en la explicación y validación de wireframes, mockups, user flows y prototipos de la aplicación web, comunicando de forma clara las decisiones de diseño y navegación tanto al equipo técnico como a usuarios relacionados con el proyecto. Además, durante la implementación de la landing page UI Design, adapté la explicación de funcionalidades y flujos según el tipo de audiencia, facilitando la comprensión de la propuesta visual y funcional del sistema.<br> **AV2:** Dirigí y ejecuté las entrevistas de validación con los usuarios del segmento objetivo, usando un lenguaje claro y empático para obtener retroalimentación directa sobre la aplicación (p. 26). Asimismo, comuniqué de forma fluida y oportuna los avances de los servicios web al resto del equipo en las reuniones síncronas, asegurando que todos comprendieran el funcionamiento técnico de la solución.<br> **TB2:** Coordiné con el equipo en las sesiones de revisión de código del backend para implementar los Bounded Contexts de Memberships y Analytics en Spring Boot. Asimismo, comuniqué de forma clara y oportuna las correcciones de la entrega anterior y de la documentación técnica en las reuniones síncronas, asegurando que todos comprendieran la reestructuración final antes del Release Review. <br><br>**Fernández Linares, Alvaro Sebastian**<br>**AV1:** Dirigí las sesiones de diseño y estructuración del frontend, sustentando las decisiones de Interfaz de Usuario (UI) ante el equipo de desarrollo. Expliqué de forma clara la aplicación de principios Lean UX y evaluaciones heurísticas, adaptando el lenguaje para asegurar la comprensión de los requerimientos de negocio de SpotTrack.<br>**TB1:** Durante las reuniones de planificación y sincronización del equipo, expuse la estrategia de desarrollo e integración para los Bounded Contexts asignados (`alerts`, `reservation`, `dashboard`) dentro de la WebApp. Argumenté la importancia de priorizar `reservation` como Core Domain de la solución y expliqué la estrategia de mitigación para las correcciones del Sprint 1, detallando además el flujo de navegación y redirección entre la Landing Page y la WebApp desplegada en Azure.<br> **AV2** Participé activamente en las reuniones de sincronización del equipo explicando los avances técnicos en la lógica de los servicios web, y debatí de forma abierta las mejoras necesarias para corregir los diagramas de arquitectura. Asimismo, apoyé en la conducción de las entrevistas de validación con los usuarios objetivo para escuchar y recopilar sus comentarios de primera mano. <br> **TB2:** Lideré la exposición técnica del Bounded Context de Membership & Billing durante las reuniones de Sprint 4 Planning, argumentando ante el equipo por qué el modelo de suscripción con Stripe era una precondición para el onboarding de gimnasios y no una funcionalidad aislada. Expliqué asimismo la incorporación de las preferencias de notificación y el endurecimiento de la autenticación (interceptor HTTP 401/403), facilitando que el resto del equipo comprendiera el impacto de estos cambios en los flujos de IAM ya existentes.<br><br>**Limache Coronel, Imanol Fabrizio**<br>**TB2:** Al incorporarme al equipo a mitad del Sprint 4, expliqué en las reuniones de sincronización mi propuesta de diseño para el Centro de Alertas unificado, sustentando ante el equipo por qué la ampliación de la red de sensores IoT (cámara y seguimiento de sesión) requería un módulo de alertas independiente del Bounded Context de Monitoring. Comuniqué también, en un lenguaje accesible para el resto del equipo, el flujo de asignación de técnicos de mantenimiento y el seguimiento en vivo de las sesiones de rutina, facilitando mi integración productiva pese a incorporarme sin contexto previo del proyecto. | Se logró establecer una comunicación oral efectiva que permitió articular con claridad la visión técnica y comercial de SpotTrack. A través de sesiones de planificación, exposiciones de arquitectura, validaciones con usuarios y sustentación de decisiones de diseño UI, el equipo demostró capacidad para adaptar el lenguaje a diferentes audiencias, tanto técnicas como administrativas y usuarios finales. Durante el TB1, esta competencia se fortaleció mediante la explicación de decisiones de arquitectura frontend, despliegue en Azure, integración mediante Fake APIs y organización basada en Domain-Driven Design, garantizando la alineación del equipo en los distintos frentes del Sprint 2. Durante el AV2, la comunicación oral evolucionó hacia la coordinación de entrevistas de validación con ambos segmentos objetivo y la presentación de resultados al equipo, demostrando la capacidad de traducir hallazgos de usuario en decisiones de mejora de producto comprensibles para audiencias técnicas y no técnicas. |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia.** | **Azama Fukuda, Juan Pablo**<br>**AV1:** Redacté y estructuré el documento *Sprint Planning 1*, documentando asignaciones de tareas y configuración del entorno de desarrollo. Desarrollé la arquitectura de información utilizando Markdown y jerarquías visuales para facilitar la lectura técnica.<br>**TB1:** Redacté el *Sprint 2 Planning*, la tabla de *Aspect Leaders* y el *Sprint Backlog*, documentando tareas CORR, SETUP, User Stories y Technical Stories con estimaciones, responsables y estados. Documenté además el pipeline CI/CD en GitHub Actions para el despliegue de la Landing Page y la WebApp, así como los endpoints del Mock API y las URLs de producción.<br>**AV2:** Redacté el *Sprint 3 Planning*, la tabla de *Aspect Leaders* y el *Sprint Backlog*, documentando las tareas de desarrollo backend, correcciones del Sprint 2, entrevistas de validación y nueva versión de la Landing Page con responsables y estados. Documenté los contratos REST del backend desplegado en Spring Boot, detallando rutas, métodos HTTP y ejemplos de respuesta para guiar la integración con el frontend Angular. Actualicé la sección de Conclusiones y Recomendaciones del informe, sintetizando los aprendizajes técnicos y de producto obtenidos a lo largo de los tres sprints del proyecto.<br>**TB2:** Redacté el *Sprint 4 Planning*, la tabla de *Aspect Leaders* y el *Sprint Backlog 4*, documentando el cambio en la composición del equipo y las tareas de integración de Stripe, monitoreo IoT, mantenimiento de técnicos y analítica financiera con responsables y estados. Documenté los nuevos endpoints REST del backend (Membership, Monitoring, Maintenance, Analytics) y actualicé las evidencias de despliegue final de los tres productos digitales en producción.<br><br>**Espinoza Orrego, Valentino Andre**<br>**AV1:** Documenté de manera estructurada el proceso de segmentación, entrevistas, user personas, journey maps y requerimientos. Elaboré entregables como el análisis competitivo y el glosario, asegurando claridad tanto para perfiles técnicos como de gestión. <br>**TB1:** Documenté y estructuré los wireflow diagrams, user flows y prototipos de la aplicación web para representar de manera clara la lógica de navegación y experiencia de usuario del proyecto. Asimismo, apoyé en la elaboración y organización de contenidos relacionados con el diseño e implementación de la landing page, asegurando una comunicación escrita comprensible tanto para el equipo de desarrollo como para stakeholders no técnicos. <br> **AV2:** Diseñé y documenté la lógica de los servicios web (Web Services) usando comentarios estructurados y buenas prácticas de codificación en el repositorio de GitHub. Adicionalmente, redacté de forma detallada el trabajo de responsabilidad social siguiendo el código de ética profesional, y dejé correcciones escritas y estructuradas durante la revisión del informe principal para garantizar su legibilidad técnica antes de la entrega <br> **TB2:** Dirigí el desarrollo, guion y locución de los videos About the Product y About the Team, adaptando el lenguaje técnico a un enfoque comercial y de retrospectiva transparente para el jurado. Además, coordiné los testimonios del equipo, usando una comunicación fluida para sintetizar los aprendizajes del ciclo de forma accesible para audiencias no técnicas. <br><br>**Fernández Linares, Alvaro Sebastian**<br>**AV1:** Redacté y estructuré la documentación de experiencia de usuario utilizando Markdown y jerarquías visuales. Elaboré artefactos de diseño como guiones de entrevistas, User Flows y Wireframes para servir como guía de implementación técnica.<br>**TB1:** Documenté la estructura e implementación de los Bounded Contexts (`alerts`, `reservation`, `dashboard`) dentro de la WebApp, detallando responsabilidades y componentes para asegurar la mantenibilidad del sistema. También redacté el reporte de correcciones del Sprint 1 y la documentación relacionada con el flujo de integración y despliegue entre la Landing Page y la infraestructura en Azure.<br> **AV2** Documenté y estructuré el código fuente de los Web Services en el repositorio de GitHub siguiendo las convenciones establecidas. Además, redacté e incorporé los cambios técnicos en los diagramas de clases UML y diagramas C4 en el informe principal, y registré de forma escrita los resúmenes y hallazgos clave obtenidos a partir de las entrevistas de validación. <br> **TB2:** Documenté el Bounded Context de Membership (agregado Membership, MembershipTier, BranchAccess), el flujo de onboarding de gimnasios con registro pendiente y pago inicial, la lista blanca de clientes y los endpoints de preferencias de notificación, dejando especificado el contrato REST correspondiente. Redacté además la documentación del interceptor global HTTP 401/403 y de las validaciones de autenticación reforzadas para el cierre del proyecto.<br><br>**Limache Coronel, Imanol Fabrizio**<br>**TB2:** Documenté el Bounded Context de Alerts (modelo de severidad, resolución de alertas) y su integración con los sensores de movimiento, cámara y seguimiento de sesión, dejando registrados los endpoints `/api/v1/alerts` en la tabla de servicios web. Redacté asimismo la documentación de la interfaz de asignación de técnicos de mantenimiento y del seguimiento de sesiones de rutina, apoyando con reportes escritos de mis pull requests durante la incorporación a mitad de ciclo. | La documentación elaborada destacó por su rigor profesional, precisión técnica y enfoque orientado al usuario. La combinación de diagramas arquitectónicos complejos (C4, DDD), artefactos UX (Journey Maps, Personas, User Flows y Wireframes) y documentación técnica permitió consolidar una única fuente de verdad para el proyecto. Durante el TB1, esta competencia se fortaleció mediante la documentación de pipelines CI/CD, despliegues en Azure, endpoints del Mock API y backlog técnico, evidenciando la capacidad del equipo para comunicar información técnica compleja de manera clara y comprensible para distintos tipos de audiencia. Durante el AV2, esta competencia se consolidó con la documentación del backend real en Spring Boot —incluyendo contratos REST, evidencias de integración y despliegue— y la síntesis de los aprendizajes de los tres sprints en las Conclusiones y Recomendaciones finales del informe, demostrando madurez en la comunicación escrita técnica y de producto a lo largo de todo el ciclo de desarrollo.                                                           |
