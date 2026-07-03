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

<center>
<table>
  <thead>
    <tr><th>Código</th><th>Apellidos y Nombres</th></tr>
  </thead>
  <tbody>
    <tr><td>u20241d317</td><td>Atoche Gonzales, Nicolas Fernando</td></tr>
    <tr><td>u202411310</td><td>Azama Fukuda, Juan Pablo</td></tr>
    <tr><td>u202413214</td><td>Cataño Zárate, Jesús Miguel</td></tr>
    <tr><td>u202414928</td><td>Fernández Linares, Alvaro Sebastian</td></tr>
    <tr><td>u202410344</td><td>Espinoza Orrego, Valentino Andre</td></tr>
  </tbody>
</table>
</center>

<br>

<p align="center"><strong>Período 202610</strong></p>

<p align="center"><strong>Junio 2026</strong></p>

</div>

---

\newpage

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|--------|------|------|-----------------------------|
|1.0.0 | 25/04/26 | Azama, Atoche, Cataño, Espinoza, Fernández | Se realizaron todos los incisos realizados a Lean UX, Needfidining, UI/UX Design y DDD|
|2.0.0 | 10/05/26 | Azama, Atoche, Cataño, Espinoza, Fernández | Se completó el despliegue de la Landing Page en GitHub Pages con todas sus secciones (Hero, Features, Pricing, Contact, Footer). Se implementó el desarrollo frontend de la Web Application en Angular con Fake RESTful API (JSON Server desplegado en Azure), cubriendo los bounded contexts de Equipment, IoT Monitoring, Heatmap, Authentication, Maintenance, Analytics, Routines y Booking. Se documentó el Sprint 2 Planning, Aspect Leaders, Sprint Backlog, Development Evidence, Services Documentation y Software Deployment Evidence. Se aplicó la corrección de artefactos pendientes del Sprint 1, incluyendo diagrama ERD, diagrama de clases, Big Picture EventStorming, evidencias de colaboración y estandarización de entrevistas. Se incorporaron las secciones de Conclusiones y Recomendaciones para ambos sprints. |
|3.0.0 | 19/06/26 | Azama, Atoche, Cataño, Espinoza, Fernández | Se implementó el desarrollo backend de la Web Application con Spring Boot, conectando los servicios reales a las vistas Angular desarrolladas en el Sprint 2. Se desplegó una nueva versión de la Landing Page con mejoras de contenido y se actualizó el frontend con las correcciones pendientes del Sprint 2. Se realizaron entrevistas de validación con representantes de ambos segmentos objetivo (administradores y clientes de gimnasio). Se documentó el Sprint 3 Planning, Aspect Leaders, Sprint Backlog, Development Evidence, Validation Interviews y Software Deployment Evidence. Se incorporaron las Conclusiones y Recomendaciones del Sprint 3. |

---



## Project Report Collaboration Insights

URL del Repositorio spottrack-report: (https://github.com/SpotTrack-1ASI0729-2610-11881/spottrack-report.git)

![](../assets/Insights/report.png)
---

\tableofcontents

---

## Student Outcome
| Criterio específico                                                        | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Conclusiones                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| :------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Comunica oralmente con efectividad a diferentes rangos de audiencia.**   | **Azama Fukuda, Juan Pablo**<br>**AV1:** Dirigí las sesiones de sincronización del equipo, explicando la visión del proyecto y asignando responsabilidades para la estructuración inicial de Lean UX y la arquitectura de la Landing Page. Articulé las metas del Sprint Planning de manera clara para alinear el trabajo del equipo de desarrollo.<br>**TB1:** Lideré la reunión de Sprint 2 Planning, exponiendo ante el equipo la estrategia dual de trabajo: correcciones del Sprint 1 en paralelo al inicio del desarrollo del frontend Angular. Presenté la arquitectura de carpetas por Bounded Context (`auth/`, `heatmap/`, `equipment/`, `maintenance/`) y argumenté su alineación con el Domain-Driven Design previamente modelado. Expliqué asimismo el funcionamiento del JSON Server desplegado en Azure como Fake API compartida, articulando cómo una URL pública elimina problemas de integración entre entornos de desarrollo.<br>**AV2:** Lideré la reunión de Sprint 3 Planning, comunicando al equipo la estrategia de transición del Fake API al backend real en Spring Boot y coordinando los frentes de trabajo de backend, actualización del frontend y nueva versión de la Landing Page. Coordiné las sesiones de entrevistas de validación, explicando a los participantes de ambos segmentos (administradores y clientes de gimnasio) el propósito y alcance de la evaluación con un lenguaje accesible y libre de tecnicismos. Expuse los resultados de las entrevistas al equipo, adaptando el nivel de detalle técnico según el interlocutor para facilitar decisiones de mejora de producto.<br><br>**Atoche Gonzales, Nicolas Fernando**<br>**AV1:** Lideré la exposición técnica de la arquitectura de contenedores (C4 Model) ante el equipo de desarrollo, detallando la integración entre los nodos IoT Edge y el backend en Spring Boot. Expliqué la lógica de los triggers de auditoría en SQL Server para asegurar que los stakeholders comprendieran los mecanismos de integridad de datos.<br>**TB1:** Participé activamente en las reuniones de planificación del Sprint 2, asumiendo responsabilidades en backend e infraestructura. Me encargué del despliegue del Mock API en Azure como App Service, garantizando una URL pública estable para la integración frontend. Desarrollé los bounded contexts y corregí la nomenclatura de la base de datos para alinearla con los estándares del proyecto. Asimismo, comuniqué mis avances y bloqueos técnicos de manera oportuna para facilitar la coordinación entre equipos.<br><br>**Espinoza Orrego, Valentino Andre**<br>**AV1:** Expuse los resultados del análisis del problema, entrevistas y validación de la solución, adaptando el mensaje tanto para usuarios finales como para administradores de gimnasios. Expliqué el valor de la propuesta (mapas de calor, IoT y mantenimiento predictivo), facilitando la comprensión técnica y comercial según la <br>**TB1:** Participé en la explicación y validación de wireframes, mockups, user flows y prototipos de la aplicación web, comunicando de forma clara las decisiones de diseño y navegación tanto al equipo técnico como a usuarios relacionados con el proyecto. Además, durante la implementación de la landing page UI Design, adapté la explicación de funcionalidades y flujos según el tipo de audiencia, facilitando la comprensión de la propuesta visual y funcional del sistema.<br><br>**Fernández Linares, Alvaro Sebastian**<br>**AV1:** Dirigí las sesiones de diseño y estructuración del frontend, sustentando las decisiones de Interfaz de Usuario (UI) ante el equipo de desarrollo. Expliqué de forma clara la aplicación de principios Lean UX y evaluaciones heurísticas, adaptando el lenguaje para asegurar la comprensión de los requerimientos de negocio de SpotTrack.<br>**TB1:** Durante las reuniones de planificación y sincronización del equipo, expuse la estrategia de desarrollo e integración para los Bounded Contexts asignados (`alerts`, `reservation`, `dashboard`) dentro de la WebApp. Argumenté la importancia de priorizar `reservation` como Core Domain de la solución y expliqué la estrategia de mitigación para las correcciones del Sprint 1, detallando además el flujo de navegación y redirección entre la Landing Page y la WebApp desplegada en Azure. <br><br>**Cataño Zárate,Jesús Miguel**<br>**AV1** Dirigi la segmentacion del trabajo en microtareas con Trello, maneje el blindaje de repositorios apoyando a mis compareños en la orientacion de los convetional commits, ademas de apoyar en la revision del documento.<br> **TB1:** Durante las reuniones de planificacion, aporte en el desarrollo de la Landing page (`Contact section`,`footer section`), en la web app desarrolle las secciones asignadas (`profile`, `alerts`). Ademas de testear y comunicar los cambios requeridos de otras partes del documento y aplicacion | Se logró establecer una comunicación oral efectiva que permitió articular con claridad la visión técnica y comercial de SpotTrack. A través de sesiones de planificación, exposiciones de arquitectura, validaciones con usuarios y sustentación de decisiones de diseño UI, el equipo demostró capacidad para adaptar el lenguaje a diferentes audiencias, tanto técnicas como administrativas y usuarios finales. Durante el TB1, esta competencia se fortaleció mediante la explicación de decisiones de arquitectura frontend, despliegue en Azure, integración mediante Fake APIs y organización basada en Domain-Driven Design, garantizando la alineación del equipo en los distintos frentes del Sprint 2. Durante el AV2, la comunicación oral evolucionó hacia la coordinación de entrevistas de validación con ambos segmentos objetivo y la presentación de resultados al equipo, demostrando la capacidad de traducir hallazgos de usuario en decisiones de mejora de producto comprensibles para audiencias técnicas y no técnicas. |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia.** | **Azama Fukuda, Juan Pablo**<br>**AV1:** Redacté y estructuré el documento *Sprint Planning 1*, documentando asignaciones de tareas y configuración del entorno de desarrollo. Desarrollé la arquitectura de información utilizando Markdown y jerarquías visuales para facilitar la lectura técnica.<br>**TB1:** Redacté el *Sprint 2 Planning*, la tabla de *Aspect Leaders* y el *Sprint Backlog*, documentando tareas CORR, SETUP, User Stories y Technical Stories con estimaciones, responsables y estados. Documenté además el pipeline CI/CD en GitHub Actions para el despliegue de la Landing Page y la WebApp, así como los endpoints del Mock API y las URLs de producción.<br>**AV2:** Redacté el *Sprint 3 Planning*, la tabla de *Aspect Leaders* y el *Sprint Backlog*, documentando las tareas de desarrollo backend, correcciones del Sprint 2, entrevistas de validación y nueva versión de la Landing Page con responsables y estados. Documenté los contratos REST del backend desplegado en Spring Boot, detallando rutas, métodos HTTP y ejemplos de respuesta para guiar la integración con el frontend Angular. Actualicé la sección de Conclusiones y Recomendaciones del informe, sintetizando los aprendizajes técnicos y de producto obtenidos a lo largo de los tres sprints del proyecto.<br><br>**Atoche Gonzales, Nicolas Fernando**<br>**AV1:** Documenté la arquitectura de software bajo estándares de Domain-Driven Design (DDD) y el modelo C4. Redacté especificaciones técnicas de procedimientos almacenados y triggers de base de datos, además de estructurar las User Stories técnicas enfocadas en persistencia y analítica.<br>**TB1:** Documenté los endpoints del Mock API desplegado en Azure, detallando rutas, métodos HTTP y ejemplos de respuesta para facilitar el consumo por parte del frontend. Corregí la documentación de la base de datos y actualicé el diagrama C4 del backend para reflejar correctamente los contenedores y sus interacciones tras los ajustes de despliegue.<br><br>**Espinoza Orrego, Valentino Andre**<br>**AV1:** Documenté de manera estructurada el proceso de segmentación, entrevistas, user personas, journey maps y requerimientos. Elaboré entregables como el análisis competitivo y el glosario, asegurando claridad tanto para perfiles técnicos como de gestión. <br>**TB1:** Documenté y estructuré los wireflow diagrams, user flows y prototipos de la aplicación web para representar de manera clara la lógica de navegación y experiencia de usuario del proyecto. Asimismo, apoyé en la elaboración y organización de contenidos relacionados con el diseño e implementación de la landing page, asegurando una comunicación escrita comprensible tanto para el equipo de desarrollo como para stakeholders no técnicos.<br><br>**Fernández Linares, Alvaro Sebastian**<br>**AV1:** Redacté y estructuré la documentación de experiencia de usuario utilizando Markdown y jerarquías visuales. Elaboré artefactos de diseño como guiones de entrevistas, User Flows y Wireframes para servir como guía de implementación técnica.<br>**TB1:** Documenté la estructura e implementación de los Bounded Contexts (`alerts`, `reservation`, `dashboard`) dentro de la WebApp, detallando responsabilidades y componentes para asegurar la mantenibilidad del sistema. También redacté el reporte de correcciones del Sprint 1 y la documentación relacionada con el flujo de integración y despliegue entre la Landing Page y la infraestructura en Azure. <br><br>**Cataño Zárate, Jesús Miguel**<br>**AV1:** Documenté y estructuré las microtareas en el tablero de Trello, redactando descripciones claras y criterios de cumplimiento para el equipo. Además, redacté las guías de uso de *conventional commits* para estandarizar el historial del repositorio en GitHub y dejé retroalimentación escrita y estructurada durante la revisión del documento principal para asegurar su legibilidad técnica.<br>**TB1:** Redacté el detalle técnico y la documentación de los *pull requests* correspondientes a las secciones implementadas en la Landing Page (`Contact section`, `footer section`) y la WebApp (`profile`, `alerts`). Asimismo, reporté por escrito los hallazgos de las sesiones de testing, documentando de manera precisa las incidencias y los cambios requeridos en el documento y la aplicación para facilitar el seguimiento asíncrono por parte de los desarrolladores. | La documentación elaborada destacó por su rigor profesional, precisión técnica y enfoque orientado al usuario. La combinación de diagramas arquitectónicos complejos (C4, DDD), artefactos UX (Journey Maps, Personas, User Flows y Wireframes) y documentación técnica permitió consolidar una única fuente de verdad para el proyecto. Durante el TB1, esta competencia se fortaleció mediante la documentación de pipelines CI/CD, despliegues en Azure, endpoints del Mock API y backlog técnico, evidenciando la capacidad del equipo para comunicar información técnica compleja de manera clara y comprensible para distintos tipos de audiencia. Durante el AV2, esta competencia se consolidó con la documentación del backend real en Spring Boot —incluyendo contratos REST, evidencias de integración y despliegue— y la síntesis de los aprendizajes de los tres sprints en las Conclusiones y Recomendaciones finales del informe, demostrando madurez en la comunicación escrita técnica y de producto a lo largo de todo el ciclo de desarrollo.                                                           |

# Capítulo I: Introducción

## Startup Profile

### Descripción de la Startup

**Descripción general:**
SpotTrack nace para cerrar la brecha entre la gestión tradicional de recintos deportivos y la innovación tecnológica impulsada por el Internet de las Cosas (IoT). Somos una startup comprometida con la optimización de los activos físicos y la mejora de la experiencia del usuario en gimnasios, asegurando que la toma de decisiones basada en datos reemplace a la intuición, maximizando la rentabilidad y la satisfacción del cliente.

**Misión:**
La misión de SpotTrack es ofrecer un servicio inteligente de monitoreo y analítica de uso de equipos deportivos, orientado a gimnasios y centros de fitness universitarios. Buscamos optimizar sus procesos operativos y de mantenimiento mediante el uso de IoT (cámaras con visión computacional y sensores en el Edge) para transformar el uso físico de las máquinas en datos accionables gestionados eficientemente en la nube.

**Visión:**
La visión de SpotTrack es ser la plataforma líder en telemetría y gestión de activos deportivos en Perú, promoviendo una administración moderna y predictiva que impulse a los gimnasios hacia una transformación digital eficiente y a la vanguardia de la tecnología.

### Perfiles de integrantes del equipo

![foto-juan-pablo-azama](../assets/foto-juan-pablo-azama.png)

Soy **Juan Pablo Azama Fukuda** (Código: u202411310), estudiante de quinto ciclo de Ingeniería de Software. En el ámbito técnico, poseo una base sólida en lenguajes como C++, Java y Unity. Para este proyecto, mi contribución principal tendrá un foco en la parte de diseño/frontend de la aplicación, tanto en la aplicación web y el landing page. Para ello, me respaldo en mis conocimientos decentes en Figma, HTML y CSS, además de mi manejo de React.js, competencias que seguiré escalando a lo largo del curso. A nivel de gestión, asumo el rol de team leader, con la responsabilidad de articular los esfuerzos del equipo, guiar el desarrollo y garantizar una metodología de trabajo eficiente.

![foto-alvaro-f](../assets/foto-alvaro-f.png)

Soy **Alvaro Sebastian Fernanadez Linares** (codigo: u202414928), estudiante de 5to ciclo de Ingeniería de Software. Cuento con un nivel intermedio en C++ y bases sólidas en Java, lenguajes que me han permitido especializarme en el desarrollo backend, enfocándome en la lógica de negocio y la funcionalidad del servidor. Me defino como una persona responsable, organizada y con una fuerte orientación al trabajo en equipo y la eficiencia. Para este ciclo, mi objetivo en Desarrollo de Aplicaciones Open Source es trasladar mi experiencia en desarrollo estructurado hacia entornos colaborativos. Aspiro a integrar mis habilidades técnicas con la filosofía de código abierto para crear soluciones que no solo sean eficientes, sino también accesibles y transparentes, entendiendo que el futuro de la ingeniería de software se construye colectivamente.
![foto-valentino](../assets/foto-valentino.jpeg)

Soy **Valentino Andre Espinoza Orrego** (código: u202410344), "Estudiante de Ingeniería de Software en la UPC apasionado por la tecnología y el aprendizaje constante. Me especializo en potenciar mis capacidades técnicas y analíticas, trabajando colaborativamente para resolver problemas con eficiencia. Busco oportunidades prácticas donde aplicar mis conocimientos, contribuir responsablemente y desarrollar soluciones funcionales de alto impacto

![foto-nicolas](../assets/foto-nicolas.png)

Soy **Nicolas Fernando Atoche Gonzales** (código: u20241d317), actualmente estoy en el quinto ciclo de la carrera de ingeniería de software. Poseo un conocimiento básico/intermedio en programación con C++, java y Lua. Además, cuento con conocimientos en el desarrollo de videojuegos. Dentro del equipo, estoy encargado en el desarrollo del backend  del proyecto. A su vez suelo orientarme por el conocimiento y el pensamiento lógico, con lo cual suelo buscar la solución más óptima y ágil dentro de un problema a través de pasos sencillos y definidos que construyan una base sólida donde pueda desarrollar respuestas claras y efectivas.

![foto-jesus](../assets/foto-jesus-c.png)

Soy **Jesús Miguel Cataño Zárate**, (Codigo: u202413214). Actualmente estudio el 5to ciclo de Ingeniería de Software. Cuento con un nivel intermedio en C++,C# y experiencia usando Java, para desarrollos moviles y HTML,JS,Node.Js en cuanto a paginas web. 
Mi aporte al equipo, a nivel técnico, contribuyo en el desarrollo creación de arquitecturas escalables y eficientes. Por otro lado, desempeño el rol de Team Leader dentro de mi grupo, asumiendo la responsabilidad de guiar y coordinar al equipo para trabajar de manera efectiva.

## Solution Profile

### Antecedentes y problemática

La gestión operativa y el mantenimiento de equipos en centros deportivos representan un desafío crítico en la actualidad. Una administración deficiente, caracterizada por el desconocimiento del estado real y la disponibilidad de las máquinas, desencadena consecuencias operativas y financieras severas para las empresas. De acuerdo con ResQ (s.f.), cuando se producen fallas repentinas en los equipos por falta de monitoreo, los costos de reparación suelen ser entre 3 y 5 veces más altos en comparación con los gastos de un mantenimiento preventivo programado.

Además del impacto económico directo, la experiencia del cliente se ve profundamente perjudicada. El 70% de los usuarios finales manifiesta una alta insatisfacción al descubrir que su máquina preferida se encuentra averiada en el momento de su entrenamiento (Athletic Business, 2024, como se citó en DINGG, 2025). Esta falta de visibilidad impide que los usuarios organicen su tiempo adecuadamente, generando desánimo e incrementando significativamente la probabilidad de que cancelen sus suscripciones. Paralelamente, para la administración del establecimiento, esta carencia de información centralizada y en tiempo real se traduce en una planificación de mantenimiento ineficiente y en una toma de decisiones imprecisa respecto a la reubicación, reparación o compra de nuevos equipos.


**What (Qué):**

El problema es la baja administración que se le dan a las máquinas, de tal manera que se ignoran el estado y disponibilidad de estas. Según ResQ (s.f), las fallas repentinas de las máquinas ocasionan que los costos de reparación sean 3 o 5 veces más caros de lo normal. Por otro lado, el 70% de usuarios finales muestran insatisfacción cuando su máquina preferida está dañada (Athletic Business, 2024, como se citó en DINGG, 2025).
Esto repercute en que los usuarios finales no tengan la capacidad de organizar su tiempo adecuadamente al no saber si una máquina está disponible o si está en mantenimiento. Incluso, es posible que se desanimen y cancelen su suscripción. Por otro lado, con respecto a la administración, la planificación del mantenimiento y la toma de decisiones fundamentadas sobre la compra o reubicación de equipos termina siendo imprecisa.
https://dingg.app/blogs/your-5-step-operational-plan-to-handle-equipment-failures

**When (Cuándo):**

El problema surge y se intensifica drásticamente durante las "horas pico" de los gimnasios (generalmente temprano por la mañana y después de las 6:00 PM). En estos momentos, los usuarios deben lidiar con instalaciones abarrotadas y disputar el uso de máquinas populares (como trotadoras o racks de sentadillas), lo que implica tiempos de espera que rompen el ritmo de sus entrenamientos.
Desde la perspectiva administrativa, el problema del mantenimiento surge de forma imprevista. Las roturas de cables o fallos de motor en máquinas cardiovasculares ocurren súbitamente en medio de la operación diaria, obligando a poner carteles de "Fuera de Servicio" que generan malestar general.

**Where (Dónde):**

El principal lugar donde se encuentran los mayores clientes potenciales sería en las cadenas de gimnasios de tamaño mediano y grande en Lima, así como en centros deportivos universitarios. Estos establecimientos poseen una gran cantidad de activos costosos distribuidos en espacios amplios y, en muchos casos, cuentan con múltiples sedes, lo que dificulta bastante el control manual de qué se usa, cuánto se usa y dónde hace falta más equipamiento.

**Who (Quién):**

El problema afecta principalmente a dos grupos bien definidos: los administradores de los gimnasios y los usuarios/clientes (feligreses del fitness).
Por un lado, los administradores y dueños lidian con presupuestos ajustados. Al no tener telemetría, deben adivinar cuándo hacer mantenimiento o qué máquinas comprar. Esto representa una gran dificultad operativa y un riesgo de pérdida económica por mala gestión de activos.
Por otro lado, los usuarios se ven directamente afectados por la falta de disponibilidad. Llegan al local y deben caminar por todo el recinto buscando una máquina libre, lo cual genera estrés y pérdida de tiempo.
La solución que proponemos está pensada para que los administradores utilicen un dashboard analítico que les alerte de mantenimientos y muestre estadísticas de uso. Asimismo, está diseñada para que los clientes, mediante una app móvil, puedan consultar la "temperatura" (disponibilidad) de las máquinas en tiempo real antes de salir de casa o mientras están en el local.

**Why (Por qué):**

En primer lugar, la principal causa del problema es la carencia de sistemas de telemetría e IoT en los gimnasios tradicionales. La gestión se basa en la observación visual de los entrenadores y en reportes manuales cuando algo ya falló. Esto puede confirmarse gracias a MantainNow (2025), un error común de las organizaciones es que el mantenimiento que se realiza es reactivo. Es decir, se efectúa una vez el daño ya está hecho.

https://www.maintainnow.app/learn/guides/mro-maintenance-repair-operations-a-practical-guide

En segundo lugar, otro factor es la incapacidad de procesar datos de flujo de personas en tiempo real. Aunque algunos gimnasios tienen torniquetes de ingreso, esto solo indica cuánta gente hay en el local, pero no indica qué están usando. En consecuencia, la gestión de la capacidad se vuelve deficiente, haciendo que los clientes pierdan tiempo y que los administradores presenten dificultades para optimizar sus locales. Esto lo confirma Rework (s.f), en donde menciona que el aforo no debería percibirse por cantidad si no por acumulación de usuarios en las máquinas. O sea, 78 personas pueden encontrarse dentro de un local con un aforo de 100 personas. No obstante, estas se agruparán en máquinas específicas, dejando el resto con un porcentaje de uso significativamente menor.

**How (Cómo):**

La plataforma funcionará mediante un sistema dual (Web App para usuarios y Dashboard para administradores) alimentado por dispositivos IoT. En las instalaciones se utilizarán cámaras simples con reconocimiento en el Edge (o sensores de uso) que solo enviarán datos de estado (Ocupado/Libre) y tiempo a nuestra base de datos, respetando la privacidad (no se graba video).
La mayoría de los clientes preferirán acceder mediante dispositivos móviles, por lo que la interfaz en Angular será responsiva. Verán un catálogo de máquinas agrupadas por tipo (Cardio, Pesas, etc.) con indicadores de colores (ej. Verde: Libre, Rojo: Ocupado) como un mapa de calor.
Los administradores ingresarán mediante un login seguro (JWT) a un panel donde visualizarán gráficos de barras de uso histórico, alertas de "Mantenimiento requerido (Límite de 500 horas superado)", y recomendaciones para reubicar equipos poco usados.

**How much (Cuánto):**

La ineficiencia en la gestión de activos dentro de los centros fitness desencadena un impacto financiero que compromete severamente la rentabilidad del negocio. En primer lugar, la dependencia de un modelo reactivo infla el Sobrecosto Operativo (OPEX), dado que la ejecución de mantenimientos correctivos de emergencia resulta entre 3 a 5 veces más costosa que una estrategia preventiva planificada (Oxmaint, 2023). Este sobrecosto se agrava con la Depreciación Acelerada de Activos (CAPEX) considerando que el equipamiento cardiovascular comercial exige inversiones iniciales de $3,000 a $8,000 USD por unidad (Top Fitness, 2024), una falla correctiva mayor (como el reemplazo de un motor AC por fricción) puede consumir hasta el 40% de su valor residual, fulminando el Retorno de Inversión (ROI) proyectado. Finalmente, esta precariedad logística golpea el indicador más crítico: la retención. Con una tasa de abandono (Churn Rate) anual de la industria que oscila entre el 30% y el 40%, la inoperatividad de los equipos y la consecuente congestión de los locales se posicionan consistentemente en el "Top 3" de motivos de cancelación (Energym, 2023). Sabiendo que el Costo de Adquisición de Clientes (CAC) es 5 veces mayor que el costo de retenerlos (IHRSA, 2023), el downtime constante de las máquinas puede convertirse en una fuga de capital insostenible.

Energym. (2023). *Why do gym members cancel their memberships?* https://energym.io/blogs/braingains/why-do-gym-members-cancel-their-memberships

Oxmaint. (2023). *Corrective vs. preventive work orders*. https://www.oxmaint.com/blog/post/corrective-vs-preventive-work-orders

Top Fitness Store. (2024). *Commercial & professional treadmills*. https://www.topfitness.com/collections/commercial-treadmills

### Lean UX Process


#### Lean UX Problem Statements

Nuestro servicio ofrece una plataforma de telemetría y visualización en tiempo real para monitorear el uso, desgaste y disponibilidad de las máquinas de ejercicio. Hemos observado que los gimnasios enfrentan sobrecostos por mantenimientos reactivos y tiempos prolongados de equipos inoperativos, a la par que los usuarios experimentan largos tiempos de espera para entrenar durante las horas pico, reduciendo la tasa de retención. ¿De qué manera podemos visibilizar la ocupación y el estado de los activos para optimizar la planificación preventiva de la gerencia y permitir a los usuarios ejecutar sus rutinas sin tiempos muertos?


#### Lean UX Assumptions

**¿Quién es el usuario?**

Nuestros usuarios principales son los administradores/dueños de gimnasios y los usuarios finales (clientes). El administrador utilizará el sistema para ver reportes y alertas, mientras que el cliente lo usará para ver la disponibilidad en tiempo real.

**¿Dónde encaja nuestro producto en su trabajo o vida?**

Para el cliente, encaja en su rutina diaria de planificación de entrenamiento (antes de ir al gimnasio o mientras descansa entre series). Para el administrador, es una herramienta de gestión diaria y de planificación financiera mensual.

**¿Qué problemas tiene nuestro producto que resolver?**

La saturación de máquinas, la pérdida de tiempo de los usuarios, las averías imprevistas de equipos costosos y la mala distribución del inventario de máquinas entre diferentes locales.

**¿Cuándo y cómo es usado nuestro producto?**

Los clientes lo usarán en sus smartphones principalmente en horas pico o minutos antes de dirigirse al local. Los administradores lo usarán en computadoras de escritorio o tablets durante su jornada laboral para revisar el estado del local.

**¿Qué características son importantes?**

Mapa de calor de disponibilidad en tiempo real, registro automático de horas de uso vía IoT, notificaciones de mantenimiento predictivo, panel estadístico de máquinas más/menos usadas, e interfaz responsiva.

**¿Cómo debe verse nuestro producto y cómo debe comportarse?**

Debe tener un aspecto moderno, deportivo y ágil. Para los usuarios, debe ser extremadamente visual (uso de semaforización: verde, amarillo, rojo). Para los administradores, debe lucir como una herramienta profesional y gerencial (dashboards claros, tablas ordenadas y alertas visibles).

**Creo que mi cliente necesita** una mejora en la organización de sus tiempos de rutina y, por el lado administrativo, una reducción en costos de mantenimiento.

**Estas necesidades se pueden resolver con** la implementación de nuestra plataforma IoT de telemetría y mapas de calor.

**Nuestros clientes iniciales son** las cadenas medianas de gimnasios en Lima, regiones cercanas a Lima y centros deportivos universitarios.

**El mayor valor que prioriza** mi cliente (usuario) es no hacer filas; y para el administrador, maximizar la vida útil de sus activos y tener menos pérdidas.

**El cliente también puede obtener beneficios adicionales** como tener certeza de cómo invertir su capital de manera más precisa, enfocar la labor operativa del staff hacia los clientes en vez de perder tiempo en la inspección de máquinas. Esto es por la parte administrativa. Por otro lado, con respecto a los usuarios finales, estos podrán tomar decisiones más inteligentes a la hora de planificar sus rutinas, lo que mejora drásticamente la conveniencia y la utilidad percibida de su membresía.

**Obtendremos clientes** ofreciendo un piloto gratuito de un mes instalando hardware básico en una zona específica (ej. zona de cardio) para demostrar el valor de la data obtenida.

**Generamos ingresos mediante** un modelo B2B SaaS: cobramos a los gimnasios una suscripción mensual por el uso del panel analítico y un costo de instalación inicial del hardware IoT.

**Nuestra competencia principal** serían las aplicaciones genéricas de reservas de gimnasios, pero los venceremos mediante nuestro valor diferencial. No requerimos que el usuario reserve una máquina manualmente, sino que usamos hardware IoT (cámaras/sensores) para reportar la realidad de forma automática y pasiva.

**Los venceremos** debido a que proponemos una solución utilizando diversos dispositivos IoT que permiten una recopilación de datos eficiente, además de que estos datos luego son convertidos a mapas de calor y gráficos estadísticos. Todo esto permite mejorar la administración de las máquinas y la satisfacción del cliente, lo que significa más ingresos y menos pérdidas para la empresa.

**Nuestros mayores riesgos** son la complejidad en la instalación física del hardware y la dependencia de la red Wi-Fi del local. 

**Esto lo resolveremos** utilizando protocolos ligeros y dispositivos que puedan guardar temporalmente la data si se cae la red.

**Otras suposiciones** que tenemos es que ciertos gimnasios ya tengan este tipo de sistemas o que cierta maquinaria venga con telemetría ya incluída. En consecuencia, nuestra idea carecería de valor. Por ende, es importante tener en mente que si un gimnasio ya posee este sistema debemos proponer una mejora.

#### Lean UX Hypothesis Statements

Hipótesis 1: 
**Creemos que** implementar un mapa de calor en tiempo real en una web app (Angular) para los clientes del gimnasio logrará reducir su nivel de frustración por aglomeraciones.

**Sabremos que** tendremos exito

**Cuando veamos** que la desviación estándar de la asistencia por hora se reduce en un 15%, indicando una distribución de usuarios más uniforme durante el día.

Hipótesis 2: 

**Creemos que** automatizar el conteo de horas de uso mediante sensores IoT para los dueños de gimnasios logrará una reducción en los costos operativos.

**Sabremos que** esto se cumplió 

**Cuando veamos** que el gasto mensual en reparaciones de emergencia (correctivas) disminuye en un 20% en un periodo de 3 meses tras la instalación de los sensores.

Hipótesis 3: 

**Creemos que** ofrecer un panel de control que contraste "horas en uso" vs. "horas ociosas" para el administrador del gimnasio logrará decisiones de compra y reubicación de máquinas más eficientes.

**Sabremos que** nuestra solución funcionará 

**Cuando veamos** que el tiempo de uso diario promedio de las máquinas reubicadas aumenta al menos un 25% en su nueva ubicación durante el primer mes.

Hipótesis 4: 

**Creemos que** procesar el reconocimiento de imágenes directamente en el dispositivo (Edge Computing) para el administrador del gimnasio logrará evitar la saturación de la red local.

**Sabremos que** funcionó 

**Cuando veamos** que el consumo de ancho de banda de salida por dispositivo no supera los 50 KBps (enviando solo estados) y el tiempo de respuesta del endpoint en Spring Boot se mantiene bajo los 500ms en el 95% de las peticiones (P95).

#### Lean UX Canvas

# Lean UX Canvas (v2)

**Título de la iniciativa:** SpotTrack   
**Fecha:** 10 de abril de 2026  
**Iteración:** v1 - Basado en Elicitación de Requisitos  

---

## 1. Problema de Negocio (Business Problem)
¿Qué problema tiene el negocio que estás intentando resolver? 

- Los gimnasios tradicionales carecen de telemetría y sistemas IoT, dependiendo de reportes manuales y operando a ciegas sobre la disponibilidad de sus equipos.  
- Esta mala gestión desencadena un modelo reactivo donde los mantenimientos correctivos son entre 3 a 5 veces más caros que los preventivos.  
- Existe una mala distribución de los equipos e inventario, con algunas máquinas subutilizadas y otras sobreexplotadas.  
- Esta ineficiencia causa hacinamiento en "horas pico", generando que el 70% de los usuarios sienta frustración al encontrar máquinas averiadas o muy solicitadas. Esto incrementa la tasa de abandono (Churn Rate), la cual oscila entre el 30% y 40%.  

---

## 2. Resultados de Negocio (Business Outcomes)
¿Cómo sabrás que resolviste el problema del negocio? ¿Qué vas a medir? 

- Se reducirán los gastos en mantenimiento correctivo en un 20% al transicionar hacia mantenimientos preventivos.  
- Disminuirá significativamente la cantidad de equipos reportados como "Fuera de Servicio" (Downtime).  
- Los administradores reubicarán máquinas poco usadas de locales con baja demanda hacia locales con alta demanda.  
- La saturación y el flujo de usuarios en horas pico se distribuirá mejor, reduciéndose en un 15%.  

---

## 3. Usuarios (Users)
¿En qué tipos de usuarios y clientes deberías enfocarte primero? 

- **B2B (Administradores):** Administradores de sedes, Gerentes de Operaciones y técnicos de mantenimiento en cadenas de gimnasios medianas/grandes y centros deportivos universitarios. Manejan presupuestos de OPEX/CAPEX y sienten frustración al operar a ciegas.  
- **B2C (Usuarios finales):** Clientes frecuentes del gimnasio (18-40 años), como estudiantes universitarios u oficinistas, que asisten principalmente en "horas pico", tienen poco tiempo libre y se frustran con las filas y equipos averiados.  

---

## 4. Resultados y Beneficios del Usuario (User Outcomes & Benefits)
¿Por qué tus usuarios buscarían tu producto o servicio?  

- **Para Administradores:** Obtendrán una plataforma predictiva que optimizará el ROI de sus máquinas y les evitará gastos inesperados. Podrán anticipar el desgaste de una máquina y programar su mantenimiento antes de que falle.  
- **Para Usuarios Finales:** Obtendrán previsibilidad y un mejor control de su tiempo, logrando finalizar sus rutinas más rápido al evitar zonas congestionadas.  

---

## 5. Soluciones (Solutions)
¿Qué podemos crear que resuelva el problema?  

- Integración de dispositivos IoT (cámaras con visión computacional en el Edge) para recopilar ocupación respetando la privacidad.  
- Web App (Angular) con un "Mapa de Calor" en vivo que muestra disponibilidad (verde, amarillo, rojo).  
- Dashboard gerencial con tracking automático de horas de uso y paneles estadísticos.  
- Alertas de mantenimiento predictivo y generación automática de tickets técnicos.  
- Motor de sugerencia de rutinas alternativas y sistema de "reserva exprés" de 15 minutos.  

---

## 6. Hipótesis (Hypotheses)

- Creemos que se reducirá el nivel de frustración por aglomeraciones en un 15% si el cliente frecuente obtiene previsibilidad de tiempo mediante un mapa de calor en tiempo real.  
- Creemos que se logrará una reducción de costos operativos si el gerente de operaciones puede anticipar fallas automatizando el conteo de horas de uso con sensores IoT.  
- Creemos que se tomarán decisiones de inversión más eficientes si el administrador obtiene respaldo estadístico mediante paneles de uso vs inactividad.  

---

## 7. ¿Qué es lo más importante que necesitamos aprender primero?

- El mayor riesgo es la viabilidad técnica y logística: instalación del hardware y dependencia de la red Wi-Fi.  
- Validar si los gimnasios ya cuentan con telemetría propia en equipos modernos.  
- Confirmar si los administradores adoptarán mantenimiento predictivo basado en datos.  

---

## 8. ¿Cuál es la menor cantidad de trabajo para aprender lo siguiente?

- Ejecutar un piloto gratuito de 30 días instalando hardware en una zona crítica del gimnasio.  
- Medir uso real del sistema, adopción del mapa de calor y validar el retorno de inversión antes de lanzar el modelo SaaS.  



## Segmentos objetivo

El modelo de negocio es B2B2C (Business to Business to Consumer), por lo que identificamos dos segmentos objetivo principales:
Administradores y Gerentes de Operaciones
Aspectos demográficos:
Sexo: Masculino o femenino.
Edad: 30 – 55 años.
Nivel socioeconómico: A, B y C (alta, media-alta).
Ocupación: Gerentes de operaciones, jefes de mantenimiento o administradores de sede.
Aspectos geográficos:
Nacionalidad: Peruana o extranjera.
Zona geográfica: Urbana.
Departamento: Lima Metropolitana y ciudades a nivel nacional con presencia de gimnasios comerciales.



Aspectos psicográficos:
Son los responsables directos de rendir cuentas sobre los presupuestos operativos (OPEX) y salvaguardar el valor de los equipos (CAPEX).
Sienten frustración al operar a ciegas y depender de la intuición o reportes en papel.
Buscan herramientas y plataformas que les permitan tomar decisiones basadas en datos duros, ahorrar dinero y evitar los mantenimientos de emergencia.
Clientes frecuentes de gimnasio 
Aspectos demográficos:
Sexo: Masculino o femenino.
Edad: 18 – 40 años.
Nivel socioeconómico: A, B, C y D (transversal, dependiendo si asisten a sedes premium o cadenas low-cost).
Ocupación: Estudiantes universitarios, oficinistas y profesionales jóvenes.
Aspectos geográficos:
Nacionalidad: Peruana o extranjera.
Zona geográfica: Urbana.
Departamento: Lima Metropolitana y ciudades a nivel nacional con presencia de gimnasios comerciales.
Aspectos psicográficos:
Tienen una agenda apretada y disponen de poco tiempo libre, obligándolos a entrenar en horarios de alta afluencia (picos de mañana y noche).
Su principal dolor es el tiempo perdido; se frustran rápidamente al encontrar máquinas ocupadas, hacinamiento o equipos con carteles de "fuera de servicio".
Valoran la eficiencia de su rutina y priorizan la operatividad del local por encima de otros factores al decidir si renuevan su membresía.




# Capítulo II: Requirements Elicitation & Analysis

## Competidores

### Análisis competitivo

### 2.1.1. Análisis competitivo

**¿Por qué llevar a cabo este análisis?**
¿De qué manera la integración de hardware IoT Edge para telemetría pasiva otorga a SpotTrack una ventaja competitiva frente a las plataformas tradicionales de gestión de máquinas sin requerir interacción manual del usuario?

| Categoría | Criterio | SpotTrack | Fitco | GYMMaster | Virtuagym |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Perfil** | **Overview** | Plataforma B2B2C con IoT Edge y visión computacional para telemetría pasiva, generación de mapas de calor en vivo y mantenimiento predictivo de maquinaria deportiva. | Software de gestión integral, enfocado en automatizar la facturación, membresías y reservas manuales de clases. | Sistema ERP global diseñado para la gestión de gimnasios con un enfoque crítico en la automatización del control de acceso físico. | Plataforma integral de coaching, gestión de clubes y retención, que combina la administración del recinto con la creación de rutinas 3D y reservas manuales. |
| **Perfil** | **Ventaja competitiva** | Manejo independiente de hardware y recolección de datos, además que no exige al usuario reservar manualmente cada máquina. | Ecosistema maduro de facturación electrónica adaptado a la región y alta familiaridad por parte de los administradores B2B. | Permite el funcionamiento continuo (24/7) de gimnasios sin necesidad de personal de recepción, bloqueando el paso a usuarios deudores. | Ofrece un ecosistema de software extremadamente profundo que hiper-personaliza el entrenamiento del usuario mediante avatares y gamificación social. |
| **Perfil de Marketing** | **Mercado objetivo** | Cadenas de gimnasios medianas y grandes en Lima, y centros deportivos universitarios que sufren por altas congestiones y presupuestos ajustados. | Centros de fitness, centros de yoga, academias de artes marciales y gimnasios que buscan digitalizar su administración básica. | Franquicias de gimnasios comerciales, locales 24 horas y centros deportivos que priorizan la reducción extrema de costos en personal. | Cadenas de gimnasios premium, entrenadores personales independientes y corporaciones que buscan un compromiso total y seguimiento nutricional del usuario. |
| **Perfil de Marketing** | **Estrategias de marketing** | Oferta de pilotos gratuitos de 30 días instalando hardware IoT en zonas críticas, para demostrar el retorno de inversión con datos tangibles. | Estrategias agresivas de Inbound Marketing, webinars para dueños de gimnasios y alianzas estratégicas con pasarelas de pago locales (Niubiz, Culqi). | Posicionamiento SEO agresivo a nivel internacional, demostraciones guiadas de software y venta combinada de su hardware. | Fuerte comunidad en redes sociales, educación gratuita para entrenadores y un modelo freemium en su aplicación móvil para captar usuarios masivamente. |
| **Perfil de Producto** | **Productos & servicios** | Dashboard gerencial B2B para decisiones de CAPEX/OPEX y aplicación web Angular B2C con visualización de aforo en tiempo real. | Plataforma ERP web alojada en la nube para gerencia y aplicación móvil B2C de marca blanca para que los usuarios aparten sus cupos manualmente. | Software Cloud complementado con hardware propietario: lectores RFID, escáneres biométricos de huella dactilar y torniquetes de acceso. | Software de gestión administrativa, motor de creación de rutinas con animaciones 3D, seguimiento de dieta y módulo de reserva de áreas/máquinas. |
| **Perfil de Producto** | **Precios & costos** | Modelo SaaS B2B con membresía mensual desde $69 USD/mes (Basic), $109 USD/mes (Mid), $189 USD/mes (Platinum). | Modelo SaaS con tarifas escalonadas: plan Lite desde $59 USD/mes, Core a $99 USD/mes y Growth a $169 USD/mes. | Costo mensual de licencia desde $89 USD/mes (Foundation), $129 USD/mes (Advanced), $209 USD/mes (Professional), en software only, con software + door accesses va desde $129 USD/mes (Foundation), $169 USD/mes (Advanced), $249 USD/mes (Professional). | Plan base desde $29 USD/mes. Estructura modular donde planes superiores encarecen la solución con precios personalizados. |
| **Perfil de Producto** | **Canales de distribución** | Web y Móvil | Web y Móvil | Web y Móvil | Web y Móvil |
| **Análisis SWOT** | **Fortalezas** | Elimina la incertidumbre del usuario mostrando disponibilidad en vivo y reduce el OPEX por reparaciones. | Interfaz de facturación probada, integración contable robusta y comunidad educada en reservas. | Control de aforo exacto y en tiempo real, erradicación de morosidad mediante barreras físicas. | Excelente gamificación comunitaria y alta capacidad para retener al cliente mediante motivación digital. |
| **Análisis SWOT** | **Debilidades** | Dependencia de la estabilidad de la red Wi-Fi del local y complejidad logística en la instalación física. | Carencia de telemetría de hardware; la medición de ocupación depende de la acción voluntaria del cliente. | Ceguera intramuros: el sistema ignora por completo qué máquinas se usan o si están averiadas. | Su sistema de reservas asume que la máquina está operativa; no detecta averías físicas reales. |
| **Análisis SWOT** | **Oportunidades** | Capitalizar el Churn Rate del 30-40% causado por la inoperatividad de equipos y frustración de filas. | Expandir sus módulos abriendo su API a startups de IoT para ofrecer datos de uso de máquinas. | Desarrollar sensores internos para complementar su dominio de las puertas o adquirir empresas de analítica. | Evolucionar su motor de rutinas para recomendar ejercicios dinámicamente según saturación real. |
| **Análisis SWOT** | **Amenazas** | Gimnasios con maquinaria de última generación con telemetría propietaria preinstalada. | Surgimiento de startups que eliminen el tedioso proceso de reservar manualmente. | Barreras arancelarias para importar hardware especializado y soporte técnico lento. | Exceso de funciones que puede abrumar a usuarios que solo buscan entrenar rápido. |

### Estrategias y tácticas frente a competidores

Desarrollar estrategias y tácticas efectivas para enfrentar a nuestros competidores requiere de un enfoque cuidadoso y planificado. A continuación se presentan algunas estrategias y tácticas que podrían ser consideradas para tener una ventaja competitiva frente a otras alternativas:

**Diferenciación por telemetría pasiva y automatización:** A diferencia de competidores como Virtuagym o Fitco, que dependen de que el usuario reserve manualmente una máquina o clase , SpotTrack se diferencia al eliminar la interacción manual mediante el uso de hardware IoT Edge. Esta ventaja permite recolectar datos reales de uso de forma pasiva, ofreciendo un mapa de calor en vivo que refleja la realidad del local sin errores humanos. Además, se aplicará un modelo B2B SaaS con planes escalables desde los $69 USD mensuales, facilitando el acceso a gimnasios medianos y grandes en Lima.

**Optimización de la rentabilidad y soporte preventivo:** 
Mientras que los sistemas tradicionales presentan una "ceguera intramuros" al ignorar si una máquina está averiada , nuestra táctica principal de acercamiento será demostrar el ahorro directo en el OPEX. Al migrar de un mantenimiento correctivo (que es de 3 a 5 veces más costoso) a uno preventivo y predictivo , los administradores logran maximizar la vida útil de sus activos. Para asegurar la adopción, se ofrecerá un piloto gratuito de 30 días instalando hardware en zonas críticas (como el área de cardio), demostrando el retorno de inversión con datos tangibles antes del cierre de venta.

**Innovación tecnológica enfocada en la privacidad y eficiencia:**
SpotTrack se posicionará como líder en tecnología Edge Computing, procesando el reconocimiento de imágenes directamente en el dispositivo para enviar únicamente paquetes ligeros de datos (JSON) a la nube. Esta táctica no solo evita la saturación de la red Wi-Fi del gimnasio —una de las debilidades identificadas frente a la competencia — sino que garantiza la privacidad total al no grabar ni transmitir video de los usuarios. Esto permite ofrecer un dashboard gerencial con métricas claras y alertas automáticas que superan la funcionalidad de los ERP tradicionales que solo gestionan accesos y membresías.

## Entrevistas

### Diseño de entrevistas

A continuación se presentan las preguntas para las entrevistas a los segmentos objetivos

Segmento 1: Administradores y Gerentes de Operaciones

Antes de las preguntas: Por favor, indícanos la siguiente información para registrar tu participación:
Nombre:
Cargo / Ocupación (confirmar si es administrador de sede o gerente de operaciones)
Edad
Gimnasio / Institución a la que pertenece:

Segmento 1: Administradores y Gerentes de Operaciones
1. Cuéntame sobre tu experiencia actual gestionando el mantenimiento y la disponibilidad de las máquinas en tu sede.
¿Cómo es el proceso exacto desde que una máquina falla hasta que el técnico la repara?
2. ¿Qué impacto financiero y operativo notas cuando una máquina de alta demanda (como una trotadora o rack de sentadillas) se avería repentinamente?
¿Tienen un presupuesto asignado para mantenimiento correctivo de emergencia o afecta directamente la rentabilidad del mes?
3. Durante las "horas pico" (mañanas o después de las 6:00 PM), ¿cómo manejan la congestión del local y las quejas de los usuarios por los tiempos de espera?
4. Si pudieras contar con un "mapa de calor" en tiempo real que te muestre qué máquinas están libres, ocupadas o en mantenimiento, ¿de qué manera utilizarías esa información en tu gestión diaria?
5. ¿Qué tan valioso sería para ti recibir alertas automáticas de "mantenimiento predictivo" (por ejemplo, saber que una cinta de correr superó las 500 horas de uso y necesita revisión) antes de que se rompa?
6. A la hora de tomar decisiones de inversión, como comprar máquinas nuevas o trasladar equipos de una sede a otra, ¿en qué información o reportes te basas actualmente?
¿Te daría más seguridad basar esas compras en estadísticas exactas de uso generadas por sensores?
7.  Si abres tu computadora el lunes por la mañana para revisar cómo le fue a tu local el fin de semana, ¿cuáles son los 3 datos principales que necesitas ver en un dashboard para sentir que tienes el control total?
8. Para implementar este sistema, planeamos usar pequeñas cámaras con procesamiento Edge (que solo detectan si la máquina está ocupada o libre, sin grabar ni guardar video de las personas). ¿Tendrías o crees que tus clientes tendrían alguna preocupación sobre la privacidad con este enfoque?
9. Pensando en tu staff de piso (entrenadores, personal de limpieza), ¿cómo crees que un sistema de alertas automatizado cambiaría la rutina de su día a día?
10. Si te ofrecemos hacer un plan piloto gratuito de SpotTrack durante un mes, instalando los sensores en una zona específica (como la zona de cardio), ¿cuál es el principal resultado o métrica que necesitarías ver para convencerte de pagar una suscripción mensual por el servicio?


Segmento 2: Clientes frecuentes a gimnasios
Antes de las preguntas: Por favor, indícanos la siguiente información para registrar tu participación:
Nombre:
Ocupación (confirmar si es estudiante universitario, oficinista, etc.):
Edad
Gimnasio al que asistes regularmente:

1. Cuéntame cómo es un día típico cuando vas a entrenar en "hora pico". ¿Cuál es tu primera impresión al entrar al área de musculación o cardio?
2. ¿Cómo te afecta anímica y físicamente cuando llegas con el tiempo justo para tu rutina y encuentras tu máquina principal ocupada, o peor aún, con un letrero de "fuera de servicio"?
3. ¿Alguna vez la constante saturación del local o la cantidad de máquinas averiadas ha sido un factor para que consideres cancelar tu membresía o cambiarte de gimnasio? Cuéntame sobre esa experiencia.
4. Si tuvieras una aplicación en tu celular que te mostrara un "mapa de calor" en tiempo real (es decir, ver exactamente qué máquinas están en rojo/ocupadas o verde/libres) antes de salir de tu casa, ¿de qué manera cambiaría la forma en que planificas tu visita al gimnasio?
5. En esos momentos donde tu máquina preferida está inoperativa o muy solicitada, ¿qué tan útil te resultaría que una aplicación te sugiera automáticamente una rutina alternativa con pesas libres para no perder tu ritmo de entrenamiento?
6. En nuestro proyecto estamos considerando un sistema de recompensas. ¿Qué tipo de beneficios (descuentos en membresía, suplementos, mercadería) te motivarían a actualizar manualmente en la app el estado de una máquina cuando terminas de usarla?
7. Para los equipos de altísima demanda (como poleas cruzadas o racks), ¿qué opinas de una función de "reserva exprés" que te permita separar un espacio de 15 minutos exclusivamente durante las horas de mayor afluencia?
8. ¿Te generaría valor recibir notificaciones automáticas (tipo push) en tu celular avisándote que esa trotadora o máquina que reportaste como malograda la semana pasada ya volvió a estar operativa? ¿Por qué?
9. Considerando que estarías usando esta aplicación en medio de tu entrenamiento, sudando y con poco tiempo para mirar el celular, ¿qué características visuales o de diseño considerarías obligatorias para que te resulte cómoda y rápida de leer?
10. Si tu gimnasio actual te ofreciera esta plataforma de forma totalmente gratuita a partir de mañana, ¿cuál crees que sería el principal obstáculo o motivo por el que quizás no llegarías a usarla todos los días?



### Registro de entrevistas

**Segmento 1: Administrador de Gimnasio y Gerente de Operaciones**

### Entrevista 1: Alexander Gutierrez

| Campo | Detalle |
| :--- | :--- |
| **Entrevistado** | Alexander Gutierrez |
| **Imagen** | ![EntrevistaAlexander](../assets/EntrevistaAlexander.jpeg){width=80%} |
| **Edad** | 31 |
| **Ocupación** | Administrador de Gimnasio |
| **Link** | [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410344_upc_edu_pe/IQBBYSV6pNzzQ48c_MHCmckZAYkuHJqXvA903HKeH3NJKPw?e=sB9lLZ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410344_upc_edu_pe/IQBBYSV6pNzzQ48c_MHCmckZAYkuHJqXvA903HKeH3NJKPw?e=sB9lLZ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| **Resumen** | La entrevista presenta a Alexander Gutiérrez, Administrador de gimnasio en Sport Life La Molina, quien comenta que el mantenimiento actual es rápido, salvo cuando requieren repuestos importados. Reconoce que gestionan la congestión en horas pico ofreciendo ejercicios alternativos o pesos libres a los clientes. Señala que un mapa de calor le ayudaría a prever la demanda específica de ciertos días, y que las alertas automáticas de mantenimiento predictivo serían magníficas para anticipar el desgaste de piezas clave (como las fajas de las trotadoras) antes de que se rompan. En cuanto al panel de control, Alexander valora métricas sobre asignación de rutinas, ingreso de invitados y comentarios de post-venta. Considera que la tecnología de cámaras podría generar reservas en adultos mayores, aunque sería bien aceptada por los jóvenes. Finalmente, destaca que un piloto gratuito lo convencería de pagar la suscripción si en 30 días arroja datos precisos sobre los horarios pico y el uso de máquinas de alta demanda, justificando así futuras compras y optimizando la gestión del local. | 


### Entrevista 2: Luis Romero

| Campo | Detalle |
| :--- | :--- |
| **Entrevistado** | Luis Romero |
| **Imagen** | ![EntrevistaLuis](../assets/EntrevistaLuis.jpeg){width=80%} |
| **Edad** | 51 |
| **Ocupación** | Administrador de Gimnasio |
| **Link** | [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410344_upc_edu_pe/IQA9a7KYoWmaT4oQ5izmZ4DhAb2Eu4E9HPpLogl-D3kjWWo?e=Ui4zd9&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410344_upc_edu_pe/IQA9a7KYoWmaT4oQ5izmZ4DhAb2Eu4E9HPpLogl-D3kjWWo?e=Ui4zd9&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| **Resumen** | Luis Romero, Administrador de gimnasio en la UPC y YMCAID, destaca que la gestión en universidades es mucho más lenta que en gimnasios comerciales, donde una reparación puede tardar solo un día frente a varias semanas por burocracia. Señala que las fallas en equipos generan quejas inmediatas y afectan la renovación de membresías. Para manejar la congestión en horas pico, promueve compartir máquinas, pero considera clave el uso de mapas de calor en gimnasios grandes. Valora especialmente las alertas de mantenimiento predictivo, ya que ayudan a no olvidar revisiones. Prefiere equipos de musculación nacionales por repuestos rápidos y cardio importado. Resalta la importancia de sensores (sobre todo en trotadoras) para medir uso y anticipar fallas. En su panel ideal prioriza asistencia, quejas y renovaciones. También ve útil el uso de cámaras con procesamiento Edge para supervisión sin afectar la privacidad. Finalmente, un piloto gratuito lo convencería si ofrece datos precisos sobre afluencia y uso para tomar decisiones de mantenimiento o reemplazo. |

### Entrevista 3: Percy Baraybar

| Campo | Detalle |
| :--- | :--- |
| **Entrevistado** | Percy Baraybar |
| **Imagen** | ![EntrevistaPercy](../assets/EntrevistaPercy.jpeg){width=80%} |
| **Edad** | 30 |
| **Ocupación** | Administrador de Gimnasio |
| **Link** | [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410344_upc_edu_pe/IQDGKFaUoKynQpegiyG2er45AdJBJk-rS0T14PDLCLwFWIE?e=lFdlbs&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410344_upc_edu_pe/IQDGKFaUoKynQpegiyG2er45AdJBJk-rS0T14PDLCLwFWIE?e=lFdlbs&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| **Resumen** | Percy, administrador de Smartfit Miraflores con 5 años de experiencia, destaca que en gimnasios de alto volumen el mantenimiento correctivo es mucho más costoso y crítico para la percepción del cliente que el preventivo. Señala que las fallas en máquinas de alta demanda generan cuellos de botella y riesgos de no renovación. Para gestionar la congestión en horas pico, aplica la "gestión de piso", pero reconoce que falta una herramienta visual para que el socio entienda la capacidad del local. Valora enormemente un mapa de calor para redistribuir al staff y optimizar el mix de máquinas basado en datos reales de uso, no en percepciones subjetivas. Considera que las alertas de mantenimiento predictivo cambiarían las reglas del juego al evitar que los equipos queden fuera de servicio. En su panel de control ideal, prioriza el tiempo de inactividad (downtime), la saturación por zona y el ranking de desgaste de equipos. Finalmente, apoya el uso de cámaras con procesamiento Edge si se garantiza la transparencia sobre la privacidad, viendo un gran beneficio en que los socios consulten la disponibilidad desde una app. Un piloto de Fitnote Analytics lo convencería si logra una reducción mínima del 20% en las quejas por disponibilidad y demuestra una alta precisión en la data para mantener la credibilidad ante el usuario. |

#### Entrevistado 4: Joan Steffano Quispe Gamez
![foto-entrevista-4](../assets/foto-entrevista-1.png){width=80%}

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Joan Steffano Quispe Gamez |
| **Edad** | 19 |
| **Distrito** | Los Olivos |
| **Ocupación** | Estudiante universitario (UPC) |
| **Frecuencia** | 3 a 4 veces por semana |
| **Horario** | Nocturno (Post-clases) |
| **Contexto** | Entrena de noche debido a su alta carga académica. |
|**Resumen**| Estefano Quispe Gámez, estudiante universitario, entrena en el gimnasio de forma intermitente, asistiendo generalmente entre 3 y 4 veces por semana en horario nocturno debido a sus clases. Suele encontrarse con un gimnasio muy concurrido en horas punta, lo que lo obliga a esperar por máquinas y a modificar su rutina con frecuencia, ya sea cambiando el orden de ejercicios o sustituyendo equipos (por ejemplo, usando mancuernas en lugar de barras). Su principal frustración es la pérdida de ritmo y tiempo causada por la espera, la búsqueda de implementos o equipos fuera de servicio. A diferencia de otros usuarios, señala que la disponibilidad y el estado de las máquinas sí influyen en su decisión de cambiar de gimnasio. Considera valioso contar con una herramienta que reduzca la incertidumbre, permitiéndole conocer previamente el nivel de ocupación y planificar mejor su entrenamiento. En particular, destaca la utilidad de un mapa en tiempo real con disponibilidad de máquinas y tiempos estimados de espera para optimizar su rutina. 
| **Link** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202414928_upc_edu_pe/IQDwUfqEP6J8Sr_AMTcZaW80AVugegqiYVjdOyG2RY3agzs?e=dymEnS&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D |

#### Entrevistado 5: Fabián Suárez
![foto-entrevista-5](../assets/foto-entrevista-2.png)

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Fabián Suárez |
| **Edad** | 19 |
| **Distrito** | Pueblo Libre |
| **Ocupación** | Estudiante y trabajador |
| **Frecuencia** | 3 a 4 días a la semana (interdiario) |
| **Duración** | Entre 1 a 2 horas |
| **Contexto** | Adapta sus entrenamientos según su carga laboral y académica. |
|**Resumen**| Fabián Suárez, estudiante y trabajador, asiste al gimnasio entre 3 y 4 veces por semana en horarios interdiarios que se ajustan a su rutina. Suele entrenar entre 1 y 2 horas, organizando sus sesiones por grupos musculares en días específicos. Generalmente encuentra el gimnasio poco concurrido, lo que le permite seguir su rutina sin interrupciones, aunque en temporadas como verano experimenta mayor congestión, adaptando su entrenamiento hacia más cardio. Su principal frustración es la interrupción de su ritmo cuando las máquinas están ocupadas, especialmente al tener que compartirlas, lo que prolonga su tiempo de entrenamiento. Aunque esto no ha influido en su permanencia en el gimnasio, reconoce que pierde tiempo en estas situaciones. Valora la idea de una herramienta que le permita visualizar en tiempo real la disponibilidad de máquinas por zonas del gimnasio, lo que le ayudaría a reorganizar su rutina de manera más eficiente y aprovechar mejor su tiempo.
| **Link** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202414928_upc_edu_pe/IQA_G4YvOVSuSrJJqjakOjOpAQnSD43pUj6g0topSDxpyg8?e=8sTjzL&
|

#### Entrevistado 6
![foto-entrevista-6](../assets/foto-entrevista-6.png){width=80%}

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Diego Quispe |
| **Edad** | 19 |
| **Distrito** | Los Olivos |
| **Ocupación** | Estudiante universitario (U. de Lima) y trabajador a medio tiempo |
| **Frecuencia** | 4 días a la semana (rutina de dos días seguidos y un día de descanso) |
| **Duración** | Variable (afectada por la alta afluencia) |
| **Contexto** | Entrena por las noches por falta de tiempo diurno; el cansancio le ayuda a conciliar el sueño. |
|**Resumen**| Diego Quispe, estudiante y trabajador de 19 años, entrena cuatro noches a la semana enfocándose en grupos musculares específicos dentro de un gimnasio que suele estar sumamente saturado en ese horario. Su principal frustración es el exceso de tiempo de espera y la necesidad de compartir máquinas con múltiples usuarios, lo que provoca que su cuerpo se enfríe al superar los tres minutos de descanso, perdiendo la intensidad y el ritmo de su entrenamiento. Aunque esta aglomeración no lo ha motivado a cancelar su membresía, ya que adapta sus horarios durante los fines de semana, señala que su solución ideal sería una aplicación que no solo muestre la disponibilidad del lugar, sino que le envíe notificaciones en tiempo real indicándole qué máquina de su lista de ejercicios se acaba de desocupar para optimizar al máximo su tiempo.|
| **Link** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202414928_upc_edu_pe/IQCchhWgyjUFSp2Bce_l8sHtAXzQMAQ7-EESo5RieiDuUnw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=CDbXkN |

#### Video unificado
| Entrevista | Marca de tiempo | Entrevistado |
| :--- | :--- | :--- |
| 1 | 00:00:00 | Alexander Gutierrez |
| 2 | 13:49:09 | Luis Romero |
| 3 | 26:43:21 | Percy Baraybar | 
| 4 | 36:57:01 | Joan Steffano Quispe Gamez |
| 5 | 41:31:08 | Fabián Suárez |
| 6 | 46:26:11 | Diego Quispe |

| **Link** | [Enlace al video unificado de entrevistas - SpotTrack] (https://upcedupe-my.sharepoint.com/:v:/g/personal/u202413214_upc_edu_pe/IQDpYTdDwbM1QZOtdJPZIbsQASLFAmK8moRkLLD7ZudoVtM?e=oDOyRi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)|

### Análisis de entrevistas
### 1st Segmento (Administradores y Gerentes de Operaciones de Gimnasios)

Análisis de Entrevistas: Segmento "Administradores y gerentes de operaciones de gimnasios
1. **Características Objetivas (Demografía y Comportamiento)**

* Rango Etario y Perfil Profesional (100%): El 100% de los entrevistados (Alexander, Luis y Percy) son hombres que se desempeñan como administradores de gimnasios. Sus edades fluctúan entre los 30 y 51 años (Alexander con 31, Luis con 51 y Percy con 30), representando un segmento con experiencia directa en la gestión operativa de instalaciones deportivas.  
* Gestión Operativa de la Congestión (100%): El 100% del segmento implementa estrategias manuales de mitigación durante las horas pico. Para manejar la saturación, recurren a ofrecer ejercicios alternativos, promover el uso de pesos libres, fomentar que se compartan las máquinas o realizar "gestión de piso".  
* Dependencia de Mantenimiento y Repuestos (100%): El 100% lidia con la logística y los tiempos del mantenimiento de equipos. Un 66.7% (Alexander y Luis) diferencia operativamente entre la rapidez de obtener repuestos de marcas nacionales frente a las demoras logísticas que implican los repuestos importados, especialmente en máquinas de cardio como las trotadoras.  
* Apertura a la Implementación Tecnológica (100%): El 100% de los entrevistados está dispuesto a integrar tecnologías como mapas de calor, paneles de control y sensores/cámaras para medir el uso real del local. Asimismo, un 66.7% (Luis y Percy) enfatiza el uso de procesamiento "Edge" en las cámaras como condición operativa para asegurar la supervisión sin vulnerar la privacidad de los usuarios.  
* Condicionamiento para la Adopción de Software (100%): El 100% coincide en que la decisión de pagar por una nueva plataforma tecnológica depende de un piloto gratuito (por ejemplo, de 30 días). Exigen que este piloto demuestre datos precisos sobre afluencia, horarios pico y uso de máquinas (o logre una reducción medible de quejas) para justificar la inversión comercial.  
  
2. **Características Subjetivas (Pain Points, Emociones y Percepciones)**

* Frustración y Preocupación por Fuga de Clientes (100%): El 100% reconoce que las fallas en los equipos generan cuellos de botella y quejas inmediatas. Un 66.7% (Luis y Percy) señala con preocupación que estas fallas afectan negativamente la percepción del cliente y son un factor crítico que impacta directamente en la no renovación de las membresías.  
* Urgencia por Anticipación y Control (100%): El 100% valora profundamente el concepto de "mantenimiento predictivo". Perciben que poder anticipar el desgaste de piezas clave antes de que se rompan "cambiaría las reglas del juego" o sería "magnífico", ya que su principal dolor es el tiempo de inactividad de las máquinas (downtime) y el alto costo del mantenimiento correctivo.  
* Necesidad de Certeza frente a la Subjetividad (66.7%): Para el 66.7% (Alexander y Percy), existe el deseo de dejar atrás la intuición para pasar a los datos reales. Sienten la necesidad de contar con mapas de calor para prever demandas, optimizar el mix de máquinas y redistribuir al staff de manera fundamentada, sin depender de percepciones subjetivas.  
* Empatía Tecnológica con el Socio (66.7%): Un 66.7% (Alexander y Percy) proyecta que las herramientas visuales beneficiarían emocionalmente al usuario final. Consideran valioso que el socio pueda visualizar la disponibilidad del local o reservar espacios a través de una app, ayudando a que el cliente entienda la capacidad del lugar y gestione mejor sus expectativas.  
  
3. **Resumen para la construcción del Arquetipo**

Basado en esta evidencia estadística, el arquetipo de este segmento debe ser modelado como un "Gestor de Operaciones Orientado a Datos y Retención (30-51 años)". Este arquetipo valora profundamente la eficiencia operativa y busca mantener la rentabilidad del negocio, pero su gestión se ve altamente estresada por factores físicos del local: el tiempo de inactividad de las máquinas (downtime) por fallas y la congestión en horas pico, lo cual desemboca en quejas y pérdida de membresías (66.7%). Aunque es proactivo usando "gestión de piso" (100%), requiere urgentemente de herramientas predictivas (alertas de mantenimiento, mapas de calor y cámaras con procesamiento Edge) para recuperar el control, anticiparse a las roturas de equipos y basar sus decisiones en datos reales; todo esto condicionado a la demostración de precisión y retorno de inversión mediante un piloto gratuito (100%). 

#### 2nd Segmento (Clientes que frecuentan Gimnasios)

Análisis de Entrevistas: Segmento "Clientes que frecuentan el gimnasio"

1. **Características Objetivas (Demografía y Comportamiento)**

* Rango Etario y Etapa de Vida (100%): El 100% de los entrevistados (Joan, Fabián y Diego) tienen exactamente 19 años y son estudiantes universitarios. Esto evidencia que el segmento principal está compuesto por adultos jóvenes en etapa académica.
* Carga de responsabilidades (66.7%): El 66.7% (Fabián y Diego) combina sus estudios universitarios con una jornada laboral. Esto justifica la limitación de tiempo que tienen para entrenar.
* Frecuencia y Disciplina de Asistencia (100%): A pesar de sus responsabilidades, el 100% del segmento es constante, asistiendo al gimnasio entre 3 a 4 veces por semana.
* Preferencia y Condicionamiento de Horarios (66.7%): El 66.7% de los usuarios (Joan y Diego) se ve obligado a asistir en horario nocturno (post-clases/trabajo), coincidiendo directamente con la "hora punta" y mayor saturación del local. Solo un 33.3% (Fabián) logra adaptar su horario a momentos de baja afluencia.
* Metodología de Entrenamiento (100%): El 100% de la muestra organiza sus rutinas mediante una división estricta por grupos musculares (ej. pecho, espalda, piernas).

2. **Características Subjetivas (Pain Points, Emociones y Percepciones)**

* Frustración por Pérdida de Intensidad y Enfriamiento Muscular (66.7%): El 66.7% de los entrevistados (Joan y Diego) coincide explícitamente en que su mayor dolor es el "enfriamiento muscular". Sienten que las esperas prolongadas rompen la intensidad y la adrenalina del entrenamiento, reduciendo la efectividad de su esfuerzo físico.
* Percepción Negativa al Compartir Equipos (66.7%): Para el 66.7% (Fabián y Diego), turnarse en las máquinas con otras personas genera una sensación de "ineficiencia" e "interrupción del ritmo". Mencionan que ajustar pesos constantemente y depender de los tiempos de descanso de terceros (grupos de hasta 3 o 4 personas) es una fuente directa de pérdida de tiempo.
* Sensación de Descontrol e Improvisación Forzada (66.7%): A pesar de tener rutinas estrictas, el 66.7% (Joan y Fabián) experimenta frustración al tener que "improvisar constantemente" o "flexibilizar" sus rutinas (cambiando máquinas por mancuernas o cardio) debido a la infraestructura deficiente o máquinas ocupadas.
* Nivel de Resiliencia y Fidelización (66.7% Retención vs 33.3% Riesgo de Fuga): * Alta Resiliencia (66.7%): Fabián y Diego demuestran una "fidelidad estable". Su percepción subjetiva es que la sobrepoblación es un mal menor; prefieren buscar estrategias de mitigación (cambiar de horario o adaptar días a fines de semana) antes que cancelar su membresía.
* Intolerancia y Riesgo (33.3%): Joan representa el lado crítico del arquetipo, indicando que el mantenimiento deficiente (máquinas malogradas) y la saturación colman su paciencia, declarando explícitamente que "preferiría migrar a otro gimnasio".

**Resumen para la construcción del Arquetipo**

Basado en esta evidencia estadística, el arquetipo de este segmento debe ser modelado como un "Joven Estudiante/Trabajador Disciplinado (19 años)". Este arquetipo valora profundamente su tiempo limitado (100% asiste 3-4 veces por semana con rutina estructurada), pero su experiencia se ve altamente mermada por factores externos del local: la sobrepoblación y colas que causan la pérdida de la intensidad muscular (66.7%). Aunque es un cliente mayoritariamente fiel (66.7%), requiere herramientas (como una app de gestión del gimnasio, seguimiento de aforo o reserva de máquinas) para recuperar el control de su tiempo y evitar improvisar sus rutinas.

## Needfinding

### User Personas

**ADMINISTRADOR DE GIMNASIO**
![User Persona Alexis Villanueva](../assets/NEEDFINDING%20ARTEFACTS/User%20Persona%20Alexis%20Villanueva.png)


**CLIENTE FRECUENTE DE GIMNASIO**
![User Persona Andrea Mendoza](../assets/NEEDFINDING%20ARTEFACTS/User%20Persona%20Andrea%20Mendoza.png)

### User Task Matrix


| Tarea | Frecuencia (Alexis) | Importancia (Alexis) | Frecuencia (Andrea) | Importancia (Andrea) |
| :--- | :--- | :--- | :--- | :--- |
| Revisar disponibilidad de máquinas en tiempo real | Alta | Alta | Alta | Alta |
| Identificar máquinas con alto uso/desgaste | Alta | Alta | Baja | Media |
| Recibir alertas de mantenimiento predictivo | Media | Alta | Baja | Media |
| Planificar mantenimiento de equipos | Media | Alta | Muy Baja | Media |
| Analizar estadísticas de uso (dashboard) | Media | Alta | Baja | Media |
| Reubicar máquinas según demanda | Baja | Alta | Muy Baja | Baja |
| Consultar mapa de calor antes de ir al gym | Muy Baja | Media | Alta | Alta |
| Evitar tiempos de espera en máquinas | Baja | Media | Alta | Alta |
| Buscar máquinas libres dentro del gimnasio | Muy Baja | Baja | Alta | Alta |
| Recibir notificaciones de disponibilidad | Baja | Media | Media | Alta |
| Reportar máquinas averiadas | Baja | Media | Media | Media |
| Tomar decisiones de compra de equipos | Baja | Alta | Muy Baja | Baja |
| Optimizar distribución del espacio del gimnasio | Baja | Alta | Baja | Media |
| Reducir quejas por saturación | Media | Alta | Alta | Alta |
| Mejorar experiencia del usuario final | Media | Alta | Alta | Alta |
### User Journey Mapping


**JOURNEY MAP ADMINISTRADOR DE GIMNASIO**
![Journey Map Alexis Villanueva](../assets/NEEDFINDING%20ARTEFACTS/Journey%20Map%20Alexis%20Villanueva.png)


**JOURNEY MAP CLIENTE FRECUENTE DE GIMNASIO**
![Journey Map Andrea Mendoza](../assets/NEEDFINDING%20ARTEFACTS/Journey%20Map%20Andrea%20Mendoza.png)



### Empathy Mapping

![Impact Mappign Alexis Villanueva](../assets/NEEDFINDING%20ARTEFACTS/Impact%20Mapping%20Alexis%20Villanueva.png)


![Impact Mapping Andre Mendoza](../assets/NEEDFINDING%20ARTEFACTS/Impact%20Mapping%20Andre%20Mendoza.png)

## Big Picture Event Storming

![Event storming Big Picture.png](../assets/Event%20storming%20Big%20Picture.png)

## Ubiquitous Language

Para mejorar la cohesión del equipo, adoptaremos el Ubiquitous Language. Esta herramienta facilitará la comprensión de los objetivos y agilizará la resolución de dudas en el proyecto.

**Telemetry (Telemetría)**: Recopilación automática y a distancia de datos sobre el uso físico de las máquinas de ejercicio mediante dispositivos IoT, enviando esta información a la nube.

**Heat Map (Mapa de calor)**: Representación visual y semaforizada en la aplicación que indica la disponibilidad de las máquinas en tiempo real mediante colores (ej. Verde: Libre, Rojo: Ocupado).

**IoT Edge (Procesamiento en el borde)**: Tecnología utilizada en los sensores o cámaras que procesa la información directamente en el dispositivo físico, enviando únicamente el estado en formato JSON a la base de datos para no saturar la red y respetar la privacidad de los usuarios.

**Predictive Maintenance (Mantenimiento predictivo)**: Estrategia y alertas automatizadas para realizar revisiones a los equipos antes de que fallen, basándose en el acumulado de horas límite de uso seguro reportadas por los sensores.

**Corrective Maintenance (Mantenimiento correctivo)**: Reparación de emergencia y costosa que se realiza cuando una máquina falla repentinamente durante la operación del local.

**Downtime (Tiempo de inactividad)**: Periodo crítico durante el cual una máquina de ejercicio se encuentra fuera de servicio por avería, generando tiempos de espera y molestia en los usuarios.

**Churn Rate (Tasa de abandono)**: Porcentaje anual de usuarios que deciden no renovar o cancelar su membresía del gimnasio, frecuentemente impulsado por la frustración ante instalaciones abarrotadas y máquinas inoperativas.

**Subutilization (Subutilización)**: Condición estadística en la que una máquina específica registra una tasa de uso excepcionalmente baja en comparación con otras, lo que sugiere al administrador que debe ser reubicada.

**Crowdsourcing (Colaboración masiva)**: Acción mediante la cual los propios usuarios del gimnasio actualizan el estado de disponibilidad de un equipo en la plataforma a cambio de puntos de recompensa.

# Capítulo III: Requirements Specification

## User Stories

### 3.1. Épicas del Proyecto
| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **EP01** | Información del Producto y Landing Page | Como visitante, quiero conocer la propuesta de valor de SpotTrack y sus funcionalidades clave (IoT Edge, mapas de calor) para comprender cómo puede optimizar la gestión de gimnasios. | N/A | N/A |
| **EP02** | Autenticación y Gestión de Perfiles | Como usuario (administrador o cliente), quiero registrarme, iniciar sesión y gestionar mi información personal para acceder de forma segura a mi panel. | N/A | N/A |
| **EP03** | Mapa de Calor y Disponibilidad | Como cliente frecuente, quiero visualizar la disponibilidad de las máquinas en tiempo real para esquivar las aglomeraciones. | N/A | N/A |
| **EP04** | Sistema de Sugerencias | Como cliente, quiero recibir recomendaciones de ejercicios alternativos para no perder el "pump". | N/A | N/A |
| **EP05** | Dashboard y Estadísticas de Uso | Como administrador, quiero ver gráficos sobre el uso histórico y afluencia de máquinas para comprender la demanda real. | N/A | N/A |
| **EP06** | Mantenimiento Predictivo y Tickets | Como gerente de operaciones, quiero recibir alertas automáticas cuando un equipo supere sus horas seguras de uso. | N/A | N/A |
| **EP07** | Gestión de Activos y Multisede | Como administrador de una cadena, quiero gestionar el inventario, repuestos y cambiar la vista entre locales. | N/A | N/A |
| **EP08** | Analítica Financiera e Impacto | Como dueño del negocio, quiero calcular el impacto financiero por inactividad y analizar el ROI para tomar decisiones rentables. | N/A | N/A |
| **US01** | Mensaje principal en el Hero Section | Como visitante, quiero ver un mensaje claro en la parte superior junto con botones de acción (CTAs), para entender rápidamente cómo Spot Track optimiza la gestión de gimnasios. | **Escenario 1: Visualización del banner principal**<br>**Given** que el visitante se encuentra en la sección Home de la landing page.<br>**When** el visitante navega hacia el contenido principal en la parte superior.<br>**Then** el sistema muestra el titular estratégico junto con los botones Start Now y Watch Demo.<br><br>**Escenario 2: Redirección de llamadas a la acción**<br>**Given** que el visitante está en la pantalla principal.<br>**When** el visitante hace clic en el botón Watch Demo.<br>**Then** el sistema despliega la demostración del producto en la vista. | EP01 |
| **US02** | Presentación de pilares del producto | Como visitante, quiero explorar la sección "About Us", para conocer la misión y visión que respalda a SpotTrack. | **Escenario 1: Sección About Us**<br>**Given** que el visitante navega mediante el menú superior a la sección About Us.<br>**When** el visitante accede a la sección cargada en pantalla.<br>**Then** el sistema muestra las tres tarjetas clave de la empresa: Mission, Vision y Product.<br><br>**Escenario 2: Detalle de la Visión**<br>**Given** que el visitante se encuentra en la sección About Us.<br>**When** el visitante lee la tarjeta de Vision.<br>**Then** el sistema muestra el texto explicativo de la visión corporativa. | EP01 |
| **US03** | Visualización de Soluciones y Características | Como visitante, quiero visualizar seis tarjetas principales con las funcionalidades, para comprender el uso de sensores IoT y almacenamiento en la nube. | **Escenario 1: Tarjetas de Soluciones**<br>**Given** que el visitante explora la página principal.<br>**When** el visitante hace scroll hasta la sección The Solution.<br>**Then** el sistema despliega seis tarjetas principales detallando las características clave del producto.<br><br>**Escenario 2: Adaptación móvil de los servicios**<br>**Given** que el visitante ingresa al portal desde un dispositivo móvil.<br>**When** el visitante accede a la sección The Solution.<br>**Then** el sistema apila las seis tarjetas verticalmente en una sola columna para facilitar la lectura. | EP01 |
| **US04** | Selección de planes de suscripción SaaS | Como administrador, quiero visualizar la comparativa de precios (Basic, Mid, Platinum), para saber qué plan se ajusta a mi negocio. | **Escenario 1: Comparativa de planes Pricing**<br>**Given** que el visitante selecciona Pricing en la barra de navegación.<br>**When** el administrador revisa la grilla de suscripciones en pantalla.<br>**Then** el sistema muestra claramente los tres niveles de suscripción con sus respectivos costos mensuales.<br><br>**Escenario 2: Redirección a la compra o contacto**<br>**Given** que el administrador de un gimnasio evalúa qué plan adquirir.<br>**When** el administrador hace clic en los botones de acción de las tarjetas de planes.<br>**Then** el sistema redirige al usuario al flujo de registro correspondiente o al formulario de contacto. | EP01 |
| **US05** | Envío de formulario de Contacto | Como visitante, quiero poder llenar un formulario con mis datos y mensaje, para solicitar información al equipo de ventas de Spot Track. | **Escenario 1: Envío exitoso del mensaje**<br>**Given** que el visitante navega a la sección Contact.<br>**When** el visitante completa los campos obligatorios y presiona el botón Submit.<br>**Then** el sistema procesa la solicitud y envía la información al equipo de ventas de Spot Track.<br><br>**Escenario 2: Validación de campos obligatorios vacíos**<br>**Given** que el visitante interactúa con el formulario de contacto.<br>**When** el visitante intenta presionar Submit dejando el campo Email vacío.<br>**Then** el sistema impide el envío y resalta el campo indicando que es obligatorio. | EP01 |
| **US06** | Acceso al portal desde la navegación | Como visitante o cliente potencial, quiero tener botones de Login y Demo a la vista, para ingresar a la plataforma de forma rápida desde la landing page. | **Escenario 1: Botones de autenticación en el menú**<br>**Given** que un usuario ya existente o potencial cliente visita la landing page.<br>**When** el visitante revisa la esquina superior derecha del menú de navegación.<br>**Then** el sistema muestra claramente las opciones Login y Free Demo.<br><br>**Escenario 2: Redirección al Login**<br>**Given** que un cliente ubica el enlace Login en el menú.<br>**When** el cliente hace clic en el enlace Login.<br>**Then** el sistema redirige al usuario al módulo de autenticación de la plataforma Spot Track. | EP02 |
| **US07** | Inicio de sesión con validación JWT | Como usuario, quiero iniciar sesión de forma segura generando un token, para acceder a mi panel de control o aplicación móvil correspondiente. | **Escenario 1: Login de administrador**<br>**Given** que un administrador ingresa credenciales correctas en la vista de Login.<br>**When** el administrador hace clic en Iniciar Sesión.<br>**Then** el sistema genera un token JWT y redirige al usuario al Dashboard Gerencial.<br><br>**Escenario 2: Login de cliente**<br>**Given** que un cliente ingresa credenciales correctas en el formulario.<br>**When** el cliente hace clic en Iniciar Sesión.<br>**Then** el sistema valida el token y redirige al usuario a la vista del Mapa de Calor.<br><br>**Escenario 3: Credenciales inválidas**<br>**Given** que un usuario ingresa una contraseña o correo incorrecto.<br>**When** el usuario presiona el botón de Iniciar Sesión.<br>**Then** el sistema deniega el acceso y muestra un mensaje de error. | EP02 |
| **US08** | Gestión de preferencias y perfil | Como usuario, quiero actualizar mi información personal y cambiar el idioma del sistema, para mantener mis datos al día y usar la plataforma cómodamente. | **Escenario 1: Actualización de datos de perfil**<br>**Given** que el usuario se encuentra en la vista Mi Perfil.<br>**When** el usuario cambia su número de teléfono y presiona Guardar.<br>**Then** el sistema actualiza la información en la base de datos y muestra una notificación de éxito.<br><br>**Escenario 2: Cambio de idioma**<br>**Given** que el usuario visualiza la interfaz del sistema.<br>**When** el usuario hace clic en el botón selector de idioma y selecciona English.<br>**Then** el sistema recarga inmediatamente los textos y menús cambiando el idioma. | EP02 |
| **US09** | Visualización del mapa de calor en VIVO | Como cliente frecuente, quiero ver la disponibilidad de las máquinas en tiempo real (verde/rojo), para esquivar aglomeraciones y no perder tiempo en filas. | **Escenario 1: Indicadores semaforizados**<br>**Given** que el cliente accede a la sección de Disponibilidad en la app.<br>**When** el cliente abre el mapa interactivo de su sede.<br>**Then** el sistema muestra las máquinas en color Verde (Libre) o Rojo (Ocupado).<br><br>**Escenario 2: Actualización en tiempo real**<br>**Given** que el cliente se encuentra interactuando con el mapa de calor.<br>**When** el sistema IoT envía la señal de que una máquina se ha desocupado.<br>**Then** el icono de la máquina cambia automáticamente de Rojo a Verde sin necesidad de recargar la página. | EP03 |
| **US10** | Filtrado del inventario por tipo de máquina | Como cliente frecuente, quiero seleccionar etiquetas (ej. Fuerza o Cardio) en el mapa, para visualizar únicamente las máquinas relevantes para mi rutina. | **Escenario 1: Aplicación de filtro específico**<br>**Given** que el cliente desea visualizar equipos de peso libre.<br>**When** el cliente selecciona la etiqueta Fuerza en el menú de filtros.<br>**Then** el mapa oculta las máquinas cardiovasculares y resalta los equipos de fuerza.<br><br>**Escenario 2: Limpieza de filtros**<br>**Given** que el mapa interactivo tiene filtros aplicados.<br>**When** el cliente presiona el botón Limpiar filtros.<br>**Then** el sistema vuelve a mostrar el inventario completo del gimnasio. | EP03 |
| **US11** | Cambio de sucursal para revisión de aforo | Como cliente frecuente, quiero seleccionar otras sedes en la app, para revisar el croquis y aforo de sucursales alternas antes de salir de casa. | **Escenario 1: Consulta de sede alterna**<br>**Given** que el usuario dispone de una membresía multisede.<br>**When** el usuario selecciona una nueva sede en el selector superior.<br>**Then** el sistema carga el croquis y el mapa de calor de la nueva sucursal.<br><br>**Escenario 2: Sede fuera del plan**<br>**Given** que el usuario posee un plan de sede única (básico).<br>**When** el usuario selecciona una sede Premium en el menú de sucursales.<br>**Then** el sistema bloquea la vista y sugiere una mejora de membresía. | EP03 |
| **US12** | Notificaciones push de resolución de disponibilidad | Como cliente frecuente, quiero activar una campana de aviso, para recibir una alerta en mi celular cuando la máquina que esperaba se libere. | **Escenario 1: Alerta de máquina libre**<br>**Given** que el cliente activó la campana de aviso en un equipo ocupado.<br>**When** el hardware IoT registra la salida física del usuario anterior.<br>**Then** el sistema envía una notificación push al celular indicando que el equipo está libre.<br><br>**Escenario 2: Descarte automático de alerta**<br>**Given** que el sistema envió la notificación de máquina libre al cliente.<br>**When** un nuevo usuario ocupa la máquina físicamente antes de que llegue el usuario notificado.<br>**Then** el sistema cancela el seguimiento y notifica que el equipo volvió a ser ocupado. | EP03 |
| **US13** | Sistema de recompensas de Crowdsourcing | Como cliente frecuente, quiero ganar puntos canjeables en mi perfil, para motivarme a actualizar manualmente el estado de disponibilidad de los equipos. | **Escenario 1: Confirmación de reporte manual**<br>**Given** que un cliente reporta en la app que una máquina está libre.<br>**When** el sistema backend valida este cambio a través del sensor o confirmación cruzada.<br>**Then** el sistema otorga puntos de recompensa en el perfil del usuario.<br><br>**Escenario 2: Penalización por reportes falsos**<br>**Given** que un cliente reporta repetidamente máquinas libres que en realidad están ocupadas.<br>**When** el sistema backend detecta la anomalía contrastando la telemetría del sensor.<br>**Then** el sistema ignora sus reportes y bloquea temporalmente su capacidad de ganar puntos. | EP03 |
| **US14** | Motor de sugerencia de rutinas alternativas | Como cliente del gimnasio, quiero recibir recomendaciones de ejercicios alternativos cuando mi máquina esté ocupada, para no perder mi ritmo de entrenamiento. | **Escenario 1: Sugerencia por indisponibilidad**<br>**Given** que el cliente selecciona un equipo ocupado en su rutina digital.<br>**When** el cliente pulsa el botón Buscar alternativa.<br>**Then** el algoritmo cruza la base de datos y sugiere un ejercicio similar usando máquinas en estado Libre.<br><br>**Escenario 2: Sin alternativas disponibles**<br>**Given** que el área de pesas del gimnasio está al tope de capacidad.<br>**When** el cliente pulsa el botón Buscar alternativa.<br>**Then** el sistema sugiere un ejercicio de peso corporal o estiramiento para no depender de máquinas. | EP04 |
| **US15** | Filtrado de alternativas por grupo muscular | Como cliente frecuente, quiero que las rutinas sugeridas respeten mi grupo muscular objetivo y omitan máquinas averiadas, para tener opciones realmente útiles. | **Escenario 1: Respeto al enfoque del entrenamiento**<br>**Given** que el cliente está realizando una rutina enfocada en pectorales.<br>**When** el cliente solicita alternativas para su rutina actual.<br>**Then** el sistema descarta automáticamente ejercicios de otros grupos musculares, priorizando el pecho.<br><br>**Escenario 2: Exclusión de máquinas averiadas**<br>**Given** que existen equipos similares pero en estado de avería.<br>**When** el cliente solicita la recomendación de reemplazo.<br>**Then** el sistema omite estrictamente los equipos que posean un ticket técnico abierto. | EP04 |
| **US16** | Sistema de reserva exprés en horas pico | Como cliente frecuente, quiero separar virtualmente una máquina libre por 10 minutos durante horas pico, para asegurar su uso mientras me dirijo a ella. | **Escenario 1: Bloqueo virtual exitoso**<br>**Given** que el sistema se encuentra en horario pico y el cliente ve una máquina libre.<br>**When** el cliente pulsa el botón Separar en la interfaz de la máquina.<br>**Then** el mapa cambia la máquina a color Amarillo e inicia un contador temporal.<br><br>**Escenario 2: Expiración de la reserva**<br>**Given** que un contador de reserva de 10 minutos está actualmente activo.<br>**When** el cliente deja expirar el contador de reserva sin ocupar la máquina físicamente.<br>**Then** el sistema libera la máquina regresándola a estado Libre en el mapa general. | EP04 |
| **US17** | Acumulación automática de horas de uso | Como administrador, quiero ver gráficos con la sumatoria de horas reales de uso de las máquinas, para comprender la demanda real sin tener que vigilar el local. | **Escenario 1: Visualización de horas e impacto operativo**<br>**Given** que el administrador se encuentra en el módulo de Impacto Financiero.<br>**When** el sistema procesa los datos de los sensores de cada equipo.<br>**Then**  el sistema despliega la tabla de inactividad detallando la sumatoria de horas acumuladas por cada máquina y su correspondiente pérdida monetaria calculada.<br><br>**Escenario 2: Filtro por rango de fechas**<br>**Given** que el administrador visualiza la interfaz de horas de uso.<br>**When** el administrador aplica un filtro definiendo un periodo específico.<br>**Then** el sistema recalcula el total de horas limitando los datos al rango seleccionado. | EP05 |
| **US18** | Identificación de equipos subutilizados | Como administrador, quiero que el sistema resalte en una tabla qué máquinas tienen una tasa de uso excepcionalmente baja, para evaluar su reubicación o descarte. | **Escenario 1: Reporte de ineficiencia operativa**<br>**Given** que el gerente revisa el dashboard analítico de su sede.<br>**When** el motor del sistema procesa las estadísticas de ocupación.<br>**Then** el sistema resalta las máquinas con una tasa de uso menor al parámetro base establecido.<br><br>**Escenario 2: Exportación de lista subutilizada**<br>**Given** que el gerente visualiza la tabla consolidada de equipos subutilizados.<br>**When** el gerente hace clic en el botón Exportar CSV.<br>**Then** el sistema descarga un archivo con la data detallada para análisis externo. | EP05 |
| **US19** | Visualización de picos de estrés del local | Como dueño del negocio, quiero ver gráficos que destaquen las horas donde el aforo de máquinas supera el 90%, para identificar cuellos de botella diarios. | **Escenario 1: Destacar bloques horarios críticos**<br>**Given** que el administrador abre el panel analítico de su sede.<br>**When** el administrador selecciona la pestaña de Reportes <br>**Then** el sistema grafica las horas del día marcando en rojo los picos de estrés del recinto.<br><br>**Escenario 2: Comparativa intersemanal**<br>**Given** que el dueño del negocio se encuentra en el gráfico de picos de estrés.<br>**When** el dueño selecciona la opción de comparativa intersemanal.<br>**Then** el gráfico superpone dos líneas de tendencia para facilitar la evaluación de la congestión. | EP05 |
| **US20** | Exportación de analíticas de uso | Como gerente de operaciones, quiero generar documentos formateados en PDF de los gráficos de uso, para presentar reportes formales de rendimiento. | **Escenario 1: Generación de reporte gerencial en PDF**<br>**Given** que el gerente requiere extraer el resumen mensual de uso para una junta.<br>**When** el gerente presiona el botón Descargar PDF en el dashboard.<br>**Then** el sistema genera un documento formateado con gráficos y tablas resumen de la gestión.<br><br>**Escenario 2: Falla temporal en la descarga**<br>**Given** que el servidor de base de datos experimenta latencia temporal.<br>**When** el gerente presiona el botón Descargar PDF.<br>**Then** el sistema muestra un aviso de proceso demorado y programa el envío del archivo por correo electrónico. | EP05 |
| **US21** | Monitoreo de estado de hardware Edge IoT | Como administrador, quiero revisar la salud de la red y el estado de los nodos IoT, para detectar si un sensor se ha desconectado. | **Escenario 1: Detección de pérdida de conexión**<br>**Given** que el administrador se encuentra auditando la salud de la red.<br>**When** el sistema central pierde el ping de comunicación con un nodo IoT.<br>**Then** el sistema marca el sensor afectado como Desconectado y arroja una alerta visible en pantalla.<br><br>**Escenario 2: Reconexión exitosa**<br>**Given** que un sensor figuraba con estado Desconectado en el panel.<br>**When** el nodo IoT restablece su conexión de red exitosamente.<br>**Then** el sistema sincroniza los datos guardados en caché y actualiza su estado a Online. | EP05 |
| **US22** | Alerta predictiva de mantenimiento | Como gerente de operaciones, quiero recibir alertas automáticas cuando un equipo supere sus horas seguras de uso, para realizar mantenimientos preventivos antes de que fallen. | **Escenario 1: Disparo de alerta por umbral**<br>**Given** que el sistema acumula continuamente las horas operativas de los equipos.<br>**When** el sistema de telemetría detecta que el acumulado de una máquina supera el umbral configurado.<br>**Then** el sistema genera una alerta automática de Mantenimiento Preventivo Requerido.<br><br>**Escenario 2: Configuración de umbrales**<br>**Given** que un nuevo equipo es ingresado al inventario digital.<br>**When** el gerente navega al módulo de configuración de mantenimiento.<br>**Then** el sistema permite al gerente definir manualmente el límite de horas seguras para esa máquina específica. | EP06 |
| **US23** | Gestión de tickets técnicos en el Centro de Mantenimiento | Como administrador, quiero ver y gestionar los tickets técnicos desde el Centro de Mantenimiento del dashboard, para iniciar la atención de equipos con mantenimiento pendiente y hacer seguimiento del progreso hasta su cierre. | **Escenario 1: Inicio de ticket pendiente**<br>**Given** que el administrador accede al módulo Centro de Mantenimiento y visualiza tickets en estado Pendiente.<br>**When** el administrador hace clic en Iniciar sobre un ticket específico.<br>**Then** el sistema cambia el estado del ticket a En Progreso, actualiza los contadores del panel y registra el inicio de la atención.<br><br>**Escenario 2: Cierre de ticket en progreso**<br>**Given** que un ticket técnico se encuentra en estado En Progreso con un técnico asignado.<br>**When** el técnico completa la reparación y hace clic en Completar.<br>**Then** el sistema marca el ticket como Completado, actualiza el conteo del panel y libera la máquina devolviéndola al mapa de calor público.<br><br>**Escenario 3: Creación manual de ticket técnico**<br>**Given** que el administrador detecta una incidencia en un equipo que no generó una alerta automática.<br>**When** el administrador hace clic en Nuevo Ticket e ingresa la máquina afectada, la descripción del problema y la prioridad.<br>**Then** el sistema registra el ticket en estado Pendiente, lo añade al listado del Centro de Mantenimiento y cambia el estado de la máquina a En Mantenimiento en el mapa de calor. | EP06 |
| **US24** | Notificación de restablecimiento a los usuarios | Como administrador, quiero que el sistema notifique a los clientes cuando un equipo reportado es reparado, para mejorar su percepción del servicio. | **Escenario 1: Equipo reparado**<br>**Given** que un técnico culmina la reparación física de una máquina reportada.<br>**When** el técnico cambia el estado del ticket a Resuelto en el sistema.<br>**Then** el mapa de calor vuelve a mostrar la máquina como Libre y notifica a los clientes afectados.<br><br>**Escenario 2: Reapertura de ticket**<br>**Given** que un equipo supuestamente reparado vuelve a presentar una falla operativa.<br>**When** el administrador marca nuevamente el equipo como averiado en el dashboard.<br>**Then** el sistema reabre el ticket original y etiqueta la incidencia con prioridad Urgente. | EP06 |
| **US25** | Política de bloqueo de mantenimiento en horarios valle | Como administrador, quiero que el sistema impida programar mantenimientos preventivos en franjas de alta demanda, para garantizar la disponibilidad de los equipos durante los picos de afluencia. | **Escenario 1: Intento de agendamiento en hora pico bloqueado**<br>**Given** que el administrador intenta agendar un bloqueo de mantenimiento en una franja horaria de alta afluencia estadística.<br>**When** el administrador selecciona el horario y confirma el agendamiento.<br>**Then** el sistema rechaza el agendamiento y muestra una advertencia indicando que ese horario es de alta demanda, sugiriendo franjas alternativas de baja afluencia.<br><br>**Escenario 2: Agendamiento exitoso en horario valle**<br>**Given** que el administrador selecciona una franja horaria de baja demanda para el mantenimiento de un equipo.<br>**When** el administrador confirma el agendamiento.<br>**Then** el sistema registra el bloqueo en el calendario, marca la máquina como no disponible durante ese intervalo y no interrumpe el aforo general de la sede. | EP06 |
| **US26** | Gestión de activos físicos y altas | Como administrador, quiero registrar o dar de baja equipos vinculándolos a un sensor IoT, para actualizar el inventario digital y el mapa de calor. | **Escenario 1: Registro de nuevo equipo**<br>**Given** que el gimnasio adquiere un nuevo equipo físico para el recinto.<br>**When** el administrador llena el formulario de registro vinculándolo al ID de un sensor IoT.<br>**Then** la máquina aparece automáticamente en el inventario digital y en el mapa de la sede.<br><br>**Escenario 2: Baja de equipo obsoleto**<br>**Given** que una máquina antigua debe ser retirada permanentemente de las instalaciones.<br>**When** el administrador selecciona Dar de baja en el perfil de gestión del equipo.<br>**Then** el sistema desvincula el sensor IoT, archiva su historial y lo retira del mapa de calor público. | EP07 |
| **US27** | Estadísticas de reubicación multisede | Como administrador, quiero estadísticas cruzadas entre sedes, para identificar y trasladar máquinas de locales con baja demanda a los más saturados. | **Escenario 1: Recomendación de traslado**<br>**Given** que el sistema almacena datos estadísticos de ocupación de múltiples sucursales.<br>**When** el algoritmo detecta exceso de demanda en una sede y subutilización de la misma máquina en otra.<br>**Then** el sistema genera una tarjeta de recomendación sugiriendo el traslado físico de la máquina.<br><br>**Escenario 2: Ejecución de traslado en sistema**<br>**Given** que el gerente aprueba el traslado sugerido entre locales.<br>**When** el gerente registra la máquina en la red de la nueva sede.<br>**Then** el sistema actualiza automáticamente la asignación de sucursal en el Dashboard. | EP07 |
| **US28** | Gestión automatizada de stock de repuestos | Como administrador, quiero controlar el inventario de piezas clave y recibir alertas de reabastecimiento, para que los técnicos siempre tengan insumos disponibles. | **Escenario 1: Descuento de inventario**<br>**Given** que un técnico repara un equipo utilizando una pieza específica de almacén.<br>**When** el técnico registra en el ticket el uso del material.<br>**Then** el sistema resta la unidad del inventario general de repuestos de la sede.<br><br>**Escenario 2: Alerta de reabastecimiento**<br>**Given** que el inventario de una pieza crítica sufre un descuento por uso.<br>**When** el sistema detecta que el inventario llega al nivel mínimo de seguridad.<br>**Then** el sistema envía una alerta de reabastecimiento inmediata al departamento de compras. | EP07 |
| **US29** | Calculadora de impacto financiero por inactividad | Como dueño del negocio, quiero cuantificar la pérdida monetaria estimada por cada hora de inactividad de una máquina, para entender el impacto real de las averías. | **Escenario 1: Visualización de pérdida en tiempo real**<br>**Given** que un equipo clave para el gimnasio se encuentra averiado.<br>**When** el administrador abre el módulo de impacto financiero del equipo.<br>**Then** el sistema calcula y muestra un monto estimado de pérdida basado en la demanda histórica.<br><br>**Escenario 2: Reporte mensual de ineficiencias**<br>**Given** que ha finalizado el periodo operativo mensual del gimnasio.<br>**When** el dueño revisa el balance de mantenimiento general.<br>**Then** el sistema muestra un gráfico con el costo oculto total generado por la inactividad de los equipos. | EP08 |
| **US30** | Analítica predictiva de compras e inversión | Como dueño del negocio, quiero reportes basados en la tasa de uso para proyectar inversiones y simular el ROI, para tomar decisiones sobre qué equipos adquirir o descartar. | **Escenario 1: Sugerencia de compra por saturación**<br>**Given** que un equipo específico se mantiene constantemente por encima del límite máximo de ocupación.<br>**When** el gerente ingresa a la sección de Proyección de Inversión.<br>**Then** el sistema recomienda adquirir una unidad adicional para cubrir la demanda insatisfecha.<br><br>**Escenario 2: Cálculo de Retorno de Inversión (ROI)**<br>**Given** que el gerente simula la compra de un equipo nuevo en el dashboard.<br>**When** el gerente ingresa el costo estimado de adquisición de la máquina en el sistema.<br>**Then** el sistema devuelve una estimación del tiempo de recuperación de inversión en meses. | EP08 |
| **TS01** | Registrar usuario API | Como Developer, quiero implementar el endpoint POST /api/v1/auth/register, para permitir el registro de nuevos usuarios en la base de datos de forma segura. | **Escenario 1: Registro exitoso**<br>**Given** que el usuario cuenta con un payload de registro válido y no duplicado.<br>**When** el cliente envía un request POST al endpoint de registro.<br>**Then** el sistema crea la cuenta en PostgreSQL y retorna un response con status 201 Created y el ID del usuario.<br><br>**Escenario 2: Datos inválidos o duplicados**<br>**Given** que el usuario cuenta con un email ya registrado o un payload inválido.<br>**When** el cliente envía un request POST al endpoint de registro.<br>**Then** el sistema rechaza la creación y retorna un response con status 400 Bad Request o 409 Conflict. | EP02 |
| **TS02** | Login de usuario API | Como Developer, quiero implementar el endpoint POST /api/v1/auth/login, para generar credenciales de acceso JWT y mantener la sesión del usuario. | **Escenario 1: Login exitoso**<br>**Given** que el usuario dispone de credenciales válidas y correctas.<br>**When** el cliente envía un request POST al endpoint de autenticación.<br>**Then** el sistema valida los datos y retorna un status 200 OK adjuntando el token JWT generado.<br><br>**Escenario 2: Credenciales inválidas**<br>**Given** que el usuario posee una contraseña o email incorrecto.<br>**When** el cliente envía un request POST al endpoint de autenticación.<br>**Then** el sistema deniega el acceso y retorna un status 401 Unauthorized. | EP02 |
| **TS03** | Mostrar perfil de usuario API | Como Developer, quiero implementar el endpoint GET /api/v1/users/{id}, para proveer al frontend los datos del perfil del usuario autenticado. | **Escenario 1: Usuario encontrado**<br>**Given** que el cliente posee un JWT autorizado y el identificador de usuario es existente.<br>**When** el cliente envía un request GET al endpoint de perfil.<br>**Then** el sistema extrae la información de la base de datos y retorna un JSON con status 200 OK.<br><br>**Escenario 2: Usuario no encontrado**<br>**Given** que el cliente posee un JWT autorizado pero apunta a un ID de usuario inexistente.<br>**When** el cliente envía un request GET al endpoint de perfil.<br>**Then** el sistema retorna un response con status 404 Not Found. | EP02 |
| **TS04** | Actualizar perfil API | Como Developer, quiero implementar el endpoint PUT /api/v1/users/{id}, para permitir la modificación de los datos personales del usuario. | **Escenario 1: Actualización exitosa**<br>**Given** que el cliente dispone de un payload de actualización válido y el ID de usuario existe.<br>**When** el cliente envía un request PUT al endpoint de perfil.<br>**Then** el sistema actualiza el registro correspondiente y retorna un status 200 OK.<br><br>**Escenario 2: ID no encontrado**<br>**Given** que el cliente proporciona un identificador de usuario que no figura en el sistema.<br>**When** el cliente envía un request PUT al endpoint de perfil.<br>**Then** el sistema retorna un response con status 404 Not Found. | EP02 |
| **TS05** | Crear nueva máquina API | Como Developer, quiero implementar el endpoint POST /api/v1/machines, para registrar nuevos equipos vinculados a la telemetría IoT. | **Escenario 1: Creación exitosa**<br>**Given** que el administrador dispone de datos válidos de equipo y un ID de sensor IoT no asignado.<br>**When** el cliente envía un request POST al endpoint de máquinas.<br>**Then** el sistema guarda el registro en base de datos y retorna un status 201 Created.<br><br>**Escenario 2: Datos de máquina inválidos**<br>**Given** que el administrador dispone de un payload con propiedades o campos faltantes.<br>**When** el cliente envía un request POST al endpoint de máquinas.<br>**Then** el sistema rechaza la solicitud y retorna un status 400 Bad Request. | EP07 |
| **TS06** | Listar máquinas por sede API | Como Developer, quiero implementar el endpoint GET /api/v1/machines, para devolver el inventario completo filtrado por sucursal. | **Escenario 1: Listado exitoso**<br>**Given** que existen máquinas registradas en una sede específica.<br>**When** el cliente envía un request GET adjuntando el parámetro branchId.<br>**Then** el sistema devuelve un array JSON de las máquinas con su estado actual y status 200 OK.<br><br>**Escenario 2: Sede sin máquinas**<br>**Given** que una sede específica no cuenta con inventario registrado en el sistema.<br>**When** el cliente envía un request GET adjuntando el parámetro branchId.<br>**Then** el sistema retorna un array JSON vacío y un status 200 OK. | EP03, EP07 |
| **TS07** | Mostrar máquina por Id API | Como Developer, quiero implementar el endpoint GET /api/v1/machines/{id}, para proveer el detalle específico físico y lógico de un equipo. | **Escenario 1: Máquina encontrada**<br>**Given** que el equipo solicitado existe en la base de datos.<br>**When** el cliente envía un request GET con el identificador exacto de la máquina.<br>**Then** el sistema retorna un JSON detallado del equipo y un status 200 OK.<br><br>**Escenario 2: Máquina no encontrada**<br>**Given** que el equipo solicitado no existe en la base de datos del sistema.<br>**When** el cliente envía un request GET con un identificador de máquina erróneo.<br>**Then** el sistema retorna un status 404 Not Found. | EP07 |
| **TS08** | Actualizar/Reubicar máquina API | Como Developer, quiero implementar el endpoint PUT /api/v1/machines/{id}, para permitir la reasignación de sede o actualización de atributos físicos. | **Escenario 1: Actualización de atributos o sede**<br>**Given** que el equipo existe en el sistema y el payload de reubicación es válido.<br>**When** el cliente envía un request PUT al endpoint de la máquina específica.<br>**Then** el sistema modifica el registro interno y retorna un status 200 OK.<br><br>**Escenario 2: Máquina no encontrada para actualizar**<br>**Given** que el equipo a actualizar no figura en la base de datos.<br>**When** el cliente envía un request PUT al endpoint de la máquina.<br>**Then** el sistema retorna un status 404 Not Found. | EP07 |
| **TS09** | Dar de baja máquina API | Como Developer, quiero implementar el endpoint DELETE /api/v1/machines/{id}, para aplicar un soft-delete a los equipos retirados de operación. | **Escenario 1: Eliminación lógica exitosa**<br>**Given** que el equipo a eliminar existe y está activo en la base de datos.<br>**When** el cliente envía un request DELETE hacia el identificador del equipo.<br>**Then** el sistema aplica la baja lógica, desvincula el sensor IoT y retorna un status 204 No Content.<br><br>**Escenario 2: Máquina no encontrada para eliminar**<br>**Given** que el equipo a eliminar ya no existe en la base de datos.<br>**When** el cliente envía un request DELETE hacia un identificador de equipo inválido.<br>**Then** el sistema retorna un status 404 Not Found. | EP07 |
| **TS10** | Registrar repuesto en inventario API | Como Developer, quiero implementar el endpoint POST /api/v1/inventory, para agregar nuevas piezas al stock de mantenimiento. | **Escenario 1: Creación exitosa de pieza**<br>**Given** que los datos y atributos del nuevo repuesto a ingresar son válidos.<br>**When** el cliente envía un request POST al endpoint de inventario.<br>**Then** el sistema guarda la pieza en la base de datos y retorna un status 201 Created.<br><br>**Escenario 2: Payload de inventario inválido**<br>**Given** que los datos numéricos de stock del repuesto están mal formateados o incompletos.<br>**When** el cliente envía un request POST al endpoint de inventario.<br>**Then** el sistema rechaza la solicitud retornando un status 400 Bad Request. | EP07 |
| **TS11** | Actualizar stock de repuesto API | Como Developer, quiero implementar el endpoint PUT /api/v1/inventory/{id}/stock, para descontar materiales cuando se resuelve un ticket técnico. | **Escenario 1: Descuento de stock exitoso**<br>**Given** que el inventario disponible del repuesto en almacén es suficiente.<br>**When** el cliente envía un request PUT con el valor exacto a descontar.<br>**Then** el sistema actualiza el conteo en base de datos y retorna un status 200 OK.<br><br>**Escenario 2: Stock insuficiente**<br>**Given** que el inventario disponible del repuesto es insuficiente.<br>**When** el cliente envía un request PUT para descontar una cantidad mayor a la disponible.<br>**Then** el sistema aborta la operación y retorna un status 409 Conflict. | EP07 |
| **TS12** | Registrar evento de telemetría IoT API | Como Developer, quiero implementar el endpoint POST /api/v1/telemetry, para recibir y procesar pasivamente el estado emitido por los sensores Edge. | **Escenario 1: Registro de estado exitoso**<br>**Given** que un equipo físico cambia su estado de ocupación.<br>**When** el dispositivo IoT envía un request POST con el payload JSON del evento.<br>**Then** el sistema actualiza el estado de la máquina, acumula el tiempo de uso en el historial y retorna un status 201 Created.<br><br>**Escenario 2: Payload corrupto o no autorizado**<br>**Given** que la red presenta un fallo de transmisión o el dispositivo no está autenticado.<br>**When** el dispositivo IoT envía un request POST con un payload mal formado.<br>**Then** el sistema ignora el registro de telemetría y retorna un status 400 Bad Request. | EP03, EP05 |
| **TS13** | Listar historial de uso general API | Como Developer, quiero implementar el endpoint GET /api/v1/telemetry, para proveer la data cruda que alimenta los gráficos históricos de uso. | **Escenario 1: Listado de historial exitoso**<br>**Given** que existen datos históricos registrados en el rango de tiempo solicitado.<br>**When** el cliente envía un request GET con los parámetros de fecha de inicio y fin.<br>**Then** el sistema retorna un array JSON con las horas acumuladas por máquina y un status 200 OK.<br><br>**Escenario 2: Consulta de periodo sin actividad**<br>**Given** que no existen registros de telemetría en el rango de fecha solicitado.<br>**When** el cliente envía un request GET con los parámetros de fecha de inicio y fin.<br>**Then** el sistema retorna una lista JSON vacía y un status 200 OK. | EP05 |
| **TS14** | Obtener picos de afluencia por día API | Como Developer, quiero implementar el endpoint GET /api/v1/analytics/peak-hours, para procesar e identificar los bloques horarios de máximo estrés en la sede. | **Escenario 1: Cálculo de bloques horarios críticos exitoso**<br>**Given** que la base de datos contiene registros históricos consolidados de aforo.<br>**When** el cliente envía un request GET al endpoint analítico.<br>**Then** el sistema retorna un JSON con los bloques horarios donde el aforo superó el 90% y un status 200 OK. | EP05 |
| **TS15** | Exportar reporte gerencial API | Como Developer, quiero implementar el endpoint GET /api/v1/analytics/export/pdf, para generar archivos físicos de formato PDF como resumen mensual sobre demanda y uso. | **Escenario 1: Generación exitosa de stream PDF**<br>**Given** que el periodo a consultar contiene datos consolidados de uso.<br>**When** el cliente envía un request GET solicitando la exportación del reporte mensual.<br>**Then** el servidor genera y retorna un stream binario de formato application/pdf junto con un status 200 OK. | EP05 |
| **TS16** | Registrar estado manual de máquina API | Como Developer, quiero implementar el endpoint POST /api/v1/machines/{id}/manual-reports, para habilitar la funcionalidad de Crowdsourcing en la app. | **Escenario 1: Reporte Crowdsourcing registrado**<br>**Given** que una máquina figura como Ocupada en el sistema pero está físicamente Libre.<br>**When** el cliente envía un request POST reportando el estado real del equipo.<br>**Then** el sistema guarda el registro en cola pendiente de validación IoT y retorna un status 201 Created. | EP03 |
| **TS17** | Sumar puntos de recompensa API | Como Developer, quiero implementar el endpoint PUT /api/v1/users/{id}/points, para retribuir la colaboración del usuario que actualiza estados manualmente. | **Escenario 1: Adición de puntos exitosa**<br>**Given** que el reporte manual del usuario coincide con la lectura posterior del sensor IoT.<br>**When** el sistema interno envía un request PUT de validación de bonificación.<br>**Then** el sistema incrementa el valor numérico de puntos en el perfil del usuario y retorna un status 200 OK. | EP03 |
| **TS20** | Obtener sugerencias de rutinas API | Como Developer, quiero implementar el endpoint GET /api/v1/routines/alternatives, para correr el algoritmo de reemplazo de ejercicios según aforo. | **Escenario 1: Sugerencia de equipos libres encontrada**<br>**Given** que existen máquinas Libres en el gimnasio compatibles con el grupo muscular deseado.<br>**When** el cliente envía un request GET con el parámetro targetMuscle.<br>**Then** el sistema retorna un JSON con el array de ejercicios compatibles en máquinas y un status 200 OK.<br><br>**Escenario 2: Zona de fuerza sin máquinas libres**<br>**Given** que el área de pesas del gimnasio se encuentra al 100% de aforo.<br>**When** el cliente envía un request GET con el parámetro targetMuscle.<br>**Then** el sistema retorna un JSON sugiriendo ejercicios alternativos de peso corporal y un status 200 OK. | EP04 |
| **TS21** | Crear ticket de mantenimiento API | Como Developer, quiero implementar el endpoint POST /api/v1/tickets, para registrar formalmente una incidencia y alterar la disponibilidad pública de un equipo. | **Escenario 1: Creación de ticket exitosa**<br>**Given** que un equipo físico presenta un fallo operativo reportado por un empleado.<br>**When** el administrador envía un request POST con los detalles del reporte técnico.<br>**Then** el sistema cambia el estado del equipo a En Mantenimiento, guarda el documento de incidencia y retorna un status 201 Created. | EP06 |
| **TS22** | Listar tickets activos/históricos API | Como Developer, quiero implementar el endpoint GET /api/v1/tickets, para proveer el backlog de trabajo técnico al equipo. | **Escenario 1: Listado filtrado de tickets**<br>**Given** que existen incidencias técnicas registradas en la base de datos del sistema.<br>**When** el técnico envía un request GET adjuntando parámetros de filtrado por sede o estado.<br>**Then** el sistema retorna un array JSON con las incidencias solicitadas y un status 200 OK. | EP06 |
| **TS23** | Resolver ticket técnico API | Como Developer, quiero implementar el endpoint PUT /api/v1/tickets/{id}/resolve, para cerrar la incidencia y regresar la máquina al mapa de calor público. | **Escenario 1: Resolución de ticket y liberación exitosa**<br>**Given** que un ticket técnico se encuentra en proceso de atención o desarrollo.<br>**When** el técnico envía un request PUT indicando la conclusión de la reparación física.<br>**Then** el sistema marca la incidencia como Cerrada, devuelve la máquina a estado Libre y retorna un status 200 OK. | EP06 |
| **TS24** | Generar alerta predictiva API | Como Developer, quiero implementar el endpoint POST /api/v1/alerts, consumido de forma interna, para alertar sobre equipos que exceden los rangos operativos seguros. | **Escenario 1: Creación de alerta por superación de umbral**<br>**Given** que el acumulado de telemetría de una máquina sobrepasa el límite horario seguro.<br>**When** el CRON job interno envía un request POST para notificar el evento.<br>**Then** el sistema autogenera un documento de alerta dirigido al administrador y retorna un status 201 Created. | EP06 |
| **TS25** | Programar bloqueo de mantenimiento API | Como Developer, quiero implementar el endpoint POST /api/v1/maintenance-blocks, para validar si los agendamientos preventivos cruzan con picos de uso. | **Escenario 1: Agendamiento en bloque horario valle**<br>**Given** que el bloque horario seleccionado por el usuario corresponde a baja afluencia estadística.<br>**When** el cliente envía un request POST para agendar el mantenimiento del equipo.<br>**Then** el sistema registra el evento preventivo en el calendario y retorna un status 201 Created.<br><br>**Escenario 2: Conflicto de agendamiento en hora pico**<br>**Given** que el bloque horario seleccionado corresponde a un pico de alta afluencia estadística.<br>**When** el cliente envía un request POST para agendar el mantenimiento del equipo.<br>**Then** el sistema rechaza el agendamiento y retorna un status 409 Conflict sugiriendo un bloque horario alterno. | EP06 |
| **TS26** | Calcular impacto financiero por inactividad API | Como Developer, quiero implementar el endpoint GET /api/v1/analytics/financial-impact, para procesar métricas que conviertan horas muertas en estimaciones monetarias. | **Escenario 1: Cálculo matemático de pérdida exitoso**<br>**Given** que un equipo registra un periodo contabilizado de inactividad técnica (Downtime).<br>**When** el cliente envía un request GET al módulo de finanzas de dicho equipo.<br>**Then** el sistema retorna un JSON con la estimación monetaria de pérdida calculada y un status 200 OK. | EP08 |
| **TS27** | Simular Retorno de Inversión / ROI API | Como Developer, quiero implementar el endpoint POST /api/v1/analytics/roi-projection, para correr simulaciones de rentabilidad de compra basadas en telemetría de estrés. | **Escenario 1: Simulación de ROI y recuperación**<br>**Given** que existe una demanda insatisfecha proyectada e identificada para un modelo de equipo.<br>**When** el cliente envía un request POST adjuntando el costo de adquisición de la nueva máquina.<br>**Then** el sistema devuelve un objeto JSON con la proyección de recuperación de inversión en meses y un status 200 OK. | EP08 |
| **TS28** | Enviar Lead desde Landing Page API | Como Developer, quiero implementar el endpoint POST /api/v1/leads, para conectar el formulario público de la web con el CRM o base de datos de ventas. | **Escenario 1: Creación de prospecto exitosa**<br>**Given** que el visitante completó correctamente los datos del formulario de la web.<br>**When** el visitante envía un request POST desde la landing page hacia el backend.<br>**Then** el sistema almacena el Lead comercial en la base de datos y retorna un status 201 Created. | EP01 |
| **TS29** | Crear Suscripción de Gimnasio API | Como Developer, quiero implementar el endpoint POST /api/v1/subscriptions, para inicializar el licenciamiento SaaS de un nuevo administrador que contrata el servicio. | **Escenario 1: Inicialización de membresía SaaS exitosa**<br>**Given** que los datos de facturación y el plan de suscripción elegido son válidos.<br>**When** el sistema envía un request POST para el alta operativa del servicio.<br>**Then** el sistema vincula el tenant o gimnasio al nivel de acceso correspondiente y retorna un status 201 Created. | EP01 |
| **TS30** | Registrar token para Push Notifications API | Como Developer, quiero implementar el endpoint POST /api/v1/notifications/tokens, para guardar identificadores únicos de dispositivos móviles que permiten enviar alertas al usuario. | **Escenario 1: Registro de token de dispositivo exitoso**<br>**Given** que el dispositivo móvil cuenta con soporte para notificaciones Push.<br>**When** el cliente envía un request POST adjuntando un token válido proveído por FCM o APNs.<br>**Then** el sistema asocia el token de notificación al perfil del usuario autenticado retornando un status 201 Created. | EP03, EP06 |



## Impact Mapping

![IMPACT MAPPING](../assets/NEEDFINDING%20ARTEFACTS/IMPACT%20MAPPING.png)


## Product Backlog



| # Orden | User Story Id | Título | Descripción | Story Points (1/ 2/ 3/ 5/ 8/) |
| :--- | :--- | :--- | :--- | :--- |
| 1 | US14 | Motor de sugerencia de rutinas alternativas | Como cliente frecuente, quiero recibir recomendaciones de ejercicios alternativos cuando mi máquina esté ocupada, para no perder mi ritmo de entrenamiento. | 8 |
| 2 | US30 | Analítica predictiva de compras e inversión | Como dueño del negocio, quiero reportes basados en la tasa de uso para proyectar inversiones y simular el ROI, para tomar decisiones sobre qué equipos adquirir o descartar. | 8 |
| 3 | US27 | Estadísticas de reubicación multisede | Como administrador de una cadena, quiero estadísticas cruzadas entre sedes, para identificar y trasladar máquinas de locales con baja demanda a los más saturados. | 8 |
| 4 | US09 | Visualización del mapa de calor en vivo | Como cliente frecuente, quiero ver la disponibilidad de las máquinas en tiempo real (verde/rojo), para esquivar aglomeraciones y no perder tiempo en filas. | 8 |
| 5 | US29 | Calculadora de impacto financiero por inactividad | Como dueño del negocio, quiero cuantificar la pérdida monetaria estimada por cada hora de inactividad de una máquina, para entender el impacto real de las averías. | 8 |
| 6 | US17 | Acumulación automática de horas de uso | Como administrador, quiero ver gráficos con la sumatoria de minutos reales de uso de cada máquina, para comprender la demanda real sin tener que vigilar el local. | 8 |
| 7 | US22 | Alerta predictiva de mantenimiento | Como gerente de operaciones, quiero recibir alertas automáticas cuando un equipo supere sus horas seguras de uso, para realizar mantenimientos preventivos antes de que fallen. | 8 |
| 8 | US25 | Política de bloqueo de mantenimiento en horarios valle | Como administrador, quiero que el sistema impida programar mantenimientos preventivos en franjas de alta demanda, para garantizar la disponibilidad de los equipos durante los picos de afluencia. | 8 |
| 9 | US16 | Sistema de reserva exprés en horas pico | Como cliente frecuente, quiero separar virtualmente una máquina libre por 10 minutos durante horas pico, para asegurar su uso mientras me dirijo a ella. | 8 |
| 10 | US13 | Sistema de recompensas de Crowdsourcing | Como cliente frecuente, quiero ganar puntos canjeables en mi perfil, para motivarme a actualizar manualmente el estado de disponibilidad de los equipos si hay discrepancias. | 8 |
| 11 | TS20 | Obtener sugerencias de rutinas API | Como Developer, quiero implementar el endpoint GET api/v1/routines/alternatives, para correr el algoritmo de reemplazo de ejercicios según aforo. | 8 |
| 12 | TS27 | Simular Retorno de Inversión / ROI API | Como Developer, quiero implementar el endpoint POST /api/v1/analytics/roi-projection, para correr simulaciones de rentabilidad de compra basadas en telemetría de estrés. | 8 |
| 13 | US07 | Inicio de sesión con validación JWT | Como usuario (administrador o cliente), quiero iniciar sesión de forma segura generando un token, para acceder a mi panel de control o aplicación móvil correspondiente. | 5 |
| 14 | US10 | Filtrado del inventario por tipo de máquina | Como cliente frecuente, quiero seleccionar etiquetas (ej. Fuerza o Cardio) en el mapa, para visualizar únicamente las máquinas relevantes para mi rutina. | 5 |
| 15 | US11 | Cambio de sucursal para revisión de aforo | Como cliente frecuente, quiero seleccionar otras sedes en la app, para revisar el croquis y aforo de sucursales alternas antes de salir de casa. | 5 |
| 16 | US15 | Filtrado de alternativas por grupo muscular | Como cliente frecuente, quiero que las rutinas sugeridas respeten mi grupo muscular objetivo y omitan máquinas averiadas, para tener opciones realmente útiles. | 5 |
| 17 | US18 | Identificación de equipos subutilizados | Como administrador, quiero que el sistema resalte en una tabla qué máquinas tienen una tasa de uso excepcionalmente baja, para evaluar su reubicación o descarte. | 5 |
| 18 | US19 | Visualización de picos de estrés del local | Como dueño del negocio, quiero ver gráficos que destaquen las horas donde el aforo de máquinas supera el 90%, para identificar cuellos de botella diarios. | 5 |
| 19 | US21 | Monitoreo de estado de hardware Edge IoT | Como administrador, quiero revisar la salud de la red y el estado de los nodos IoT, para detectar si un sensor se ha desconectado. | 5 |
| 20 | US23 | Gestión de tickets técnicos en el Centro de Mantenimiento | Como administrador, quiero ver y gestionar los tickets técnicos desde el Centro de Mantenimiento, para iniciar la atención de equipos con mantenimiento pendiente y hacer seguimiento hasta su cierre. | 5 |
| 21 | US26 | Gestión de activos físicos y altas | Como administrador, quiero registrar o dar de baja equipos vinculándolos a un sensor IoT, para actualizar el inventario digital y el mapa de calor. | 5 |
| 22 | US28 | Gestión automatizada de stock de repuestos | Como administrador, quiero controlar el inventario de piezas clave y recibir alertas de reabastecimiento, para que los técnicos siempre tengan insumos disponibles. | 5 |
| 23 | US20 | Exportación de analíticas de uso | Como gerente de operaciones, quiero generar documentos formateados en PDF de los gráficos de uso, para presentar reportes formales de rendimiento. | 5 |
| 24 | US12 | Notificaciones push de resolución de disponibilidad | Como cliente frecuente, quiero activar una campana de aviso, para recibir una alerta en mi celular cuando la máquina que esperaba se libere. | 5 |
| 25 | US24 | Notificación de restablecimiento a los usuarios | Como administrador, quiero que el sistema notifique a los clientes cuando un equipo reportado es reparado, para mejorar su percepción del servicio. | 5 |
| 26 | TS12 | Registrar evento de telemetría IoT API | Como Developer, quiero implementar el endpoint POST api/v1/telemetry, para recibir y procesar pasivamente el estado emitido por los sensores Edge. | 5 |
| 27 | TS14 | Obtener picos de afluencia por día API | Como Developer, quiero implementar el endpoint GET /api/v1/analytics/peak-hours, para procesar e identificar los bloques horarios de máximo estrés en la sede. | 5 |
| 28 | TS15 | Exportar reporte gerencial API | Como Developer, quiero implementar el endpoint GET api/v1/analytics/export/pdf, para generar archivos físicos de formato de stream PDF sobre resumen mensual sobre demanda y uso. | 5 |
| 29 | TS18 | Crear reserva exprés API | Como Developer, quiero implementar el endpoint POST api/v1/reservations, para ejecutar bloqueos lógicos de máquinas durante horas de alta demanda. | 5 |
| 30 | TS24 | Generar alerta predictiva API | Como Developer, quiero implementar el endpoint POST /api/v1/alerts, consumido de forma interna, para alertar sobre equipos que exceden los rangos operativos seguros. | 5 |
| 31 | TS25 | Programar bloqueo de mantenimiento API | Como Developer, quiero implementar el endpoint POST /api/v1/maintenance-blocks, para validar si los agendamientos preventivos cruzan con picos de uso. | 5 |
| 32 | TS26 | Calcular impacto financiero por inactividad API | Como Developer, quiero implementar el endpoint GET /api/v1/analytics/financial-impact, para procesar métricas que conviertan horas muertas en estimaciones monetarias. | 5 |
| 33 | TS29 | Crear Suscripción de Gimnasio API | Como Developer, quiero implementar el endpoint POST /api/v1/subscriptions, para inicializar el licenciamiento SaaS de un nuevo administrador que contrata el servicio. | 5 |
| 34 | US08 | Gestión de preferencias y perfil | Como usuario, quiero actualizar mi información personal y cambiar el idioma del sistema, para mantener mis datos al día y usar la plataforma cómodamente. | 3 |
| 35 | US04 | Selección de planes de suscripción SaaS | Como visitante o administrador, quiero visualizar la comparativa de precios (Basic, Mid, Platinum), para saber qué plan se ajusta a mi negocio. | 3 |
| 36 | US05 | Envío de formulario de contacto | Como visitante, quiero poder llenar un formulario con mis datos y mensaje, para solicitar información al equipo de ventas de Spot Track. | 3 |
| 37 | TS01 | Registrar usuario API | Como Developer, quiero implementar el endpoint POST api/v1/auth/register, para permitir el registro de nuevos usuarios en la base de datos de forma segura. | 3 |
| 38 | TS02 | Login de usuario API | Como Developer, quiero implementar el endpoint POST /api/v1/auth/login, para generar credenciales de acceso JWT y mantener la sesión del usuario. | 3 |
| 39 | TS04 | Actualizar perfil API | Como Developer, quiero implementar el endpoint PUT api/v1/users/{id}, para permitir la modificación de los datos personales del usuario. | 3 |
| 40 | TS05 | Crear nueva máquina API | Como Developer, quiero implementar el endpoint POST api/v1/machines, para registrar nuevos equipos vinculados a la telemetría IoT. | 3 |
| 41 | TS06 | Listar máquinas por sede API | Como Developer, quiero implementar el endpoint GET api/v1/machines, para devolver el inventario completo filtrado por sucursal. | 3 |
| 42 | TS08 | Actualizar/Reubicar máquina API | Como Developer, quiero implementar el endpoint PUT /api/v1/machines/{id}, para permitir la reasignación de sede o actualización de atributos físicos. | 3 |
| 43 | TS10 | Registrar repuesto en inventario API | Como Developer, quiero implementar el endpoint POST api/v1/inventory, para agregar nuevas piezas al stock de mantenimiento. | 3 |
| 44 | TS11 | Actualizar stock de repuesto API | Como Developer, quiero implementar el endpoint PUT api/v1/inventory/{id}/stock, para descontar materiales cuando se resuelve un ticket técnico. | 3 |
| 45 | TS13 | Listar historial de uso general API | Como Developer, quiero implementar el endpoint GET api/v1/telemetry, para proveer la data cruda que alimenta los gráficos históricos de uso. | 3 |
| 46 | TS16 | Registrar estado manual de máquina API | Como Developer, quiero implementar el endpoint POST api/v1/machines/{id}/manual-reports, para habilitar la funcionalidad de Crowdsourcing en la app. | 3 |
| 47 | TS17 | Sumar puntos de recompensa API | Como Developer, quiero implementar el endpoint PUT api/v1/users/{id}/points, para retribuir la colaboración del usuario que actualiza estados manualmente. | 3 |
| 48 | TS19 | Cancelar reserva exprés API | Como Developer, quiero implementar el endpoint PUT api/v1/reservations/{id}/cancel, para limpiar el bloqueo virtual cuando expira el temporizador o el usuario lo aborta. | 3 |
| 49 | TS21 | Crear ticket de mantenimiento API | Como Developer, quiero implementar el endpoint POST api/v1/tickets, para registrar formalmente una incidencia y alterar la disponibilidad pública de un equipo. | 3 |
| 50 | TS22 | Listar tickets activos/históricos API | Como Developer, quiero implementar el endpoint GET /api/v1/tickets, para proveer el backlog de trabajo técnico al equipo. | 3 |
| 51 | TS23 | Resolver ticket técnico API | Como Developer, quiero implementar el endpoint PUT /api/v1/tickets/{id}/resolve, para cerrar la incidencia y regresar la máquina al mapa de calor público. | 3 |
| 52 | TS28 | Enviar Lead desde Landing Page API | Como Developer, quiero implementar el endpoint POST /api/v1/leads, para conectar el formulario público de la web con el CRM o base de datos de ventas. | 3 |
| 53 | TS30 | Registrar token para Push Notifications API | Como Developer, quiero implementar el endpoint POST /api/v1/notifications/tokens, para guardar identificadores únicos de dispositivos móviles que permiten enviar alertas al usuario. | 3 |
| 54 | US01 | Descripción principal en el Hero Section | Como visitante, quiero ver un mensaje claro en la parte superior junto con botones de acción (CTAs), para entender rápidamente cómo SpotTrack optimiza la gestión de gimnasios. | 2 |
| 55 | US02 | Presentación de pilares del producto | Como visitante, quiero explorar la sección "About Us", para conocer la misión y visión que respalda a SpotTrack Analytics. | 2 |
| 56 | US03 | Visualización de Soluciones y Características | Como visitante, quiero visualizar seis tarjetas principales con las funcionalidades, para comprender el uso de sensores IoT y almacenamiento en la nube. | 2 |
| 57 | US06 | Acceso al portal desde la navegación | Como visitante o cliente potencial, quiero tener botones de Login y Demo a la vista, para ingresar a la plataforma de forma rápida desde la landing page. | 2 |
| 58 | TS03 | Mostrar perfil de usuario API | Como Developer, quiero implementar el endpoint GET api/v1/users/{id}, para proveer al frontend los datos del perfil del usuario autenticado. | 2 |
| 59 | TS07 | Mostrar máquina por Id API | Como Developer, quiero implementar el endpoint GET /api/v1/machines/{id}, para proveer el detalle específico físico y lógico de un equipo. | 2 |
| 60 | TS09 | Dar de baja máquina API | Como Developer, quiero implementar el endpoint DELETE api/v1/machines/{id}, para aplicar un soft-delete a los equipos retirados de operación. | 2 |

# Capítulo IV: Product Design

## Style Guidelines

Para garantizar la consistencia visual, la accesibilidad y una experiencia de usuario (UX) coherente en todas las plataformas de SpotTrack (Landing Page, Dashboard B2B y Web App B2C), se ha definido la siguiente guía de estilos. Esta guía no solo estandariza los componentes de la interfaz, sino que también alinea la identidad visual con los objetivos del negocio.

### General Style Guidelines

La legibilidad es fundamental para una plataforma que muestra datos analíticos complejos y mapas de calor en tiempo real. Se ha establecido una jerarquía tipográfica limpia y moderna:

Tipografía Primaria: Utilizada para títulos (H1, H2, H3) y elementos de gran énfasis visual. Posee un carácter geométrico y dinámico que transmite modernidad tecnológica y agilidad deportiva. (Pesos utilizados: SemiBold, Bold).

Tipografía Secundaria: Utilizada para párrafos, etiquetas de la interfaz, tablas de datos y botones. Se caracteriza por su alta legibilidad en tamaños pequeños y pantallas móviles, garantizando que el usuario pueda escanear la información rápidamente. (Pesos utilizados: Regular, Medium, SemiBold).

![Typography](../assets/STYLEGUIDELINES/Typography.png)

Paleta de Colores
La selección cromática de SpotTrack está construida sobre un contraste de alto impacto que refleja innovación tecnológica y energía deportiva, utilizando los siguientes colores base:

Primary Dark / Neutral (#000000 - Negro Absoluto): Usado para fondos estructurados, modo oscuro del dashboard, textos principales y contenedores de gráficos.

Transmite autoridad, elegancia, fuerza y alta tecnología. En interfaces analíticas y de monitoreo constante (como el dashboard gerencial), el negro reduce drásticamente la fatiga visual y permite que los datos y los mapas de calor resalten de manera inmediata.

Primary Accent / Brand (#00ccb2 - Verde Azulado / Teal): Usado para los Call to Action (CTAs) principales, enlaces, indicadores de progreso y elementos interactivos primarios.

Es un color que fusiona la tranquilidad y fiabilidad tecnológica del azul con el crecimiento, salud y balance del verde. Transmite claridad, eficiencia e innovación. En el contexto del gimnasio, da una sensación de frescura y fluidez (ideal para indicar máquinas disponibles o acciones confirmadas).

Secondary Accent / Highlight (#f5bc36 - Amarillo Anaranjado / Dorado): Usado para destacar alertas preventivas, notificaciones importantes, botones secundarios de alta prioridad y estados de "Reserva" en el mapa de calor.

Representa vitalidad, energía, movimiento y el dinamismo puro del sector fitness. Capta la atención del ojo humano de inmediato, por lo que es perfecto para advertencias de mantenimiento predictivo o cuellos de botella en el aforo, comunicando precaución sin llegar a la agresividad de un rojo puro.

![Colors](../assets/STYLEGUIDELINES/Colors.png)

Logo
El logotipo de SpotTrack Analytics se compone de un isotipo acompañado de un logotipo tipográfico.

Isotipo: Representa un "nodo" estilizado que simula el flujo de datos e interconexión (Edge IoT), utilizando contrastes entre el #00ccb2 y el #f5bc36 sobre fondos oscuros (#000000) para proyectar dinamismo.

Tipografía del Logo: De trazos gruesos, limpios y modernos, estableciendo una presencia sólida en el mercado B2B, denotando confianza y robustez tecnológica.

![Branding](../assets/STYLEGUIDELINES/Branding.png)

### Web Style Guidelines
Para la construcción de las interfaces en código (Angular / CSS), se ha definido un sistema de diseño atómico estricto que rige la estructura y disposición de los elementos.

Grid System
El diseño se basa en un layout estructurado para mantener la alineación perfecta en resoluciones de escritorio y su correcta adaptabilidad a dispositivos móviles.

Columnas: Sistema de 12 columnas.

Ancho de Gutter: 24px.

Spacing System
Se utiliza una escala de espaciado predecible basada en múltiplos de 4 y 8 píxeles para mantener el ritmo vertical y horizontal

![Launguage and Spacing](../assets/STYLEGUIDELINES/Launguage%20and%20Spacing.png)

## Information Architecture

### Organization Systems
### 4.2.1. Organization Systems

Para estructurar el ecosistema de SpotTrack de forma práctica, utilizamos una categorización principal basada en la audiencia. Al final del día, toda la arquitectura de la información se rige por un modelo de **jerarquía visual (visual hierarchy)**, priorizando el contenido de mayor a menor importancia según lo que cada tipo de usuario necesita ver primero al entrar.

![INFO-ADMIN](../assets/INFO/INFO-ADMIN.jpg)
**Plataforma Administrativa (Dashboard B2B)**
Su estructura jerárquica se divide de frente por módulos operativos (Inventario, Tickets, Estadísticas). Dentro de estos, los datos se categorizan por tópicos (para agrupar las máquinas según la sucursal) y de forma cronológica (para ordenar las alertas predictivas y el historial de horas de uso de más reciente a más antiguo).

![INFO-CLIENT](../assets/INFO/INFO-CLIENT.jpg)
**Aplicación Móvil (Web App B2C)**
Diseñada para la inmediatez. La jerarquía visual coloca el mapa de calor en tiempo real como el componente absoluto y principal de la pantalla, subordinando opciones secundarias (como el perfil o recompensas) a menús de navegación. El catálogo de máquinas aplica una categorización directa por tópicos (ej. "Fuerza", "Cardio") para que el cliente filtre y encuentre lo que busca sin dar tantas vueltas.

![INFO-LANDING-PAGE](../assets/INFO/INFO-LANDING-PAGE.jpg)
**Landing Page Comercial**
Sigue una jerarquía visual descendente (top-down) para guiar la lectura. El flujo arranca con lo más importante arriba (Hero Section con la propuesta de valor) y decanta hacia los detalles específicos más abajo (features, tabla de precios y formulario de contacto). El texto y las tarjetas están categorizados explícitamente según la audiencia, separando qué gana el dueño del gimnasio y qué gana el usuario final.
https://miro.com/app/board/uXjVHcq90QA=/?share_link_id=360970048482

### Labeling Systems
Para garantizar la simplicidad y reducir la carga cognitiva de los usuarios, se utilizará un vocabulario directo, estandarizado y libre de jerga técnica compleja. Las etiquetas representan acciones claras o agrupaciones lógicas de información.

Para el Dashboard Administrativo (B2B):

    "Resumen": En lugar de "Dashboard Principal" o "Métricas Generales". Agrupa los KPIs de alto nivel.

    "Activos": En lugar de "Inventario de Máquinas Físicas".

    "Monitoreo IoT": Agrupa el estado de la red y conexión de sensores.

    "Mantenimiento": En lugar de "Gestión de Tickets y Reparaciones". Agrupa las alertas y órdenes de trabajo.

    "Reportes": Agrupa la analítica histórica y mapas de calor estáticos.

    "Finanzas": En lugar de "Calculadora de Impacto Financiero y ROI".

Para la Aplicación Móvil (Cliente B2C):

    "Mapa en Vivo": Representa la vista de disponibilidad en tiempo real.

    "Rutinas": Agrupa las sugerencias de ejercicios alternativos.

    "Reservar": Acción directa para bloquear temporalmente un equipo.


### SEO Tags and Meta Tags
Para asegurar un posicionamiento orgánico adecuado y una correcta indexación, se definen las siguientes etiquetas principales.

Landing Page (Sitio Público)

    Title: SpotTrack | Gestión Inteligente y Telemetría para Gimnasios

    Description: Optimiza la gestión de tu gimnasio con telemetría IoT. Reduce costos de mantenimiento, evita aglomeraciones y mejora la retención de tus clientes con mapas de calor en tiempo     real.

    Keywords: software para gimnasios, telemetría deportiva, mantenimiento predictivo gimnasios, sensores IoT fitness, gestión de activos deportivos, mapa de calor gimnasio, SpotTrack.

    Author: SpotTrack

Web Application (Portal de Acceso Administrativo)

    Title: SpotTrack Dashboard | Acceso Administrativo
    
    Description: Panel de control gerencial para la gestión de activos, monitoreo de hardware IoT y resolución de tickets de mantenimiento en tiempo real.
    
    Keywords: spottrack admin, login spottrack, gestión interna, dashboard gimnasios.
    
    Author: SpotTrack


### Searching Systems
SpotTrack ofrece mecanismos de búsqueda y filtrado integrados en las secciones donde el volumen de información puede dificultar la navegación del usuario.

Gestión de Equipos: El usuario dispone de una barra de búsqueda de texto libre que filtra por nombre, marca o modelo del equipo en tiempo real, sin necesidad de confirmar la consulta. Adicionalmente, cuenta con un filtro desplegable de estado (Operativo, En Mantenimiento, Fuera de Servicio). Los resultados se presentan en una tabla paginada que muestra ID, nombre, zona, estado y precio de compra; las filas se actualizan de forma reactiva conforme el usuario ajusta los criterios.

Gestión de Mantenimiento: La búsqueda combina texto libre (nombre del equipo, descripción del ticket o ID) con dos filtros independientes de estado (Abierto, En Progreso, Resuelto) y prioridad (Alta, Media, Baja). Los tickets que coincidan se listan en tarjetas ordenadas cronológicamente, mostrando el equipo asociado, la prioridad destacada por color y las marcas de tiempo de creación y actualización.

Analítica: El sistema permite segmentar los datos mediante un selector de período (mes, trimestre, año) y un selector de rango de fechas personalizado, combinables con el filtro de sede. Tras aplicar los filtros, los resultados se presentan como gráficos de uso, tasas de ocupación y proyecciones de ROI actualizados dinámicamente.

Sección Cliente – Reservas: El cliente puede localizar máquinas disponibles filtrando por tipo de equipo y franja horaria. Los resultados indican disponibilidad en tiempo real y permiten confirmar la reserva directamente desde la vista de búsqueda.

En todos los casos, el filtrado opera en el lado del cliente mediante computed properties reactivas, garantizando respuesta inmediata sin peticiones adicionales al servidor para conjuntos de datos de tamaño moderado.

### Navigation Systems
El sistema de navegación está diseñado para ser predecible y jerárquico, minimizando la cantidad de clics necesarios para alcanzar cualquier objetivo.

Landing Page (One-Page Scroll Navigation):

Navegación global superior fija (Sticky Top Navbar) que permite saltos rápidos (Anchor links) a las secciones clave: Inicio, Soluciones, Precios, Contacto. Incluye un Call to Action persistente ("Login") que redirige a la Web App.

Dashboard Administrativo (Desktop Web):

Navegación Estructural Permanente: Se utilizará un Sidebar (menú lateral izquierdo) persistente que contiene las etiquetas de los módulos principales (Activos, IoT, Mantenimiento, etc.). Esto permite al administrador saltar entre contextos sin perder su ubicación.

Navegación Local: Pestañas (Tabs) dentro de cada módulo para separar vistas internas (ej. dentro de "Mantenimiento", pestañas para Pendientes, En Progreso, Completados).

Aplicación Móvil (Clientes):

Bottom Navigation Bar: Barra inferior persistente con 3 o 4 íconos de acceso rápido a las funciones críticas para el usuario en movimiento (ej. Mapa, Rutinas, Perfil). Facilita el uso con una sola mano.


## Landing Page UI Design


### Landing Page Wireframe
![Landing Wireframe](../assets/WIREFRAMES/landing_wireframe.png){width=100%}

### Landing Page Mock-up
![Landing Mockup](../assets/MOCKUPS/landing_mockup.png){width=100%}

## Web Applications UX/UI Design

### Web Applications Wireframes


![US07 Inicio de sesión con validación JWT](../assets/WIREFRAMES/US07%20Inicio%20de%20sesión%20con%20validación%20JWT%20(Epic_%20EP02).png){width=600px}

![US08 Gestión de preferencias y perfil](../assets/WIREFRAMES/US08%20Gestión%20de%20preferencias%20y%20perfil%20(Epic_%20EP02).png){width=600px}

![US09 Y US10 MAPA DE CALOR Y FILTROS](../assets/WIREFRAMES/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png){width=600px}

![US11 Cambio de sucursal para revisión de aforo](../assets/WIREFRAMES/US11%20Cambio%20de%20sucursal%20para%20revisión%20de%20aforo%20(Epic_%20EP03).png){width=600px}

![US12 Notificaciones push de resolución de disponibilidad](../assets/WIREFRAMES/US12%20Notificaciones%20push%20de%20resolución%20de%20disponibilidad%20(Epic_%20EP03).png){width=600px}

![US13 Reporte de máquina](../assets/WIREFRAMES/US13_%20Reporte%20de%20máquina.png){width=600px}

![US14 Motor de sugerencia de rutinas alternativas](../assets/WIREFRAMES/US14%20Motor%20de%20sugerencia%20de%20rutinas%20alternativas%20(Epic_%20EP04).png){width=600px}

![US17 Acumulación automática de horas de uso](../assets/WIREFRAMES/US17_Wireframe.png){width=600px}

![US18 Clasificación de ineficiencia operativa](../assets/WIREFRAMES/US18_Wireframe.png){width=600px}

![US19 Comparativa de demanda intersemanal](../assets/WIREFRAMES/US19_Wireframe.png){width=600px}


![US20 Exportación de analíticas de uso](../assets/WIREFRAMES/US20%20Exportación%20de%20analíticas%20de%20uso%20(Epic_%20EP05).png){width=600px}

![US21 Monitoreo de estado de hardware Edge IoT](../assets/WIREFRAMES/US21%20Monitoreo%20de%20estado%20de%20hardware%20Edge%20IoT%20(Epic_%20EP05).png){width=600px}

![US22 Alerta predictiva de mantenimiento](../assets/WIREFRAMES/US22%20Alerta%20predictiva%20de%20mantenimiento%20(Epic_%20EP06)%20CONFIGURAR%20UMBRAL.png){width=600px}

![US23 Despacho automatizado de tickets técnicos](../assets/WIREFRAMES/US23%20Despacho%20automatizado%20de%20tickets%20técnicos%20(Epic_%20EP06).png){width=600px}

![US24 Notificación de restablecimiento a los usuarios](../assets/WIREFRAMES/US24%20Notificación%20de%20restablecimiento%20a%20los%20usuarios%20(Epic_%20EP06).png){width=600px}

![US25 Calendario inteligente de bloqueos de reserva](../assets/WIREFRAMES/US25%20Calendario%20inteligente%20de%20bloqueos%20de%20reserva(Epic_%20EP04).png){width=600px}

![US26 Gestión de activos físicos y altas](../assets/WIREFRAMES/US26%20Gestión%20de%20activos%20físicos%20y%20altas%20(Epic_%20EP07).png){width=600px}

![US27 Estadísticas de reubicación multisede](../assets/WIREFRAMES/US27%20Estadísticas%20de%20reubicación%20multisede%20(Epic_%20EP07).png){width=600px}

![US29 Calculadora de impacto financiero por inactividad](../assets/WIREFRAMES/US29%20Calculadora%20de%20impacto%20financiero%20por%20inactividad%20(Epic_%20EP08).png){width=600px}

![US30 Analítica predictiva de compras e inversión](../assets/WIREFRAMES/US30%20Analítica%20predictiva%20de%20compras%20e%20inversión%20(Epic_%20EP08).png){width=600px}


### Web Applications Wireflow Diagrams
![TASKFLOW-07](../assets/TASKFLOWS/TASKFLOW-07.jpg)
![WFM-07](../assets/WIREFLOWS%20MOBILE/US07%20Inicio%20de%20sesión%20con%20validación%20JWT%20(Epic_%20EP02).png) 
![WF-07](../assets/WIREFLOWS/US07%20Inicio%20de%20sesión%20con%20validación%20JWT%20(Epic_%20EP02).png)
![TASKFLOW-08](../assets/TASKFLOWS/TASKFLOW-08.jpg)

![WFM-08](../assets/WIREFLOWS%20MOBILE/US08%20Gestión%20de%20preferencias%20y%20perfil%20(Epic_%20EP02).png)
![WF-08](../assets/WIREFLOWS/US08%20Gestión%20de%20preferencias%20y%20perfil%20(Epic_%20EP02).png)
![TASKFLOW-09](../assets/TASKFLOWS/TASKFLOW-09.jpg)
![WFM-09](../assets/WIREFLOWS%20MOBILE/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png)
![WF-O9](../assets/WIREFLOWS/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png)
![TASKFLOW-10](../assets/TASKFLOWS/TASKFLOW-10.jpg)
![WFM-10](../assets/WIREFLOWS%20MOBILE/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png)
![WF-10](../assets/WIREFLOWS/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png)
![TASKFLOW-11](../assets/TASKFLOWS/TASKFLOW-11.jpg)
![WFM-11](../assets/WIREFLOWS%20MOBILE/US11%20Cambio%20de%20sucursal%20para%20revisión%20de%20aforo%20(Epic_%20EP03).png)
![WF-11](../assets/WIREFLOWS/US11%20Cambio%20de%20sucursal%20para%20revisión%20de%20aforo%20(Epic_%20EP03).png)
![TASKFLOW-12](../assets/TASKFLOWS/TASKFLOW-12.jpg)
![WFM-12](../assets/WIREFLOWS%20MOBILE/US12%20Notificaciones%20push%20de%20resolución%20de%20disponibilidad%20(Epic_%20EP03).png)
![WF-12](../assets/WIREFLOWS/US12%20Notificaciones%20push%20de%20resolución%20de%20disponibilidad%20(Epic_%20EP03).png)
![TASKFLOW-13](../assets/TASKFLOWS/TASKFLOW-13.jpg)
![WFM-13](../assets/WIREFLOWS%20MOBILE/US13_%20Reporte%20de%20máquina.png)
![WF-13](../assets/WIREFLOWS/US13_%20Reporte%20de%20máquina.png)
![TASKFLOW-14](../assets/TASKFLOWS/TASKFLOW-14.jpg)
![WFM-14](../assets/WIREFLOWS%20MOBILE/US14%20Motor%20de%20sugerencia%20de%20rutinas%20alternativas%20(Epic_%20EP04).png)
![WF-14](../assets/WIREFLOWS/US14%20Motor%20de%20sugerencia%20de%20rutinas%20alternativas%20(Epic_%20EP04).png)
![task16.png](../assets/TASKFLOWS/TASKFLOW-16.png)
![WF-16](../assets/WIREFLOWS/Frame%2017.png)
![task17.png](../assets/TASKFLOWS/TASKFLOW-17.png)
![WF-17](../assets/WIREFLOWS/S16%20-%20reserva%20express.png)
![task18.png](../assets/TASKFLOWS/TASKFLOW-18.png)
![WF-18](../assets/WIREFLOWS/US26%20Gestión%20de%20activos%20físicos%20y%20altas%20(Epic_%20EP07).png)
![task19.png](../assets/TASKFLOWS/TASKFLOW-19.png)


![task20.png](../assets/TASKFLOWS/TASKFLOW-20.png)
![WF-20](../assets/WIREFLOWS/US20%20Exportación%20de%20analíticas%20de%20uso%20(Epic_%20EP05).png)
![WFM-20](../assets/WIREFLOWS%20MOBILE/US20%20Exportación%20de%20analíticas%20de%20uso%20(Epic_%20EP05).png)

![TASKFLOW-21](../assets/TASKFLOWS/TASKFLOW-21.png)
![WF-21](../assets/WIREFLOWS/US21%20Monitoreo%20de%20estado%20de%20hardware%20Edge%20IoT%20(Epic_%20EP05).png)
![WFM-21](../assets/WIREFLOWS%20MOBILE/US21%20Monitoreo%20de%20estado%20de%20hardware%20Edge%20IoT%20(Epic_%20EP05).png)

![TASKFLOW-22](../assets/TASKFLOWS/TASKFLOW-22.png)
![WF-22-UMBRAL](../assets/WIREFLOWS/US22%20Alerta%20predictiva%20de%20mantenimiento%20(Epic_%20EP06)%20CONFIGURAR%20UMBRAL.png)
![WF-22](../assets/WIREFLOWS/US22%20Alerta%20predictiva%20de%20mantenimiento%20(Epic_%20EP06).png)
![WFM-22-UMBRAL](../assets/WIREFLOWS%20MOBILE/US22%20Alerta%20predictiva%20de%20mantenimiento%20(Epic_%20EP06)%20CONFIGURAR%20UMBRAL.png)
![WFM-22](../assets/WIREFLOWS%20MOBILE/US22%20Alerta%20predictiva%20de%20mantenimiento%20(Epic_%20EP06).png)

![TASKFLOW-23](../assets/TASKFLOWS/TASKFLOW-23.png)
![WF-23](../assets/WIREFLOWS/US23%20Despacho%20automatizado%20de%20tickets%20técnicos%20(Epic_%20EP06).png)
![WFM-23](../assets/WIREFLOWS%20MOBILE/US23%20Despacho%20automatizado%20de%20tickets%20técnicos%20(Epic_%20EP06).png)

![TASKFLOW-24](../assets/TASKFLOWS/TASKFLOW-24.png)
![WF-24](../assets/WIREFLOWS/US24%20Notificación%20de%20restablecimiento%20a%20los%20usuarios%20(Epic_%20EP06).png)
![WFM-24](../assets/WIREFLOWS%20MOBILE/US24%20Notificación%20de%20restablecimiento%20a%20los%20usuarios%20(Epic_%20EP06).png)

![TASKFLOW-25](../assets/TASKFLOWS/TASKFLOW-25.png)
![WF-25](../assets/WIREFLOWS/US25%20Calendario%20inteligente%20de%20bloqueos%20de%20reserva(Epic_%20EP04).png)
![WFM-25](../assets/WIREFLOWS%20MOBILE/US25%20Calendario%20inteligente%20de%20bloqueos%20de%20reserva(Epic_%20EP04).png)

![TASKFLOW-26](../assets/TASKFLOWS/TASKFLOW-26.png)
![WF-26](../assets/WIREFLOWS/US26%20Gestión%20de%20activos%20físicos%20y%20altas%20(Epic_%20EP07).png)
![WFM-26](../assets/WIREFLOWS%20MOBILE/US26%20Gestión%20de%20activos%20físicos%20y%20altas%20(Epic_%20EP07).png)

![TASKFLOW-29](../assets/TASKFLOWS/TASKFLOW-29.png)
![WF-29](../assets/WIREFLOWS/US29%20Calculadora%20de%20impacto%20financiero%20por%20inactividad%20(Epic_%20EP08).png)
![WFM-29](../assets/WIREFLOWS%20MOBILE/US29%20Calculadora%20de%20impacto%20financiero%20por%20inactividad%20(Epic_%20EP08).png)

![TASKFLOW-30](../assets/TASKFLOWS/TASKFLOW-30.png)
![WF-30](../assets/WIREFLOWS/US30%20Analítica%20predictiva%20de%20compras%20e%20inversión%20(Epic_%20EP08).png)
![WFM-30](../assets/WIREFLOWS%20MOBILE/US30%20Analítica%20predictiva%20de%20compras%20e%20inversión%20(Epic_%20EP08).png)

### Web Applications Mock-ups

![MOCKUP-FRAME-17](../assets/MOCKUPS/Frame%2017.png)
![MOCKUP-LANDING](../assets/MOCKUPS/landing_mockup.png)
![MOCKUP-S16](../assets/MOCKUPS/S16%20-%20reserva%20express.png)
![MOCKUP-US07](../assets/MOCKUPS/US07%20Inicio%20de%20sesión%20con%20validación%20JWT%20(Epic_%20EP02).png)
![MOCKUP-US08](../assets/MOCKUPS/US08%20Gestión%20de%20preferencias%20y%20perfil%20(Epic_%20EP02).png)
![MOCKUP-US09-US10](../assets/MOCKUPS/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png)
![MOCKUP-US11](../assets/MOCKUPS/US11%20Cambio%20de%20sucursal%20para%20revisión%20de%20aforo%20(Epic_%20EP03).png)
![MOCKUP-US12](../assets/MOCKUPS/US12%20Notificaciones%20push%20de%20resolución%20de%20disponibilidad%20(Epic_%20EP03).png)
![MOCKUP-US13](../assets/MOCKUPS/US13_%20Reporte%20de%20máquina.png)
![MOCKUP-US14](../assets/MOCKUPS/US14%20Motor%20de%20sugerencia%20de%20rutinas%20alternativas%20(Epic_%20EP04).png)
![MOCKUP-US20](../assets/MOCKUPS/US20%20Exportación%20de%20analíticas%20de%20uso%20(Epic_%20EP05).png)
![MOCKUP-US21](../assets/MOCKUPS/US21%20Monitoreo%20de%20estado%20de%20hardware%20Edge%20IoT%20(Epic_%20EP05).png)
![MOCKUP-US22-UMBRAL](../assets/MOCKUPS/US22%20Alerta%20predictiva%20de%20mantenimiento%20(Epic_%20EP06)%20CONFIGURAR%20UMBRAL.png)
![MOCKUP-US22](../assets/MOCKUPS/US22%20Alerta%20predictiva%20de%20mantenimiento%20(Epic_%20EP06).png)
![MOCKUP-US23](../assets/MOCKUPS/US23%20Despacho%20automatizado%20de%20tickets%20técnicos%20(Epic_%20EP06).png)
![MOCKUP-US24](../assets/MOCKUPS/US24%20Notificación%20de%20restablecimiento%20a%20los%20usuarios%20(Epic_%20EP06).png)
![MOCKUP-US25](../assets/MOCKUPS/US25%20Calendario%20inteligente%20de%20bloqueos%20de%20reserva(Epic_%20EP04).png)
![MOCKUP-US26](../assets/MOCKUPS/US26%20Gestión%20de%20activos%20físicos%20y%20altas%20(Epic_%20EP07).png)
![MOCKUP-US27](../assets/MOCKUPS/US27%20Estadísticas%20de%20reubicación%20multisede%20(Epic_%20EP07).png)
![MOCKUP-US29](../assets/MOCKUPS/US29%20Calculadora%20de%20impacto%20financiero%20por%20inactividad%20(Epic_%20EP08).png)
![MOCKUP-US30](../assets/MOCKUPS/US30%20Analítica%20predictiva%20de%20compras%20e%20inversión%20(Epic_%20EP08).png)




### Web Applications User Flow Diagrams 
---

## US04: Selección de planes de suscripción SaaS

* **Happy Path:** El visitante hace clic en Pricing en la barra de navegación. El sistema despliega correctamente la grilla comparativa con los tres niveles de suscripción (Basic $69, Mid $109, Platinum $189), mostrando características y costos mensuales claramente diferenciados para cada plan.
* **Unhappy Path:** El visitante desea acceder al pago de la pagina, pero al no rellenar los campos necesarios, el programa muestra un error de campos vacios.
  

## US05: Envío de formulario de Contacto

* **Happy Path:** El visitante completa todos los campos obligatorios incluyendo un email con formato válido y presiona Enviar. El sistema pasa la validación sin bloqueos y completa el flujo exitosamente.
* **Unhappy Path:** Si el visitante intenta presionar Enviar dejando el campo Email vacío, el sistema impide el envío, resalta el campo con un indicador de error y exige completar la información requerida antes de continuar. No se realiza ninguna llamada al servidor.

## US06: Acceso al portal desde la navegación

* **Happy Path:** El cliente hace clic en el enlace Iniciar Sesión ubicado en la esquina superior derecha del menú. El sistema redirige al usuario al módulo de autenticación de SpotTrack, donde puede ingresar sus credenciales para acceder al dashboard o al mapa de disponibilidad según su rol.

* **Unhappy Path:** Si el visitante intenta presionar Enviar dejando el campo Email vacío, el sistema muestra el mensaje de campos vacios, resalta el campo con un indicador de error y exige completar la información requerida antes de continuar. 


## US07: Inicio de sesión con validación JWT

![UF-07](../assets/USERFLOWS/US07%20Inicio%20de%20sesión%20con%20validación%20JWT%20(Epic_%20EP02).png){ width=90% }
![UFM-07](../assets/USERFLOW%20MOBILE/US07%20Inicio%20de%20sesión%20con%20validación%20JWT%20(Epic_%20EP02).png){ width=50% }

* **User Goal:** Como usuario (administrador o cliente), quiero iniciar sesión de forma segura generando un token, para acceder a mi panel de control o aplicación móvil correspondiente.
* **Happy Path:** El usuario se autentica ingresando credenciales válidas. El sistema verifica el token JWT y evalúa el rol de la cuenta. Los administradores son redirigidos directamente al dashboard analítico, mientras que los clientes acceden al mapa de disponibilidad en tiempo real.
* **Unhappy Path:** Si las credenciales son incorrectas, la interfaz despliega una alerta visual de error. Si se intenta procesar el formulario con campos vacíos, el frontend bloquea la petición y exige completar la información requerida.

---

## US08: Gestión de preferencias y perfil

![UF-08](../assets/USERFLOWS/US08%20Gestión%20de%20preferencias%20y%20perfil%20(Epic_%20EP02).png){ width=90% }
![UFM-08](../assets/USERFLOW%20MOBILE/US08%20Gestión%20de%20preferencias%20y%20perfil%20(Epic_%20EP02).png){ width=50% }

* **User Goal:** Como cliente, quiero actualizar mi información personal y cambiar el idioma del sistema, para mantener mis datos al día y usar la plataforma cómodamente.
* **Happy Path:** Mediante el menú lateral, el usuario accede a "Mi Perfil" para consultar su plan actual, métricas y puntos acumulados. Puede actualizar configuraciones como el idioma de la interfaz. Al guardar, la plataforma registra y aplica los cambios instantáneamente.
* **Unhappy Path:** Ante un fallo de red o un error de validación en el backend durante el guardado, los cambios se descartan de forma segura. La UI mantiene el estado previo de la configuración y notifica al usuario sobre el fallo.

---

## US09 y US10: Mapa de calor y filtros de equipamiento

![UF-09-10](../assets/USERFLOWS/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png){ width=90% }
![UFM-09-10](../assets/USERFLOW%20MOBILE/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png){ width=50% }

* **User Goal:** 
  - Como cliente frecuente, quiero ver la disponibilidad de las máquinas en tiempo real (verde/rojo), para esquivar aglomeraciones y no perder tiempo en filas.
  - Como cliente frecuente, quiero seleccionar etiquetas (ej. Fuerza o Cardio) en el mapa, para visualizar únicamente las máquinas relevantes para mi rutina.
* **Happy Path:** Dentro del mapa de disponibilidad, el usuario interactúa con los chips de filtrado. Al seleccionar "Fuerza", el renderizado aísla y muestra únicamente ese tipo de equipamiento. Alternar a "Cardio" refresca la vista instantáneamente con la nueva categoría.
* **Unhappy Path:** Si la combinación de filtros aplicada no arroja resultados (ej. todas las máquinas de la categoría están en mantenimiento o no existen en la sede actual), la interfaz maneja la excepción mostrando un *empty state* limpio.

---

## US11: Cambio de sucursal para revisión de aforo

![UF-11](../assets/USERFLOWS/US11%20Cambio%20de%20sucursal%20para%20revisión%20de%20aforo%20(Epic_%20EP03).png){ width=90% }
![UFM-11](../assets/USERFLOW%20MOBILE/US11%20Cambio%20de%20sucursal%20para%20revisión%20de%20aforo%20(Epic_%20EP03).png){ width=50% }

* **User Goal:** Como cliente frecuente, quiero seleccionar otras sedes en la app, para revisar el croquis y aforo de sucursales alternas antes de salir de casa.
* **Happy Path:** El usuario despliega el selector de sucursales y elige una ubicación distinta (ej. "Gimnasio Norte"). El sistema valida la jerarquía de su membresía y, al confirmar acceso multisede, carga el mapa de disponibilidad de la nueva ubicación.
* **Unhappy Path:** Si un usuario con plan "Basic" intenta acceder a la telemetría de una sede no incluida en su paquete, el sistema interrumpe la navegación y levanta un modal de "Sede Premium", funcionando como un punto de upsell para mejorar la membresía.

---

## US12: Notificaciones push de resolución de disponibilidad

![UF-12](../assets/USERFLOWS/US12%20Notificaciones%20push%20de%20resolución%20de%20disponibilidad%20(Epic_%20EP03).png){ width=90% }
![UFM-12](../assets/USERFLOW%20MOBILE/US12%20Notificaciones%20push%20de%20resolución%20de%20disponibilidad%20(Epic_%20EP03).png){ width=50% }

* **User Goal:** Como cliente frecuente, quiero activar una campana de aviso, para recibir una alerta en mi celular cuando la máquina que esperaba se libere.
* **Happy Path:** El usuario visualiza una máquina en estado ocupado (rojo) y suscribe una alerta de disponibilidad. Cuando el hardware IoT detecta que el equipo ha sido liberado, el sistema despacha una notificación push al dispositivo y el nodo en el mapa pasa a verde.
* **Unhappy Path:** Si la máquina continúa ocupada prolongadamente o es reclamada de inmediato por un usuario con mayor prioridad en la cola, el estado visual se mantiene en rojo y la notificación queda en espera o se informa de un cambio de estado a mantenimiento.

---

## US13: Reporte de máquina

![UF-13](../assets/USERFLOWS/US13_%20Reporte%20de%20máquina.png){ width=90% }
![UFM-13](../assets/USERFLOW%20MOBILE/US13_%20Reporte%20de%20máquina.png){ width=50% }

* **User Goal:** Como cliente frecuente, quiero ganar puntos canjeables en mi perfil, para motivarme a actualizar manualmente el estado de disponibilidad de los equipos.
* **Happy Path:** El usuario levanta un ticket reportando un fallo en un equipo específico. El sistema procesa el reporte, valida su legitimidad cruzando la telemetría, confirma la recepción y recompensa al usuario sumando +25 puntos a su perfil.
* **Unhappy Path:** Si el algoritmo de seguridad detecta un comportamiento anómalo (spam de reportes o falsos positivos recurrentes), la solicitud es rechazada. El sistema aplica una penalización automática, bloqueando la capacidad del usuario para emitir nuevos reportes durante 48 horas.

---

## US14: Motor de sugerencia de rutinas alternativas

![UF-14](../assets/USERFLOWS/US14%20Motor%20de%20sugerencia%20de%20rutinas%20alternativas%20(Epic_%20EP04).png){ width=90% }
![UFM-14](../assets/USERFLOW%20MOBILE/US14%20Motor%20de%20sugerencia%20de%20rutinas%20alternativas%20(Epic_%20EP04).png){ width=50% }

* **User Goal:** Como cliente del gimnasio, quiero recibir recomendaciones de ejercicios alternativos cuando mi máquina esté ocupada, para no perder mi ritmo de entrenamiento.
* **Happy Path:** Al encontrarse con una máquina inhabilitada u ocupada dentro de su rutina programada, el usuario solicita alternativas. El motor de recomendación mapea el grupo muscular y devuelve una lista de ejercicios biomecánicamente equivalentes (ej. sustituir press de banca por flexiones) utilizando el equipo disponible.
* **Unhappy Path:** Si la base de datos no logra resolver una equivalencia factible para ese ejercicio dadas las restricciones actuales del entorno, la UI presenta un *empty state* comunicando que temporalmente no hay rutinas alternativas disponibles.

## US15: Filtrado de alternativas por grupo muscular 

## US16: Sistema de reserva exprés en horas pico

## US17: Acumulación automática de horas de uso (EP08)
![UF-17](../assets/USERFLOWS/US17_%20Acumulacio%CC%81n%20automa%CC%81tica%20de%20horas%20de%20uso%20(EP08).png){ width=90% }

* **User Goal:** Como administrador, quiero ver gráficos con la sumatoria de horas reales de uso de las máquinas, para comprender la demanda real sin tener que vigilar el local.
* **Happy Path:** El administrador ingresa a Reportes y visualiza los gráficos de uso generados por los sensores IoT. Al revisar el tiempo inactivo, el sistema calcula y detalla automáticamente la pérdida monetaria por cada máquina. Finalmente, al aplicar un filtro de fechas, la plataforma recalcula y actualiza toda la información al instante.
* **Unhappy Path:** El administrador ingresa a Reportes, pero el backend no logra comunicarse con los sensores IoT. El sistema no se cae, sino que muestra un estado de alerta ("Sin conexión con los equipos") y los gráficos aparecen en cero o con el último dato en caché.


## US18: Identificación de equipos subutilizados (EP05)

![UF-18](../assets/USERFLOWS/US18_%20Identificacio%CC%81n%20de%20equipos%20subutilizados%20(EP05).png){ width=90% }


* **User Goal:** Como administrador, quiero que el sistema resalte en una tabla qué máquinas tienen una tasa de uso excepcionalmente baja, para evaluar su reubicación o descarte.
* **Happy Path:** El administrador ingresa a la sección de Reportes para evaluar la ineficiencia operativa de la sede. El sistema procesa las estadísticas de ocupación recopiladas por los sensores y resalta automáticamente en una tabla aquellas máquinas cuya tasa de uso es inferior al parámetro base. Finalmente, el administrador hace clic en "Exportar CSV" y la plataforma descarga exitosamente un archivo con la data detallada para su análisis externo.
* **Unhappy Path:** El administrador visualiza correctamente la tabla consolidada de equipos subutilizados y procede a hacer clic en "Exportar CSV". Debido a un error de conexión con el servidor, la generación del documento falla y el sistema despliega una notificación de error advirtiendo que no es posible descargar el archivo.


## US19: Visualización de picos de estrés del local (EP05) 

![UF-19](../assets/USERFLOWS/US19_%20Visualizacio%CC%81n%20de%20picos%20de%20estre%CC%81s%20del%20local%20(EP05)%20(1).png){ width=90% }
* **User Goal:** Como administrador, quiero que el sistema resalte en una tabla qué máquinas tienen una tasa de uso excepcionalmente baja, para evaluar su reubicación o descarte.
* **Happy Path:** El administrador accede al módulo de Reportes en SpotTrack, donde el sistema genera automáticamente un gráfico de picos de estrés resaltando en rojo las horas con aforo superior al 90%. Al activar la comparativa intersemanal, la interfaz superpone dos líneas de tendencia, permitiendo al dueño del negocio identificar cuellos de botella diarios y comparar el comportamiento de la demanda entre distintos periodos de forma inmediata.
* **Unhappy Path:** Debido a un error de red, el sistema no puede procesar el porcentaje de uso. En lugar del gráfico de estrés, se muestra un estado de carga infinito o un aviso de "Error al cargar analíticas de aforo", sugiriendo reintentar la consulta.


## US20 Exportación de analíticas de uso (Epic: EP05)

![UF-20](../assets/USERFLOWS/US20%20Exportación%20de%20analíticas%20de%20uso%20(Epic_%20EP05).png){ width=90% }
![UFM-20](../assets/USERFLOW%20MOBILE/US20%20Exportación%20de%20analíticas%20de%20uso%20(Epic_%20EP05).png){ width=50% }

* **User Goal**: Como gerente de operaciones, quiero generar documentos formateados en PDF de los gráficos de uso, para presentar reportes formales de rendimiento.
  

* **Happy Path:** El usuario accede a la sección de Reportes y Analíticas, selecciona el período y las sedes deseadas, y genera el reporte en formato CSV o PDF. El sistema procesa la solicitud y muestra una confirmación de "PDF generado correctamente" junto con la opción de descarga inmediata del archivo.
* **Unhappy Path:** Si no existen datos registrados para el período o la sede seleccionada, o si ocurre un fallo durante la generación del archivo, el sistema no puede completar la exportación y muestra un mensaje de error indicando la imposibilidad de generar el reporte, sin ofrecer archivo de descarga.


## US21 Monitoreo de estado de hardware Edge IoT (Epic_ EP05)

![UF-21](../assets/USERFLOWS/US21%20Monitoreo%20de%20estado%20de%20hardware%20Edge%20IoT%20(Epic_%20EP05).png){ width=90% }
![UFM-21](../assets/USERFLOW%20MOBILE/US21%20Monitoreo%20de%20estado%20de%20hardware%20Edge%20IoT%20(Epic_%20EP05).png){ width=50% }

* **User Goal:** Como administrador, quiero revisar la salud de la red y el estado de los nodos IoT, para detectar si un sensor se ha desconectado.
* **Happy Path:** El sistema detecta automáticamente la reconexión de un sensor IoT previamente desconectado y notifica al administrador mediante un mensaje de éxito con opción de descarga de reporte.
* **Unhappy Path:** Si el sensor permanece desconectado tras el intento de sincronización, la interfaz alerta al administrador sobre la falla crítica de conexión, manteniendo el estado de "Desconectado" en el reporte de alertas.

## US22 Alerta predictiva de mantenimiento (Epic_ EP06) CONFIGURAR UMBRAL


![UF-22](../assets/USERFLOWS/US22%20Alerta%20predictiva%20de%20mantenimiento%20(Epic_%20EP06)%20CONFIGURAR%20UMBRAL.png){ width=90% }
![UFM-22](../assets/USERFLOW%20MOBILE/US22%20Alerta%20predictiva%20de%20mantenimiento%20(Epic_%20EP06)%20CONFIGURAR%20UMBRAL.png){ width=50% }

* **User Goal:**
* **Happy Path:** El administrador ajusta los parámetros de los umbrales (batería, tiempos de inactividad, horas críticas) en el panel de configuración, y el sistema guarda los cambios aplicando las nuevas reglas a los modelos predictivos.
* **Unhappy Path:** Ante valores de configuración fuera de los rangos técnicos permitidos (ej. un intervalo de ping inexistente), el sistema bloquea la acción de guardado y requiere el ajuste de los parámetros.

## US23 Despacho automatizado de tickets técnicos (Epic_ EP06)

![UF-23](../assets/USERFLOWS/US23%20Despacho%20automatizado%20de%20tickets%20técnicos%20(Epic_%20EP06).png){ width=90% }
![UFM-23](../assets/USERFLOW%20MOBILE/US23%20Despacho%20automatizado%20de%20tickets%20técnicos%20(Epic_%20EP06).png){ width=50% }

* **User Goal:**
* **Happy Path:** El usuario técnico crea un ticket completando todos los campos requeridos (ID máquina, descripción, prioridad), y el sistema lo integra en el tablero de mantenimiento en tiempo real.
* **Unhappy Path (Missing fields):** Si el formulario se envía sin descripción o prioridad, la UI invalida la creación del ticket y solicita completar la información obligatoria.
* **Unhappy Path (Incorrect data):** Al ingresar datos técnicos inconsistentes o IDs de máquinas inexistentes, el sistema muestra un error de validación impidiendo el despacho del ticket.

## US24 Notificación de restablecimiento a los usuarios (Epic_ EP06)

![UF-24](../assets/USERFLOWS/US24%20Notificación%20de%20restablecimiento%20a%20los%20usuarios%20(Epic_%20EP06).png){ width=90% }
![UFM-24](../assets/USERFLOW%20MOBILE/US24%20Notificación%20de%20restablecimiento%20a%20los%20usuarios%20(Epic_%20EP06).png){ width=50% }
* **User Goal:** Como administrador, quiero que el sistema notifique a los clientes cuando un equipo reportado es reparado, para mejorar su percepción del servicio.
* **Happy Path:** Tras la resolución de una incidencia en el centro de mantenimiento, el sistema actualiza automáticamente el mapa de disponibilidad, habilitando nuevamente la máquina para los usuarios finales.
* **Unhappy Path:** Si la resolución del ticket es parcial o el problema persiste tras la intervención técnica, la máquina permanece inhabilitada en el mapa de disponibilidad, manteniendo la alerta de estado crítico en el centro de mantenimiento.

## US25 Calendario inteligente de bloqueos de reserva(Epic_ EP04)

![UF-25](../assets/USERFLOWS/US25%20Calendario%20inteligente%20de%20bloqueos%20de%20reserva(Epic_%20EP04).png){ width=90% }
![UFM-25](../assets/USERFLOW%20MOBILE/US25%20Calendario%20inteligente%20de%20bloqueos%20de%20reserva(Epic_%20EP04).png){ width=50% } 

* **User Goal:** Como gerente de operaciones, quiero que el sistema agende los mantenimientos preventivos exclusivamente en horarios valle, para no afectar la disponibilidad en horas de alta demanda.
* **Happy Path:** El usuario selecciona un activo desde el mapa de disponibilidad, completa el formulario de reserva con datos válidos y el sistema confirma la operación exitosamente.
* **Unhappy Path:** Si el usuario intenta realizar una reserva con campos obligatorios vacíos o ingresa datos inválidos (como horarios conflictivos), la UI presenta validaciones en rojo indicando los errores específicos.

## US26 Gestión de activos físicos y altas (Epic_ EP07)

![UF-26](../assets/USERFLOWS/US26%20Gestión%20de%20activos%20físicos%20y%20altas%20(Epic_%20EP07).png){ width=90% }
![UFM-26](../assets/USERFLOW%20MOBILE/US26%20Gestión%20de%20activos%20físicos%20y%20altas%20(Epic_%20EP07).png){ width=50% }
* **User Goal:**Como administrador, quiero registrar o dar de baja equipos vinculándolos a un sensor IoT, para actualizar el inventario digital y el mapa de calor. 
* **Happy Path:** El administrador completa el formulario de registro de nueva máquina con datos correctos (nombre, tipo, sede, ID de sensor) y el sistema lo añade al inventario global.
* **Unhappy Path:** Si existen campos faltantes o datos inválidos (como un ID de sensor ya existente), el flujo se detiene y la interfaz resalta los campos que requieren corrección antes de permitir el guardado.

## US29 Calculadora de impacto financiero por inactividad (Epic: EP08)

![UF-29](../assets/USERFLOWS/US29%20Calculadora%20de%20impacto%20financiero%20por%20inactividad%20(Epic_%20EP08).png){ width=90% }
![UFM-29](../assets/USERFLOW%20MOBILE/US29%20Calculadora%20de%20impacto%20financiero%20por%20inactividad%20(Epic_%20EP08).png){ width=50% }
* **User Goal:**
* **Happy Path:** El sistema calcula y presenta automáticamente el impacto financiero de la inactividad de activos, mostrando métricas clave como la pérdida por inactividad ($1,872), el costo de mantenimiento ($5,150), el ahorro potencial con mantenimiento predictivo ($1,840) y el ROI promedio de recuperación de inversión (7.2 meses).
* **Unhappy Path:** Si los activos no cuentan con datos de operación o historial de inactividad registrado, o si los parámetros financieros ingresados son incompletos o inválidos, la calculadora no puede generar los indicadores y muestra los campos vacíos o un mensaje de error indicando la imposibilidad de calcular el impacto financiero.

## US30 Analítica predictiva de compras e inversión (Epic_ EP08)

![UF-30](../assets/USERFLOWS/US30%20Analítica%20predictiva%20de%20compras%20e%20inversión%20(Epic_%20EP08).png){ width=90% }
![UFM-30](../assets/USERFLOW%20MOBILE/US30%20Analítica%20predictiva%20de%20compras%20e%20inversión%20(Epic_%20EP08).png){ width=50% }
* **User Goal:**
* **Happy Path:** El sistema procesa los datos financieros y de uso para generar proyecciones de ROI y recomendaciones de inversión automáticas basadas en la salud de los activos.
* **Unhappy Path:** Ante la falta de datos históricos suficientes o la introducción de parámetros de cálculo inconsistentes en el simulador, el motor de análisis muestra un estado de error o campos vacíos informando la imposibilidad de generar la proyección.

## Web Applications Prototyping

![Proto-Capture.png](../assets/Proto-Capture.png)

Video del prototipo:

https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241d317_upc_edu_pe/IQDCANk2iXBXRJw2mH1ZdZXPASTGyLkvsZa1prA9mkQ0dyw?e=ItBRSW&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D    


## Domain-Driven Software Architecture

### Design-Level Event Storming
![Design-Level Event Storming](../assets/event%20storming.png)

### Aggregates
![aggregates.png](../assets/aggregates.png)

### Software Architecture Context Diagram
![Context D.png](../docs/c4-banckend/Context%20D.png)
Frontend context diagram: 
![](../docs/c4-frontend/01_SystemContext-dark.png)


### Software Architecture Container Diagrams
![Container D.png](../docs/c4-banckend/Container%20D.png)
Frontend container diagram: 
![](../docs/c4-frontend/02_Containers-dark.png)


### Software Architecture Components Diagrams


#### IoT Sensor Ingestion
![Components1 D.png](../docs/c4-banckend/Components1%20D.png)
Frontend:
![](../docs/c4-frontend/03c_IoT-dark.png)

#### Monitoring
![Components2 D.png](../docs/c4-banckend/Components2%20D.png)
Frontend:
![](../docs/c4-frontend/03c_IoT-dark.png)

#### Maintenance
![Components3 D.png](../docs/c4-banckend/Components3%20D.png)
Frontend:
![](../docs/c4-frontend/03g_Maintenance-dark.png)

#### Equipment
![Components4 D.png](../docs/c4-banckend/Components4%20D.png)
Frontend:
![](../docs/c4-frontend/03b_Equipment-dark.png)

#### Analytics
![Components5 D.png](../docs/c4-banckend/Components5%20D.png)
Frontend:
![](../docs/c4-frontend/03e_Analytics-dark.png)

#### Reservation
![Components6 D.png](../docs/c4-banckend/Components6%20D.png)
Frontend:
![](../docs/c4-frontend/03i_Reservation-dark.png)


#### Authentication
![Components7 D.png](../docs/c4-banckend/Components7%20D.png)

#### Membership
![Components8 D.png](../docs/c4-banckend/Components8%20D.png)

## Software Object-Oriented Design

### Class Diagrams

#### Frontend

![class-diagram-auth](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-frontend/class-diagram-auth.puml)

![class-diagram-asset](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-frontend/class-diagram-asset-management.puml)


![class-diagram-availability](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-frontend/class-diagram-availability.puml)



![class-diagram-financial-impact](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-frontend/class-diagram-finantial-impact.puml)

![class-diagram-maintenance](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-frontend/class-diagram-matainance.puml)

![class-diagram-monitoring](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-frontend/class-diagram-monitoring.puml)


![class-diagram-notifications](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-frontend/class-diagram-notifications.puml)


![class-diagram-profiles](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-frontend/class-diagram-profiles.puml)



![class-diagram-reports](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-frontend/class-diagram-reports.puml)



![class-diagram-routines](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-frontend/class-diagram-routines.puml)



![class-diagram-settings](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-frontend/class-diagram-settings.puml)

#### Backend

![00_shared_kernel](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-backend/00_shared_kernel.puml)

![01_authentication_bc](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-backend/01_authentication_bc.puml)

![02_iot_sensor_ingestion_bc](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-backend/02_iot_sensor_ingestion_bc.puml)

![03_monitoring_bc](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-backend/03_monitoring_bc.puml)

![04_equipment_bc](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-backend/04_equipment_bc.puml)

![05_reservation_bc](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-backend/05_reservation_bc.puml)

![06_membership_bc](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-backend/06_membership_bc.puml)

![07_maintenance_bc](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-backend/07_maintenance_bc.puml)

![08_analytics_bc](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-backend/08_analytics_bc.puml)

![09_inter_context_event_flows](https://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New/refs/heads/develop/docs/class-diagrams-backend/09_inter_context_event_flows.puml)

## Database Design

### Database Diagrams
![db_opensource.png](../docs/database/db_opensource.png)

# Capítulo V: Product Implementation, Validation & Deployment

## Software Configuration Management

### Software Development Environment Configuration

**Figma**

![Figma-logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjih1p5gfTNIjPJ8wUgngz7_k8tUFdhHG42g&s){width=150px}

Producto SaaS utilizado para la elaboración de la propuesta de diseño de interfaces (UX/UI), incluyendo la creación de Wireframes, Mock-ups y Prototipos interactivos para el Landing Page y las aplicaciones web. Permite la colaboración en tiempo real del equipo de diseño.

* **Ruta de referencia:** [https://www.figma.com/](https://www.figma.com/)

**HTML5 & CSS3**

![html_css-logo](https://i.pinimg.com/736x/fe/57/10/fe571020f2e476bca20e1ae6441569ec.jpg){width=150px}

Lenguajes estándar de marcado y hojas de estilo utilizados para definir la estructura semántica y el diseño visual estático de los templates en el Landing Page y los componentes de las Frontend Web Applications.

* **Documentación de referencia:** [https://developer.mozilla.org/](https://developer.mozilla.org/)

**Angular Framework**

![angular-logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQVUcQofbdW28AoTCjLFzojT7sSZQVsEurWQA&s){width=150px}

Framework de desarrollo principal para la construcción de las Frontend Web Applications en formato SPA (Single Page Application). Se encarga de la lógica de presentación en el lado del cliente, el enrutamiento y el consumo de la API RESTful utilizando TypeScript como lenguaje de programación.

* **Ruta de descarga:** [https://angular.io/cli](https://angular.io/cli)

**Miro**

![miro-logo](https://asset.brandfetch.io/idAnDTFapY/idDdbxxs3M.png){width=150px}

Plataforma de pizarra virtual (SaaS) empleada para las sesiones colaborativas de análisis de dominio y la elaboración de los diagramas de Big Picture EventStorming y Design-Level EventStorming.

* **Ruta de referencia:** [https://miro.com/](https://miro.com/)

**Structurizr**

![structurizr-logo](https://www.nuget.org/profiles/structurizr/avatar?imageSize=512){width=150px}

Herramienta de modelado utilizada para el diseño y la documentación de la arquitectura de software de la solución, aplicando estrictamente el C4 Model (Context, Container y Component diagrams).

* **Ruta de referencia:** [https://structurizr.com/](https://structurizr.com/)

**Microsoft SQL Server**

![sql-logo](https://cdn-icons-png.flaticon.com/512/5968/5968364.png){width=150px}

Sistema de Gestión de Bases de Datos Relacionales (RDBMS) utilizado para el diseño y almacenamiento persistente de los datos transaccionales de los Bounded Contexts del sistema. Soporta la integridad referencial y las consultas estructuradas necesarias para la lógica del backend.

* **Ruta de descarga:** [https://www.microsoft.com/sql-server/sql-server-downloads](https://www.microsoft.com/sql-server/sql-server-downloads)

**Spring Boot (Java)**

![springboot-logo](https://e4developer.com/posts/microservices-toolbox-spring-boot/images/spring-boot.png){width=150px}

Framework backend basado en Java utilizado para la construcción, configuración y despliegue de los RESTful Web Services. Gestiona la lógica de negocio, la seguridad, las transacciones y la exposición de los endpoints que serán consumidos por las aplicaciones web.

* **Ruta de descarga:** [https://spring.io/projects/spring-boot](https://spring.io/projects/spring-boot)

### Source Code Management

El proyecto utiliza **GitHub** como sistema de control de versiones mediante un repositorio público. Se adoptó una estrategia basada en **GitFlow**:
* La rama `main` contiene versiones estables del sistema.
* La rama `develop` funciona como entorno de integración.
* Las nuevas funcionalidades se desarrollan en ramas `feature/*`.

La integración de cambios se realiza mediante **Pull Requests** hacia la rama `develop`, asegurando un control previo antes de incorporar modificaciones. Se emplea una convención de commits semánticos (`feat`, `fix`).


### Source Code Style Guide & Conventions

Para garantizar la claridad y cohesión del código fuente en el desarrollo de la plataforma, el equipo ha adoptado rigurosas convenciones de codificación y una nomenclatura estrictamente en idioma inglés, aplicándose esto a todas las tecnologías de la solución. 

En relación al **frontend**, la estructura semántica y los estilos se rigen por la *Google HTML/CSS Style Guide*, priorizando el uso exclusivo de minúsculas y la separación de palabras mediante guiones (**kebab-case**) para identificadores y clases, tal como se evidencia en selectores estructurales tipo `machine-status-badge` o `asset-detail-card` (Google, s.f.). Asimismo, la lógica de la interfaz y la arquitectura siguen los lineamientos de la *Google TypeScript Style Guide* (Google, s.f.) y la *Angular Coding Style Guide* (Angular, s.f.), aplicando **lowerCamelCase** para la declaración de variables y funciones (por ejemplo, `reportMachineIssue()`) y estandarizando la denominación de archivos por responsabilidades separadas por puntos (ej., `equipment-list.component.ts`). 

Por otro lado, en la **arquitectura del lado del servidor**, el código se alinea con la *Google Java Style Guide* y las directrices de *Spring Boot Features* (Google, s.f.), estableciendo el uso innegociable de **UpperCamelCase (PascalCase)** para la definición de entidades y controladores (ej., `MaintenanceTicketController`), además de seguir patrones arquitectónicos definidos por el framework para la inyección de dependencias. 

Finalmente, para asegurar una trazabilidad transparente entre los requerimientos del gimnasio y las pruebas automatizadas, el equipo utiliza las *Gherkin Conventions for Readable Specifications*, modelando historias de usuario bajo la sintaxis declarativa de comportamiento (**Given, When, Then**), lo que unifica el entendimiento funcional entre desarrolladores y stakeholders (Cucumber, s.f.).

### Software Deployment Configuration

Para el despliegue de la **Landing Page** de SpotTrack, se seleccionó **GitHub Pages** como servicio de hosting estático, aprovechando su integración nativa con el repositorio del equipo. La automatización del proceso se realizó mediante **GitHub Actions**, definiendo un pipeline CI/CD en el archivo `.github/workflows/deploy.yml`. Este workflow se activa automáticamente ante cada `push` a la rama `main`, ejecuta el proceso de build y publica el sitio en la URL pública del repositorio, garantizando que cada cambio integrado quede inmediatamente reflejado en producción sin intervención manual.

La siguiente figura muestra la configuración del archivo de workflow de GitHub Actions utilizado para el despliegue continuo de la Landing Page:

![Configuración del workflow de GitHub Actions (`.github/workflows/deploy.yml`) para el despliegue en GitHub Pages](../assets/landing-page-deployment-evidence/jekyll-gh-pages-yml_config_evidence.png)

Deployed landing page:
![Landing page screenshot](../assets/landing-page-deployment-evidence/lading-page-screenshot.png)

https://spottrack-1asi0729-2610-11881.github.io/SpotTrack-Landing-Page/

## Landing Page, Services & Applications Implementation

### Sprint 1
#### Sprint Planning 1  

El presente apartado detalla los acuerdos y objetivos definidos durante el Sprint Planning Meeting de nuestra primera iteración. Para este Sprint inicial de SpotTrack, nuestro esfuerzo se centró en sentar las bases estratégicas y técnicas del proyecto. Esto abarcó desde la elaboración de los artefactos fundacionales de Lean UX y la especificación de requerimientos, hasta el modelado de la arquitectura usando Domain-Driven Design (DDD) y el diseño lógico de la base de datos. Asimismo, priorizamos el prototipado de interfaces en Figma y el despliegue de nuestra Landing Page comercial para asegurar una presencia web temprana orientada a gimnasios y centros deportivos.

| Aspect | Details |
| :--- | :--- |
| **Sprint #** | Sprint 1 |
| **Date** | 2026-04-23 |
| **Time** | 10:00 AM |
| **Location** | Reunión Virtual (Discord / Microsoft Teams) |
| **Prepared By** | Azama Fukuda, Juan Pablo |
| **Attendees (to planning meeting)** | Atoche Gonzales, Nicolas Fernando / Azama Fukuda, Juan Pablo / Cataño Zarate, Jesus Miguel / Espinoza Orrego, Valentino Andre / Fernández Linares, Alvaro Sebastian |
| **Sprint n – 1 Review Summary** | No aplica (Primer Sprint del proyecto). |
| **Sprint n – 1 Retrospective Summary** | No aplica (Primer Sprint del proyecto). |
| **Sprint Goal** | Nuestro enfoque principal es establecer el diseño fundamental de UX/UI, la arquitectura de dominio bajo DDD y el despliegue de la Landing Page de SpotTrack. Consideramos que esto nos entrega una estructura de proyecto clara, los artefactos IoT correctamente modelados y un primer punto de contacto digital para gimnasios y administradores de centros deportivos. Esto se confirmará cuando los artefactos de Lean UX, base de datos, DDD y Figma estén completados, y la Landing Page se encuentre desplegada y funcional en producción. |
| **Sprint n Velocity** | 45 Story Points |
| **Sum of Story Points** | 45 |

#### Aspect Leaders and Collaborators

Durante este sprint, la dinámica de trabajo exigió una división estratégica de los integrantes. Para optimizar el flujo de desarrollo, conformamos subequipos especializados que pudieran concentrarse íntegramente en el ecosistema frontend, la investigación de usuarios y la estructuración de la Landing Page de SpotTrack. Esta organización nos permitió mantener un avance continuo y evitar la fragmentación en microtareas, lo cual habría ocasionado que perdiéramos la perspectiva general de la solución IoT orientada a gimnasios.

| Team Member (Last Name, First Name) | GitHub Username | Aspect Name 1 Leader (L) / Collaborator (C) | Aspect Name 2 Leader (L) / Collaborator (C) | Aspect Name 3 Leader (L) / Collaborator (C) | Aspect Name 4 Leader (L) / Collaborator (C) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Azama Fukuda, Juan Pablo | llummo | Landing Page Elaboration (L) | Bounded Context Development (C) | Prototyping (L) | Scrum Master Role (L) |
| Atoche Gonzales, Nicolas Fernando | THECOMAX | Landing Page Elaboration (C) | Bounded Context Development (C) | Prototyping (C) | UX Research (L) |
| Cataño Zarate, Jesus Miguel | jcuz1510 | Landing Page Elaboration (C) | Bounded Context Development (L) | Database & Class Diagram (L) | UX Research (C) |
| Espinoza Orrego, Valentino Andre | valentinoespinoza13 | Landing Page Elaboration (C) | Bounded Context Development (C) | Database & Class Diagram (C) | UX Research (C) |
| Fernández Linares, Alvaro Sebastian | ORION-tech-c | Landing Page Elaboration (C) | Bounded Context Development (C) | Prototyping (C) | UX Research (C) |

### Sprint Backlog

| Id | Title | Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| | | T01 | UX Research & Entrevistas | Realizar entrevistas a administradores de gimnasios y clientes frecuentes; crear User Personas y Empathy Maps orientados al dominio IoT de SpotTrack. | 6 hrs | Atoche / Espinoza / Azama / Fernández | Done |
| | | T02 | Diseño UX/UI de Landing Page | Diseñar Wireframes, Mockups y User Flows para la presentación comercial web de SpotTrack dirigida a gimnasios B2B. | 5 hrs | Cataño / Azama / Espinoza | Done |
| | | T03 | Domain-Driven Design Artifacts | Elaborar EventStorming, Bounded Contexts y Context Mapping para la lógica de telemetría IoT y gestión de activos. | 5 hrs | Fernández / Atoche | Done |
| | | T04 | Database & Class Diagram | Diseñar el Diagrama de Clases (UML) y el Diagrama Entidad-Relación (ERD) del sistema SpotTrack. | 5 hrs | Fernández / Atoche | Done |
| | | T05 | Software Development Environment | Configurar el entorno de desarrollo y dependencias locales para el framework Angular (frontend) y Spring Boot (backend). | 4 hrs | Azama | Done |
| | | T06 | Source Code Management & Styles | Definir el Style Guide del código, convenciones de commits y la arquitectura de información base bajo GitFlow. | 4 hrs | Cataño | Done |
| | | T07 | Segmento objetivo & Lean UX Process | Definir segmentos objetivo (administradores de gimnasios y clientes frecuentes), Lean UX Canvas y la matriz de tareas del usuario. | 4 hrs | Cataño | Done |
| | | T08 | Software Deployment Configuration | Configurar el servicio de hosting cloud estático para la Landing Page de SpotTrack (Vercel/Netlify/GitHub Pages). | 4 hrs | Azama | Done |
| | | T09 | Sprint 1 Planning & Backlog | Redactar el Sprint Planning, Aspect Leaders y el Backlog en el documento académico del proyecto. | 4 hrs | Espinoza | Done |
| | | T10 | Development & Execution Evidence | Recolectar capturas de commits y evidencia gráfica de la ejecución de la Landing Page de SpotTrack. | 4 hrs | Cataño | Done |
| | | T11 | Deployment & Services Evidence | Documentar los enlaces de producción desplegados y las métricas de colaboración del equipo en GitHub. | 4 hrs | Fernández | Done |
| US-01 | Descripción principal en el Hero Section | T12 | Desarrollo: Hero Section | Maquetar en HTML/CSS/JS la cabecera principal con el mensaje sobre optimización IoT de gimnasios y los CTAs de acceso al portal. | 4 hrs | Azama | Done |
| US-03 | Visualización de Soluciones y Características | T13 | Desarrollo: Módulos del Sistema | Programar la sección responsiva que detalla los seis módulos del sistema: telemetría, mapa de calor, analíticas, mantenimiento predictivo, reservas y reportes. | 4 hrs | Cataño | Done |
| US-04 | Selección de planes de suscripción SaaS | T14 | Desarrollo: Pricing Table | Maquetar la tabla de precios interactiva para los planes SaaS (Basic, Mid, Platinum) dirigidos a centros deportivos. | 4 hrs | Espinoza | Done |
| US-05 | Envío de formulario de Contacto | T15 | Desarrollo: Formulario & Validaciones | Codificar el formulario de contacto para leads comerciales con validaciones en JavaScript. | 4 hrs | Atoche | Done |
| US-06 | Acceso al portal desde la navegación | T16 | Desarrollo: Navbar & Footer | Implementar la barra de navegación superior con botones de Login y Demo visibles, y el footer con enlaces institucionales. | 4 hrs | Fernández | Done |

#### Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/hero-section | e480ef9 | feat(hero-section): add background animations | - | 2026-04-19 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/header | ed84ec5 | feat: add header | - | 2026-04-19 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | 6a2919f | chore: project-setup | - | 2026-04-18 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | main | 3871093 | Initial commit | - | 2026-04-18 |

#### Execution Evidence for Sprint Review

A lo largo de esta primera iteración del proyecto SpotTrack, logramos consolidar el diseño estratégico del sistema apoyándonos en la elaboración de artefactos de Domain-Driven Design orientados al dominio de telemetría IoT para gimnasios, así como en el modelado estructural de la base de datos. Esta arquitectura, diseñada para integrarse con sensores Edge que capturan el estado de ocupación de las máquinas en tiempo real, se complementó con una exhaustiva investigación de Experiencia de Usuario (UX/UI) enfocada en los dolores reales de administradores de centros deportivos y clientes frecuentes de gimnasio.


#### Team Collaboration Insights during Sprint

### Sprint 2

#### Sprint Planning 2

El presente apartado detalla los acuerdos y objetivos definidos durante el Sprint Planning Meeting de nuestra segunda iteración. Para este Sprint, el equipo se enfocó en dos frentes de trabajo simultáneos: (1) la corrección y completitud de todos los artefactos pendientes del Sprint 1, incluyendo el despliegue completo de la Landing Page; y (2) el inicio del desarrollo frontend de la Web Application principal (Angular), empleando una Fake API (JSON Server) como capa de datos simulada para desacoplar el desarrollo frontend del backend real, cuya implementación se reserva para el Sprint 3.

| Aspect | Details |
| :--- | :--- |
| **Sprint #** | Sprint 2 |
| **Date** | 2026-05-08 |
| **Time** | 10:00 AM |
| **Location** | Reunión Virtual (Discord / Microsoft Teams) |
| **Prepared By** | Azama Fukuda, Juan Pablo |
| **Attendees (to planning meeting)** | Atoche Gonzales, Nicolas Fernando / Azama Fukuda, Juan Pablo / Cataño Zarate, Jesus Miguel / Espinoza Orrego, Valentino Andre / Fernández Linares, Alvaro Sebastian |
| **Sprint n – 1 Review Summary** | Sprint 1 entregó los artefactos fundacionales de Lean UX, DDD, diseño UX/UI en Figma y el inicio de la Landing Page (Hero Section y Header). Sin embargo, quedaron pendientes el despliegue, las secciones de módulos, precios y contacto de la Landing Page, así como diversas secciones de documentación del informe. |
| **Sprint n – 1 Retrospective Summary** | El equipo identificó que la carga de trabajo de documentación y diseño subestimó el tiempo necesario. Para este Sprint 2 se priorizará paralelizar la corrección de Sprint 1 con el inicio del desarrollo de la Web App, asignando responsables claros por cada frente. |
| **Sprint Goal** | Nuestro enfoque es completar todos los artefactos pendientes del Sprint 1 (correcciones de documentación y Landing Page completa) e iniciar el desarrollo frontend de la Web Application de SpotTrack consumiendo una Fake API, implementando las vistas de autenticación, mapa de calor, gestión de activos, alertas de mantenimiento y sugerencias de rutinas. Esto se confirmará cuando la Landing Page esté desplegada y funcional con todas sus secciones, y las vistas frontend de las User Stories priorizadas estén implementadas y navegables en el entorno de desarrollo local. |
| **Sprint n Velocity** | 58 Story Points |
| **Sum of Story Points** | 58 |

#### Aspect Leaders and Collaborators

Para este Sprint 2, el equipo adoptó una estructura dual de trabajo: un subequipo dedicado a las correcciones del Sprint 1 (documentación + Landing Page) y otro enfocado en el desarrollo frontend de la Web Application. Esta división permite avanzar en paralelo sin bloqueos entre tareas de distinta naturaleza.

| Team Member (Last Name, First Name) | GitHub Username | Aspect 1: Sprint 1 Corrections Leader (L) / Collaborator (C) | Aspect 2: Angular App Setup & Auth Leader (L) / Collaborator (C) | Aspect 3: Client App Frontend (Heatmap & Routines) Leader (L) / Collaborator (C) | Aspect 4: Admin Dashboard Frontend Leader (L) / Collaborator (C) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Azama Fukuda, Juan Pablo | llummo | Corrections (C) | Angular App Setup (L) | Client App (C) | Admin Dashboard (C) |
| Atoche Gonzales, Nicolas Fernando | THECOMAX | Corrections (C) | Fake API Config (L) | Client App (C) | Admin Dashboard (C) |
| Cataño Zarate, Jesus Miguel | jcuz1510 | Landing Page Completion (L) | Angular App Setup (C) | Client App (C) | Admin Dashboard (C) |
| Espinoza Orrego, Valentino Andre | valentinoespinoza13 | Corrections (C) | Angular App Setup (C) | Client App (C) | Admin Dashboard (L) |
| Fernández Linares, Alvaro Sebastian | ORION-tech-c | Corrections (L) | Angular App Setup (C) | Client App (L) | Admin Dashboard (C) |

#### Sprint Backlog

> **Nota:** Las filas con prefijo `CORR-` y `SETUP-` son **storyless** — no corresponden a ninguna User Story y no tienen Story Points asignados, pero son obligatorias para subsanar deficiencias del Sprint anterior y preparar el entorno de desarrollo.

| Id | Title | Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| - | Corrección Sprint 1 | CORR-01 | Completar sección "The Solution" en Landing Page | Maquetar las seis tarjetas de soluciones del sistema (US-03 pendiente) con HTML/CSS responsivo. | 4 hrs | Cataño | Done |
| - | Corrección Sprint 1 | CORR-02 | Completar Pricing Table en Landing Page | Implementar la tabla comparativa de planes SaaS Basic/Mid/Platinum con CTAs (US-04 pendiente). | 4 hrs | Cataño | Done |
| - | Corrección Sprint 1 | CORR-03 | Completar formulario de Contacto en Landing Page | Codificar el formulario de contacto con validaciones JavaScript (US-05 pendiente). | 4 hrs | Espinoza | Done |
| - | Corrección Sprint 1 | CORR-04 | Completar Navbar y Footer de Landing Page | Implementar la barra de navegación sticky con anchor links y el footer con enlaces institucionales (US-06 pendiente). | 4 hrs | Fernández | Done |
| - | Corrección Sprint 1 | CORR-05 | Despliegue de Landing Page en producción | Configurar y publicar la Landing Page en GitHub Pages (T08 pendiente). Documentar el enlace de producción. | 4 hrs | Azama | Done |
| - | Corrección Sprint 1 | CORR-06 | Completar Diagrama ERD y Diagrama de Clases | Finalizar y subir el ERD y el Diagrama de Clases UML al repositorio (T04 pendiente). Actualizar referencias en el informe. | 4 hrs | Atoche / Cataño | Done |
| - | Corrección Sprint 1 | CORR-07 | Completar evidencias del Sprint 1 en el informe | Añadir capturas de pantalla de la Landing Page, commits reales y métricas de GitHub Insights en Development Evidence, Execution Evidence y Team Collaboration Insights. | 4 hrs | Espinoza / Fernández | Done |
| - | Corrección Sprint 1 | CORR-08 | Completar Big Picture Event Storming (Capítulo II) | Elaborar y añadir el Big Picture Event Storming al Capítulo II (sección actualmente vacía). | 4 hrs | Atoche | Done |
| - | Corrección Sprint 1 | CORR-09 | Completar sección Software Deployment Configuration (Capítulo V) | Redactar la descripción del entorno de despliegue, pipelines CI/CD y hosting utilizados. | 4 hrs | Azama | Done |
| - | Corrección Sprint 1 | CORR-10 | Completar Project Report Collaboration Insights (Capítulo 0) | Añadir la descripción de la colaboración del equipo en el desarrollo del informe con evidencia de GitHub. | 4 hrs | Espinoza | Done |
| - | Corrección Sprint 1 | CORR-11 | Agregar Student Outcome de Cataño Zárate (Capítulo 0) | Añadir las entradas de "Comunica oralmente" y "Comunica por escrito" para Jesús Miguel Cataño Zárate, actualmente ausentes de la tabla. | 4 hrs | Cataño | Done |
| - | Corrección Sprint 1 | CORR-12 | Estandarizar análisis de entrevistas 4 y 5 | Añadir el campo "Resumen" completo a las entrevistas de Joan Steffano Quispe (Entrevistado 4) y Fabián Suárez (Entrevistado 5), siguiendo el mismo formato de las entrevistas 1–3. | 4 hrs | Fernández | Done |
| - | Corrección Sprint 1 | CORR-13 | Subir fotos faltantes de integrantes del equipo | Agregar al repositorio las imágenes `foto-valentino.jpeg`, `foto-nicolas.png` y `foto-jesus-c.png`, referenciadas en el Capítulo I pero ausentes en la carpeta assets. | 4 hrs | Azama / Cataño | Done |
| - | Corrección Sprint 1 | CORR-14 | Corregir inconsistencia de tech stack (ASP.NET vs Spring Boot) | En el Sprint 1 Backlog, la tarea T05 menciona "Spring Boot" como backend, pero el tech stack oficial declara Spring Boot. Corregir la descripción de T05 en el informe. | 4 hrs | Azama | Done |
| - | Corrección Sprint 1 | CORR-15 | Corregir nombre de marca en análisis competitivo | La tabla de análisis competitivo usa "SpotTrack" (nombre antiguo) en lugar de "SpotTrack". Actualizar todas las instancias en el Capítulo II. | 4 hrs | Espinoza | Done |
| - | Setup Web App | SETUP-01 | Crear proyecto Angular con estructura por Bounded Contexts | Inicializar el proyecto Angular (ng new spottrack-app), configurar la estructura de carpetas por bounded context: `auth/`, `heatmap/`, `admin/`, `maintenance/`, `equipment/`, `routines/`, `shared/`, `analytics/`. | 4 hrs | Azama | Done |
| - | Setup Web App | SETUP-02 | Configurar JSON Server como Fake API | Instalar y configurar `json-server` con un `db.json` que contenga datos seed para: `users`, `equipments`, `IoT`, `alerts`, `tickets`, `reservations`, `routines/alternatives`, `analytics`. Exponer en `localhost:3000`. | 4 hrs | Atoche | Done |
| - | Setup Web App | SETUP-03 | Documentar Sprint 2 Planning, Backlog y evidencias en el informe | Redactar las secciones de Sprint Planning 2, Aspect Leaders y Sprint Backlog en el Capítulo V. Al finalizar el sprint, completar Development Evidence, Execution Evidence y Team Collaboration Insights. | 4 hrs | Espinoza | Done |
| US26 | Gestión de activos físicos y altas | T01 | Implement equipment registration form | Build the UI form to register new equipment linked to an IoT sensor | 6 | Juan Pablo | Done |
| US26 | Gestión de activos físicos y altas | T02 | Implement equipment decommission flow | Add decommission action and confirmation dialog | 4 | Juan Pablo | Done |
| US21 | Monitoreo de estado de hardware Edge IoT | T03 | Build IoT node health dashboard view | Display connected/disconnected status per sensor node | 5 | Juan Pablo | Done |
| US21 | Monitoreo de estado de hardware Edge IoT | T04 | Implement reconnection status sync | Handle state sync when a node reconnects | 4 | Juan Pablo | Done |
| TS12 | Registrar evento de telemetría IoT API | T05 | Implement POST /api/v1/telemetry endpoint | Receive and process IoT sensor state events | 5 | Juan Pablo | Done |
| TS12 | Registrar evento de telemetría IoT API | T06 | Validate telemetry payload and auth | Return 400 on malformed or unauthorized payloads | 4 | Juan Pablo | Done |
| TS13 | Listar historial de uso general API | T07 | Implement GET /api/v1/telemetry endpoint | Return usage history array filtered by date range | 4 | Juan Pablo | Done |
| US08 | Gestión de preferencias y perfil | T08 | Build profile edit view | Allow user to update personal data and language preference | 4 | Jesús | Done |
| US08 | Gestión de preferencias y perfil | T09 | Implement language toggle i18n | Wire language selector to i18n service | 4 | Jesús | Done |
| US12 | Notificaciones push de disponibilidad | T10 | Build availability bell subscription UI | Allow client to subscribe to machine availability alert | 4 | Jesús | Done |
| US12 | Notificaciones push de disponibilidad | T11 | Display push notification on machine release | Show notification when subscribed machine becomes free | 4 | Jesús | Done |
| US13 | Sistema de recompensas Crowdsourcing | T12 | Build manual status report UI | Allow client to report machine status manually | 5 | Jesús | Done |
| US13 | Sistema de recompensas Crowdsourcing | T13 | Display reward points in profile | Show accumulated points after validated report | 4 | Jesús | Done |
| US24 | Notificación de restablecimiento a usuarios | T14 | Show restoration notification to clients | Notify clients when a repaired machine is back online | 4 | Nicolas | Done |
| US09 | Visualización del mapa de calor en vivo | T15 | Build interactive heatmap component | Render machine availability map with green/red indicators | 8 | Juan Pablo | Done |
| US09 | Visualización del mapa de calor en vivo | T16 | Implement real-time status update via polling | Auto-update machine icons without page reload | 6 | Juan Pablo | Done |
| US10 | Filtrado del inventario por tipo de máquina | T17 | Implement filter tags component | Add Fuerza/Cardio filter tags to heatmap | 4 | Juan Pablo | Done |
| US10 | Filtrado del inventario por tipo de máquina | T18 | Implement clear filters action | Restore full inventory on filter clear | 4 | Juan Pablo | Done |
| US11 | Cambio de sucursal para revisión de aforo | T19 | Implement branch selector component | Allow user to switch branches and reload heatmap | 4 | Juan Pablo | Done |
| US11 | Cambio de sucursal para revisión de aforo | T20 | Block premium branch for basic plan users | Show upgrade suggestion when branch access is denied | 4 | Juan Pablo | Done |
| US14 | Motor de sugerencia de rutinas alternativas | T21 | Build alternative routine suggestion view | Show alternative exercises when selected machine is occupied | 6 | Álvaro | Done |
| US14 | Motor de sugerencia de rutinas alternativas | T22 | Handle no-alternatives scenario | Suggest bodyweight exercises when gym is at full capacity | 4 | Álvaro | Done |
| US15 | Filtrado de alternativas por grupo muscular | T23 | Filter suggestions by target muscle group | Discard exercises from other muscle groups in suggestions | 4 | Álvaro | Done |
| US15 | Filtrado de alternativas por grupo muscular | T24 | Exclude machines with open tickets from suggestions | Filter out equipment in maintenance from suggestions | 4 | Álvaro | Done |
| US16 | Sistema de reserva exprés en horas pico | T25 | Build express reservation button and timer UI | Show yellow status and countdown on reservation | 5 | Álvaro | Done |
| US16 | Sistema de reserva exprés en horas pico | T26 | Implement reservation expiry release flow | Return machine to free state when timer runs out | 4 | Álvaro | Done |
| US25 | Calendario inteligente de bloqueos | T27 | Build smart schedule view with peak-hour warnings | Show warning when client selects high-demand slot | 5 | Álvaro | Done |
| US25 | Calendario inteligente de bloqueos | T28 | Implement valley-hour suggestion on conflict | Suggest off-peak alternative when peak slot is selected | 4 | Álvaro | Done |
| TS18 | Crear reserva exprés API | T29 | Implement POST /api/v1/reservations endpoint | Execute logical machine block during high demand | 5 | Nicolas | Done |
| TS19 | Cancelar reserva exprés API | T30 | Implement PUT /api/v1/reservations/{id}/cancel endpoint | Release machine block on timer expiry or user abort | 4 | Nicolas | Done |
| TS20 | Obtener sugerencias de rutinas API | T31 | Implement GET /api/v1/routines/alternatives endpoint | Run replacement algorithm by muscle group and availability | 5 | Nicolas | Done |
| TS20 | Obtener sugerencias de rutinas API | T32 | Handle bodyweight fallback in suggestions | Return bodyweight alternatives when no machines are free | 4 | Nicolas | Done |
| TS14 | Obtener picos de afluencia por día API | T33 | Implement GET /api/v1/analytics/peak-hours endpoint | Identify hourly blocks exceeding 90% capacity | 5 | Nicolas | Done |
| TS15 | Exportar reporte gerencial API | T34 | Implement GET /api/v1/analytics/export/pdf endpoint | Generate binary PDF stream of monthly usage report | 5 | Nicolas | Done |
| TS16 | Registrar estado manual de máquina API | T35 | Implement POST /api/v1/machines/{id}/manual-reports endpoint | Save crowdsourcing report to validation queue | 4 | Nicolas | Done |
| TS17 | Sumar puntos de recompensa API | T36 | Implement PUT /api/v1/users/{id}/points endpoint | Increment points when manual report matches IoT reading | 4 | Nicolas | Done |
| TS21 | Crear ticket de mantenimiento API | T37 | Implement POST /api/v1/tickets endpoint | Register incident and set machine to In Maintenance | 4 | Nicolas | Done |
| TS22 | Listar tickets activos/históricos API | T38 | Implement GET /api/v1/tickets endpoint | Return filtered ticket backlog by branch or status | 4 | Nicolas | Done |
| TS23 | Resolver ticket técnico API | T39 | Implement PUT /api/v1/tickets/{id}/resolve endpoint | Close ticket and return machine to free status | 4 | Nicolas | Done |
| TS24 | Generar alerta predictiva API | T40 | Implement POST /api/v1/alerts endpoint | Auto-generate alert when usage exceeds safe threshold | 5 | Nicolas | Done |
| TS25 | Programar bloqueo de mantenimiento API | T41 | Implement POST /api/v1/maintenance-blocks endpoint | Validate maintenance schedule against peak-hour conflicts | 5 | Nicolas | Done |
| TS26 | Calcular impacto financiero API | T42 | Implement GET /api/v1/analytics/financial-impact endpoint | Convert downtime hours to monetary loss estimate | 5 | Nicolas | Done |
| TS27 | Simular ROI API | T43 | Implement POST /api/v1/analytics/roi-projection endpoint | Run ROI simulation based on stress telemetry | 5 | Nicolas | Done |
| TS05 | Crear nueva máquina API | T44 | Implement POST /api/v1/machines endpoint | Register new equipment linked to IoT sensor | 4 | Nicolas | Done |
| TS06 | Listar máquinas por sede API | T45 | Implement GET /api/v1/machines endpoint | Return full inventory filtered by branchId | 4 | Nicolas | Done |
| TS07 | Mostrar máquina por Id API | T46 | Implement GET /api/v1/machines/{id} endpoint | Return detailed physical and logical machine data | 4 | Nicolas | Done |
| TS08 | Actualizar/Reubicar máquina API | T47 | Implement PUT /api/v1/machines/{id} endpoint | Allow branch reassignment or attribute update | 4 | Nicolas | Done |
| TS09 | Dar de baja máquina API | T48 | Implement DELETE /api/v1/machines/{id} endpoint | Apply soft-delete and unlink IoT sensor | 4 | Nicolas | Done |
| TS10 | Registrar repuesto en inventario API | T49 | Implement POST /api/v1/inventory endpoint | Add new spare part to maintenance stock | 4 | Nicolas | Done |
| TS11 | Actualizar stock de repuesto API | T50 | Implement PUT /api/v1/inventory/{id}/stock endpoint | Discount materials when a ticket is resolved | 4 | Nicolas | Done |
| US17 | Acumulación automática de horas de uso | T51 | Build equipment usage hours chart | Display cumulative usage minutes per machine | 5 | Valentino | Done |
| US17 | Acumulación automática de horas de uso | T52 | Implement date range filter on usage chart | Recalculate totals based on selected period | 4 | Valentino | Done |
| US18 | Identificación de equipos subutilizados | T53 | Build underutilized equipment table | Highlight machines below usage threshold | 4 | Valentino | Done |
| US18 | Identificación de equipos subutilizados | T54 | Implement CSV export for underutilized list | Download underutilized equipment data as CSV | 4 | Valentino | Done |
| US19 | Visualización de picos de estrés del local | T55 | Build peak stress hours chart | Mark red hourly blocks exceeding 90% capacity | 5 | Valentino | Done |
| US19 | Visualización de picos de estrés del local | T56 | Implement intersemanal comparison overlay | Superimpose two trend lines for weekly comparison | 4 | Valentino | Done |
| US20 | Exportación de analíticas de uso | T57 | Build PDF export button on dashboard | Trigger formatted PDF download from analytics view | 4 | Valentino | Done |
| US20 | Exportación de analíticas de uso | T58 | Handle export delay with email fallback notice | Show deferred notice when server is under load | 4 | Valentino | Done |
| US22 | Alerta predictiva de mantenimiento | T59 | Build maintenance alert banner component | Display predictive alert when threshold is exceeded | 5 | Nicolas | Done |
| US22 | Alerta predictiva de mantenimiento | T60 | Implement manual threshold configuration UI | Allow manager to set safe hours limit per machine | 4 | Nicolas | Done |
| US23 | Despacho automatizado de tickets técnicos | T61 | Build assign-to-support action on alert | Convert alert to ticket and notify technician | 4 | Nicolas | Done |
| US23 | Despacho automatizado de tickets técnicos | T62 | Update machine status to In Maintenance on ticket creation | Reflect maintenance state on public heatmap | 4 | Nicolas | Done |
| US27 | Estadísticas de reubicación multisede | T63 | Build cross-branch utilization stats view | Show demand comparison between branches | 6 | Valentino | Done |
| US27 | Estadísticas de reubicación multisede | T64 | Display relocation recommendation card | Show transfer suggestion when demand imbalance is detected | 4 | Valentino | Done |
| US28 | Gestión automatizada de stock de repuestos | T65 | Build spare parts inventory table | Show current stock per part with restock alert indicator | 4 | Nicolas | Done |
| US28 | Gestión automatizada de stock de repuestos | T66 | Implement restock alert notification display | Show alert when part reaches minimum stock level | 4 | Nicolas | Done |
| US29 | Calculadora de impacto financiero | T67 | Build financial impact module view | Display estimated monetary loss per machine downtime | 5 | Valentino | Done |
| US29 | Calculadora de impacto financiero | T68 | Show monthly inefficiency cost chart | Render total hidden cost from equipment inactivity | 4 | Valentino | Done |
| US30 | Analítica predictiva de compras e inversión | T69 | Build ROI projection simulation view | Allow manager to input acquisition cost and see ROI estimate | 5 | Valentino | Done |
| US30 | Analítica predictiva de compras e inversión | T70 | Display purchase recommendation on saturation | Show buy suggestion when machine consistently exceeds max capacity | 4 | Valentino | Done |

Trello board: https://trello.com/invite/b/69fc21c2d05be44be499c75d/ATTI944e7a75fa88bba093494745abbec4eb6F6DB156/spottrack-tb1


![](../assets/trello-evidence.png)

Si bien es cierto se solicitó el desarrollo de un Trello board, nuestro equipo principalmente decidió utilizar la plataforma de Jira para la asignación de tareas.
![](../assets/jira-evidence.png)



#### Development Evidence for Sprint Review

Frontend Web Applications Commits:

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | d3a30e2 | Merge pull request #40 from SpotTrack-1ASI0729-2610-11881/fix/mantainance | fix: fix base infrastructure not being used | 2026-05-10 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | fix/mantainance | 94bb1f9 | fix: fix base infrastructure not being used | - | 2026-05-10 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 424a52d | Merge pull request #39 from SpotTrack-1ASI0729-2610-11881/feature/client-booking | added booking section | 2026-05-10 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/client-booking | 3a88e65 | added booking section | - | 2026-05-10 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | d16b42b | Merge pull request #38 from SpotTrack-1ASI0729-2610-11881/feature/analytics | chore: analytics context structured | 2026-05-10 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/analytics | 0f0df28 | chore: analytics context structured | - | 2026-05-10 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 9e5e94a | Merge pull request #37 from SpotTrack-1ASI0729-2610-11881/feature/client-map | add map view | 2026-05-10 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/client-map | 4f093fa | add map view | - | 2026-05-10 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | e02b3e6 | Merge pull request #36 from SpotTrack-1ASI0729-2610-11881/feature/analytics | feat(analytics): add analytics section | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/analytics | d224048 | feat(analytics): add analytics section | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 139bca7 | Merge pull request #35 from SpotTrack-1ASI0729-2610-11881/feature/client-map | separe bottombar from layout | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/client-map | 9ac8232 | separe bottombar from layout | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 660ba4f | Merge pull request #34 from SpotTrack-1ASI0729-2610-11881/feature/mantainance | feat(mantainance): add mantainace section | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/mantainance | c9a42db | feat(mantainance): add mantainace section | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 50ad787 | Merge pull request #33 from SpotTrack-1ASI0729-2610-11881/fast-hotfix | fixerrors | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | fast-hotfix | dd10791 | fixerrors | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 8bbb3e4 | Merge pull request #32 from SpotTrack-1ASI0729-2610-11881/feature/client-app | Feature/client app | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/client-app | 448b08e | Merge branch 'develop' into feature/client-app | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/client-app | 9f45f61 | add new properties client&admin | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/client-app | f3e9dc1 | Views adjusted also added proper preview components | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/client-app | 87e85ff | added-switch-button-between-client&admin | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 4522b29 | Merge pull request #31 from SpotTrack-1ASI0729-2610-11881/feature/login | fix: build fix | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/login | 0053e96 | fix: build fix | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 7b32797 | Merge pull request #30 from SpotTrack-1ASI0729-2610-11881/feature/login | feat: add login screen | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/login | 68cc54e | feat: add login screen | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 183bc13 | Merge pull request #29 from SpotTrack-1ASI0729-2610-11881/feature/iot-monitoring | fix: translation in iot monitoring section didnt work | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/iot-monitoring | 10c6cd0 | fix: translation in iot monitoring section didnt work | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | ae98bd6 | Merge pull request #28 from SpotTrack-1ASI0729-2610-11881/feature/iot-monitoring-2 | feat: IoT monitoring latest version | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/iot-monitoring-2 | 96a0b95 | feat: IoT monitoring latest version | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 76b164c | Merge pull request #27 from SpotTrack-1ASI0729-2610-11881/feature/configuration | Add configuration section | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/configuration | 414aa67 | Add configuration section | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | main | 2c1aa9b | Revert "Merge pull request #18 from SpotTrack-1ASI0729-2610-11881/US-24" | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 1c35ac9 | Merge pull request #25 from SpotTrack-1ASI0729-2610-11881/fix/endpoint-equipment | fix: equipents endopoint hardcoded | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | fix/endpoint-equipment | f2e5559 | fix: equipents endopoint hardcoded | - | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 2695fe5 | Merge pull request #24 from SpotTrack-1ASI0729-2610-11881/fix/endpoints | fix: register new equipment route renamed | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | fix/endpoints | 9e5b897 | fix: register new equipment route renamed | - | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | cb357fc | Merge pull request #23 from SpotTrack-1ASI0729-2610-11881/fix/endpoints | fix: equipents route fixed | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | fix/endpoints | 6172264 | fix: equipents route fixed | - | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | cc80283 | Merge pull request #22 from SpotTrack-1ASI0729-2610-11881/fix/endpoints | fix: rename equipent routes | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | fix/endpoints | ed95636 | fix: rename equipent routes | - | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 050fb54 | ci: add Azure Static Web Apps workflow file | - | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 83e0b66 | Merge pull request #21 from SpotTrack-1ASI0729-2610-11881/chore/production | chore: add production api | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | chore/production | 4f820da | chore: add production api | - | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 760fe04 | Merge pull request #20 from SpotTrack-1ASI0729-2610-11881/chore/production | chore: add dist folder | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | chore/production | b852edf | chore: add dist folder | - | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 65c1a21 | Merge pull request #19 from SpotTrack-1ASI0729-2610-11881/chore/dist | chore: configure rewrite rule for SPA | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | chore/dist | 75b24fd | chore: configure rewrite rule for SPA | - | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | dbd63df | Merge pull request #18 from SpotTrack-1ASI0729-2610-11881/US-24 | Add initial configurations components | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | US-24 | 82b1833 | Add initial configurations components | - | 2026-05-08 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 1ed2967 | Merge pull request #17 from SpotTrack-1ASI0729-2610-11881/feature/iot-monitoring | feat: add monitoring section initial version | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/iot-monitoring | a23eba3 | feat: add monitoring section initial version | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | b8a8cf5 | Merge pull request #16 from SpotTrack-1ASI0729-2610-11881/fix/equipment | Fix/equipment | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | fix/equipment | 1dd31ba | fix: fix equipment.entity structure | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | fix/equipment | 91555b7 | feat: add IoT entity | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 985f74c | Merge pull request #15 from SpotTrack-1ASI0729-2610-11881/feature/sidebar | feat: add configuration to sidebar | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/sidebar | 456b712 | feat: add configuration to sidebar | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 84d2e87 | Merge pull request #14 from SpotTrack-1ASI0729-2610-11881/feature/sidebar | feat: add dashboard to the sidebar | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/sidebar | bc619c3 | feat: add dashboard to the sidebar | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | c9f20a0 | Merge pull request #13 from SpotTrack-1ASI0729-2610-11881/feature/sidebar | feat(sidebar): add sidebar | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/sidebar | a3d59a5 | feat(sidebar): add sidebar | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | cd26e26 | Merge pull request #12 from SpotTrack-1ASI0729-2610-11881/feature/equipment | feat(equipment): add register equipment and equipment section | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/equipment | 95f0342 | feat(equipment): add register equipment and equipment section | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | d43d059 | Merge pull request #11 from SpotTrack-1ASI0729-2610-11881/feature/equipment | Feature/equipment | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/equipment | ac98a93 | feat: working json server methods for equipment feature | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/equipment | 6f70b17 | feat: add equipment store | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | e1c2a86 | Merge pull request #10 from SpotTrack-1ASI0729-2610-11881/feature/equipment | feat: add partially working us-26 with json server set up | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/equipment | eabed49 | feat: add partially working us-26 with json server set up | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 9fefd90 | Merge pull request #9 from SpotTrack-1ASI0729-2610-11881/feature/equipment | Feature/equipment | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/equipment | 8ace1b1 | feat: add presentation layer for equipment related user stories | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/equipment | c9fe227 | feat: finished equipment APIs, assemblers and reponses | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/equipment | f5e6b9e | feat: add equipment infrastructure | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | cd8c1a0 | Merge pull request #8 from SpotTrack-1ASI0729-2610-11881/chore/json-local-server | feat: structure equipment infrastructure | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | chore/json-local-server | bcd9596 | feat: structure equipment infrastructure | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | cbda4b1 | Merge pull request #7 from SpotTrack-1ASI0729-2610-11881/chore/json-local-server | chore: setup db.json | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | chore/json-local-server | 6164e8c | chore: setup db.json | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 4caee1e | Merge pull request #6 from SpotTrack-1ASI0729-2610-11881/feature/generic-infrastructure | chore: add routing | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/generic-infrastructure | d2fdd81 | chore: add routing | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/generic-infrastructure | 13dc0d4 | chore: add routing | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | df621bc | Merge pull request #5 from SpotTrack-1ASI0729-2610-11881/feature/generic-infrastructure | Feature/generic infrastructure | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/generic-infrastructure | ec0489d | feat: add equipment bounded context presentation and i18n | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/generic-infrastructure | b1d97c7 | docs: add class diagrams frontend | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 67fc548 | Merge pull request #4 from SpotTrack-1ASI0729-2610-11881/feature/generic-infrastructure | feat: add base apis, responses, entities and assembler | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/generic-infrastructure | 03697f5 | feat: add base apis, responses, entities and assembler | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | f385091 | Merge pull request #3 from SpotTrack-1ASI0729-2610-11881/feature/generic-infrastructure | feat: setup shared bounded context | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/generic-infrastructure | c6345ac | feat: setup shared bounded context | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 7c2c65d | Merge pull request #2 from SpotTrack-1ASI0729-2610-11881/feature/US-26 | chore: add equipment bounded context | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/US-26 | 8102bfa | chore: add equipment bounded context | - | 2026-05-04 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | develop | 29dcac5 | Merge pull request #1 from SpotTrack-1ASI0729-2610-11881/feature/class-diagrams | docs: add class diagrams | 2026-04-24 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/class-diagrams | 1308f7a | docs: add class diagrams | - | 2026-04-24 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | feature/init-testing | 66d1157 | feat: add initial angular testing program | - | 2026-04-15 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | main | 5fd40ea | chore: initial commit | - | 2026-04-14 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | main | 39f083c | chore:second commit | - | 2026-04-06 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | main | ec1c353 | chore:initial commit | - | 2026-04-06 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications | main | fd32baf | Initial commit | - | 2026-04-06 |

Landing Page Commits

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | f6eba3a | Merge pull request #17 from SpotTrack-1ASI0729-2610-11881/feature/contact-email | feat:add-email-sender | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/contact-email | df0057d | feat:add-email-sender | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | ba302d6 | Merge pull request #16 from SpotTrack-1ASI0729-2610-11881/fix/contact-section-i18n | fixed:i18n contanct and footer | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | fix/contact-section-i18n | cdb34bc | fixed:i18n contanct and footer | - | 2026-05-09 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | 62a2b97 | Merge pull request #15 from SpotTrack-1ASI0729-2610-11881/fix/contact-section | fixed: add-angular-materials | 2026-05-07 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | 9380f51 | Merge pull request #13 from SpotTrack-1ASI0729-2610-11881/landing/hotfix-features | landing-fix | 2026-05-07 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | landing/hotfix-features | 7564abb | landing-fix | - | 2026-05-07 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/contact-section | a95b603 | Merge branch 'develop' into feature/contact-section | - | 2026-05-07 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/contact-section | 248395f | fixed: add-angular-materials | - | 2026-05-07 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | 009da6e | Merge pull request #11 from SpotTrack-1ASI0729-2610-11881/feature/footer-section | feat:add-footer-section | 2026-05-07 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/footer-section | 914917c | Merge branch 'develop' into feature/footer-section | - | 2026-05-07 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/footer-section | 04fb8c8 | feat:add-footer-section | - | 2026-05-07 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | db87823 | Merge pull request #10 from SpotTrack-1ASI0729-2610-11881/landing/features-section | Landing/features section | 2026-05-07 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | landing/features-section | ae25905 | landing-feature-implementation-v2 | - | 2026-05-07 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | landing/features-section | de4178a | landing-feature-implementation | - | 2026-05-07 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | d98b24a | Merge pull request #9 from SpotTrack-1ASI0729-2610-11881/feature/contact-section | Feature/contact section | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/contact-section | 212b557 | feat:source correction | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/contact-section | f083ae0 | Merge branch 'feature/contact-section' into feature/contact-section | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/contact-section | c5e629f | feat:add-contact | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | 11cb386 | Merge pull request #8 from SpotTrack-1ASI0729-2610-11881/chore/github-pages | fix: github pages only showed readme.md | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | chore/github-pages | 742612a | fix: github pages only showed readme.md | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | 8c34fe6 | Merge pull request #7 from SpotTrack-1ASI0729-2610-11881/chore/github-pages | Chore/GitHub pages | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | chore/github-pages | 1fb2b77 | fix: switch deployment branch | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | chore/github-pages | 1831ca2 | chore: add github pages | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | b414365 | Merge pull request #6 from SpotTrack-1ASI0729-2610-11881/fix/stripe | fix: add environments and services | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | fix/stripe | 7c2a041 | fix: add environments and services | - | 2026-05-05 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | cf91d30 | Merge pull request #5 from SpotTrack-1ASI0729-2610-11881/feature/hero-header | fix: fix login button height | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/hero-header | f3804cb | fix: fix login button height | - | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/hero-header | d3b9348 | fix: fix login button height | - | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | 6357640 | Merge pull request #4 from SpotTrack-1ASI0729-2610-11881/feature/hero-header | fix: hero section completed | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/hero-header | cb21759 | fix: hero section completed | - | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | ae2957c | Merge pull request #3 from SpotTrack-1ASI0729-2610-11881/feature/niubiz | feat(stripe): add stripe payments | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/niubiz | 1aa12f4 | feat(stripe): add stripe payments | - | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | db9a16c | Merge pull request #2 from SpotTrack-1ASI0729-2610-11881/feature/pricing | fix: fix pricing cards organization | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/pricing | b996a8a | fix: fix pricing cards organization | - | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | 8b00971 | Merge pull request #1 from SpotTrack-1ASI0729-2610-11881/feature/pricing | Feature/pricing | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/pricing | d732028 | feat(pricing): add pricing section | - | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/pricing | 76e113d | feat(en-es): add diciontarios for en and es | - | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/pricing | 0138b31 | feat(i18n): add language switcher component | - | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/pricing | 68b1da4 | chore: add translate service | - | 2026-05-03 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | e480ef9 | feat(hero-section): add background animations | - | 2026-04-19 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | ed84ec5 | feat: add header | - | 2026-04-19 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | 6a2919f | chore: project-setup | - | 2026-04-18 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | main | 3871093 | Initial commit | - | 2026-04-18 |

#### Execution Evidence for Sprint Review

Se logró desplegar una primera versión de la aplicación web, se reailzaron correcciones en los diagramas C4, diagramas de clase, diagramas de base de datos, calidad de imágenes de figma. Finalmente, se desplegó el landing page completamente funcional con call-to-action.

Execution evidence video: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202411310_upc_edu_pe/IQAyZJfDltN7RJ8xrkWcS9TAAd0yi2YQX-Dd3K_c-9unRaM?e=LvnaDZ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

#### Services Documentation Evidence for Sprint Review

Para este Sprint, se ha implementado y desplegado con éxito un Mock API utilizando JSON-Server, alojado en Azure App Service. Este servicio proporciona un backend funcional para el proyecto SpotTrack, permitiendo la persistencia de datos y la integración con el frontend. Se configuró un flujo de CI/CD mediante GitHub Actions, integrando el perfil de publicación de Azure como un secreto de organización. La API está configurada con un prefijo /api/v1 y soporta operaciones CRUD completas, facilitando el desarrollo paralelo de las funcionalidades de monitoreo de equipos y gestión de dispositivos IoT.

##### Relación de Endpoints Documentados

| Endpoint | Acción | Verbo HTTP | Sintaxis de Llamada      | Ejemplo de Response | Explicación |
|---|---|---|--------------------------|---|---|
| `/gyms` | Listar / Crear | `GET`, `POST` | `/api/v1/gyms`           | `{ "id": 1, "name": "FitNode Central", "subscription_tier": "Premium", "created_at": "2026-05-01T10:00:00Z" }` | Gestión de la entidad principal del gimnasio. |
| `/branches` | Listar / Crear | `GET`, `POST` | `/api/v1/branches`              | `{ "id": 1, "gym_id": 1, "name": "Main Branch", "address": "123 Main Street", "city": "Lima" }` | Información de sedes físicas. |
| `/zones` | Listar / Crear | `GET`, `POST` | `/api/v1/zones`                 | `{ "id": 1, "branch_id": 1, "name": "Cardio Zone", "capacity_limit": 20 }` | Áreas específicas dentro de una sede (ej. Cardio). |
| `/users` | Listar / Crear | `GET`, `POST` | `/api/v1/users`                 | `{ "id": 1, "gym_id": 1, "name": "Admin User", "email": "admin@fitnode.com", "role": "ADMIN" }` | Gestión de acceso y perfiles de usuario. |
| `/equipments` | Listar / Crear | `GET`, `POST` | `/api/v1/equipments`            | `{ "id": 1, "zone_id": 1, "name": "Treadmill", "brand": "Life Fitness", "model": "T5 Track", "status": "OPERATIONAL" }` | Inventario de máquinas de entrenamiento. |
| `/iot_devices` | Listar / Crear | `GET`, `POST` | `/api/v1/iot_devices`           | `{ "id": 1, "equipment_id": 1, "mac_address": "AA:BB:CC:DD:01", "status": "ACTIVE" }` | Dispositivos de monitoreo vinculados a equipos. |
| `/sensor_data` | Listar / Crear | `GET`, `POST` | `/api/v1/sensor_data`           | `{ "id": 1, "device_id": 1, "timestamp": "2026-05-04T09:00:00Z", "occupancy_detected": true, "vibration_index": 0.75 }` | Captura de telemetría y detección de ocupación. |
| `/usage_sessions` | Listar / Crear | `GET`, `POST` | `/api/v1/usage_sessions`        | `{ "id": 1, "equipment_id": 1, "start_time": "2026-05-04T08:00:00Z", "end_time": "2026-05-04T08:30:00Z", "calories_burned_est": 250.5 }` | Historial de uso de máquinas por sesión. |
| `/equipment_usage_stats` | Listar / Crear | `GET`, `POST` | `/api/v1/equipment_usage_stats` | `{ "id": 1, "equipment_id": 1, "total_usage_hours": 120.5, "usage_count_daily": 8, "estimated_wear_level": 0.35 }` | Estadísticas acumuladas y nivel de desgaste. |
| `/maintenance_tickets` | Listar / Crear | `GET`, `POST` | `/api/v1/maintenance_tickets`   | `{ "id": 1, "equipment_id": 2, "status": "OPEN", "priority": "HIGH", "type": "CORRECTIVE" }` | Registro de fallos y tickets de reparación. |
| `/maintenance_logs` | Listar / Crear | `GET`, `POST` | `/api/v1/maintenance_logs`      | `{ "id": 1, "ticket_id": 1, "action_description": "Replaced internal belt", "cost": 150.0 }` | Bitácora de acciones realizadas en mantenimientos. |
| `/maintenance_schedules` | Listar / Crear | `GET`, `POST` | `/api/v1/maintenance_schedules` | `{ "id": 1, "equipment_id": 1, "scheduled_date": "2026-06-01", "task_type": "LUBRICATION" }` | Planificación de mantenimientos preventivos. |
| `/spare_parts` | Listar / Crear | `GET`, `POST` | `/api/v1/spare_parts`           | `{ "id": 1, "gym_id": 1, "part_name": "Treadmill Belt", "stock_quantity": 5, "unit_cost": 80.0 }` | Inventario de repuestos para equipos. |
| `/alerts` | Listar / Crear | `GET`, `POST` | `/alerts`                | `{ "id": 1, "equipment_id": 4, "severity": "CRITICAL", "message": "Equipment out of order", "is_resolved": false }` | Notificaciones de estado crítico de equipos. |
| `/notifications` | Listar / Crear | `GET`, `POST` | `/api/v1/notifications`         | `{ "id": 1, "user_id": 1, "title": "Critical Alert", "content": "Lat Pulldown Machine is out of order", "is_read": false }` | Mensajes enviados a usuarios finales. |


##### Evidencias de Interacción con la Documentación

###### Disponibilidad del Servicio
Validación del endpoint /api/v1/health que confirma el estado "ok" del servidor en Azure.
![captura-disponibilidad-servicio.png](../assets/captura-disponibilidad-servicio.png)

###### Interacción con Recurso Equipments
Visualización de los datos de equipos obtenidos directamente desde el App Service de Azure.
![captura-equipments-db.png](../assets/captura-equipments-db.png)

##### Repositorio y Trazabilidad de Documentación

Para asegurar la transparencia y el seguimiento de los cambios, se detallan los enlaces a los repositorios de la organización.

URL Repositorio Mock API: https://github.com/SpotTrack-1ASI0729-2610-11881/SpotTrack-Mock-Api

URL Repositorio Frontend: https://github.com/SpotTrack-1ASI0729-2610-11881/SpotTrack-Frontend-Web-Applications

URL Repositorio Landing Page: https://github.com/SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page.git


#### Software Deployment Evidence for Sprint Review

Como parte de la tarea **CORR-05**, la Landing Page de SpotTrack fue desplegada exitosamente en **GitHub Pages** durante este Sprint 2. El proceso se automatizó mediante el workflow de GitHub Actions definido en `.github/workflows/deploy.yml`, el cual se activa con cada `push` a la rama `main` del repositorio `SpotTrack-Landing-Page`, asegurando despliegues continuos sin fricción.

| Producto | Entorno | URL de Producción |
| :--- | :--- | :--- |
| SpotTrack Landing Page | GitHub Pages (producción) | https://spottrack-1asi0729-2610-11881.github.io/SpotTrack-Landing-Page/ |

La siguiente figura muestra la Landing Page de SpotTrack correctamente desplegada y funcional en el entorno de producción de GitHub Pages:

![Vista de la Landing Page de SpotTrack desplegada y funcional en GitHub Pages](../assets/landing-page-deployment-evidence/lading-page-screenshot.png)


Por parte de la aplicación web, se utilizó un static web app de Azure para realizar el despliegue. Para ello, simplemente se configura la organización, repositorio y rama deseada en donde se va desplegar la aplicación, esto se vincula a un Github Actions. La activación de este último sucede en cada push a develop.

![](../assets/azure-evidence.png)
![](../assets/github-actions-webapp.png)

Webapp URL: https://purple-tree-092d40a10.7.azurestaticapps.net/

#### Team Collaboration Insights during Sprint

![](../assets/Insights/website.png)
![](../assets/Insights/webapp.png)


## Conclusiones y Recomendaciones

### Conclusiones

#### Sprint 1

La propuesta central de SpotTrack no es un sistema de reportes, sino la visibilidad en tiempo real del estado de cada máquina a través de sensores Edge. Esta telemetría pasiva —que no requiere ninguna acción del usuario— transforma directamente la experiencia del cliente en el gimnasio: este puede consultar qué máquinas están libres antes de desplazarse al local, organizar su rutina evitando tiempos de espera y obtener sugerencias de ejercicios alternativos cuando una máquina está ocupada. El mapa de calor interactivo (con indicadores verde/rojo por máquina) es la interfaz que convierte los datos del sensor en valor tangible para el usuario final, y es la razón por la que SpotTrack resuelve un problema que ningún competidor como Fitco, GYMMaster o Virtuagym puede atender sin IoT.

La telemetría acumulada por los dispositivos Edge es la materia prima de todas las capas superiores del sistema: los patrones de uso histórico alimentan las alertas de mantenimiento predictivo, las estadísticas de ocupación por hora informan las recomendaciones de horario, y los datos de desgaste acumulado sustentan las decisiones de reubicación o reemplazo de activos. Las funcionalidades analíticas y de gestión son extensiones que amplifican el valor del sensor, pero no pueden existir sin él. Esta dependencia refuerza la importancia de priorizar la estabilidad y cobertura del flujo de telemetría como fundamento de todo el sistema.

La definición de Bounded Contexts (Telemetría, Mantenimiento, Activos, Reservas, Rutinas y Analíticas) permitió que los cinco integrantes del equipo trabajaran en áreas delimitadas sin interferencias. El modelado previo mediante EventStorming fue determinante para identificar flujos críticos —como la sincronización del estado de una máquina entre el sensor, el mapa de calor y el módulo de reservas— antes de iniciar el desarrollo, lo que redujo la necesidad de refactorizaciones costosas.

La automatización del despliegue de la Landing Page en GitHub Pages garantizó que cada integración a main quedara reflejada en producción de forma inmediata y sin intervención manual. Esta práctica, implementada desde el Sprint 1, demostró que configurar el pipeline de despliegue en las etapas tempranas del proyecto elimina la fricción acumulada de los despliegues manuales y sienta las bases para extender esta automatización al backend en sprints posteriores.

#### Sprint 2

El Sprint 2 operó en dos frentes simultáneos: sanear los artefactos pendientes del Sprint 1 (15 tareas CORR + 4 tareas SETUP) e iniciar el desarrollo del frontend Angular con Fake API. Esta dualidad permitió avanzar en ambas dimensiones sin bloquear ninguna, pero evidenció que la carga de coordinación entre subequipos es significativamente mayor que en un sprint de un solo frente. La asignación de responsables claros por área (correcciones vs. desarrollo) fue determinante para mantener el flujo.

El hecho de contar con la Fake API accesible en una URL pública —y no solo en localhost— permitió que todos los integrantes del equipo consumieran el mismo backend simulado independientemente de su entorno local. Esto eliminó la clase de errores de integración más frecuente en proyectos de equipo ("funciona en mi máquina") y validó el flujo de despliegue que se reutilizará para el backend Spring Boot en el Sprint 3.

Inicializar el proyecto Angular con carpetas separadas por contexto (`auth/`, `heatmap/`, `admin/`, `maintenance/`, `equipment/`, `routines/`) demostró que los límites de dominio definidos en el DDD son aplicables también en la capa de presentación. Esta organización facilitó que cada integrante trabajara en su módulo asignado con mínima interferencia sobre el código de los demás, confirmando que la inversión en el diseño de arquitectura del Sprint 1 tiene retorno directo en la productividad del equipo de desarrollo.

---

### Recomendaciones

#### Sprint 1

Las 15 tareas de corrección abarcan deficiencias documentales y de despliegue identificadas en la revisión del Sprint 1. En particular, CORR-06 (Diagrama ERD y Diagrama de Clases), CORR-07 (evidencias de ejecución y colaboración) y CORR-08 (Big Picture EventStorming) tienen impacto directo en la calificación de entregables anteriores. Se recomienda asignar fechas límite internas por responsable y verificar su cierre antes de iniciar la documentación del Sprint Review.

Al diseñar el flujo de navegación de la Angular SPA, el mapa de calor debe ser la pantalla principal que el cliente ve inmediatamente después del login. Dado que la disponibilidad de máquinas en tiempo real es el motivo por el que un usuario abre la aplicación durante su visita al gimnasio, colocarlo como punto de entrada refuerza la propuesta de valor central del producto desde el primer uso y reduce la fricción de navegación.

#### Sprint 2

La configuración del `db.json` con datos semilla completos  es un requisito técnico que desbloquea la mayor parte del backlog de vistas del Sprint 2. Las vistas de autenticación, reservas, mapa de calor y gestión de activos dependen de que esta tarea esté resuelta para funcionar correctamente contra la Fake API. Continuarla en paralelo al desarrollo de vistas genera inconsistencias que producen retrabajo.

Las tareas T15 (Build interactive heatmap component) y T16 (Implement real-time status update via polling) son el núcleo funcional del producto desde la perspectiva del cliente final. El resto de funcionalidades del flujo de cliente —filtrado por tipo de máquina (T17-T18), cambio de sucursal (T19-T20) y motor de rutinas alternativas (T21-T22)— dependen del mapa de calor como superficie de interacción base. Dejarlas para el final del sprint compromete la viabilidad de toda la demo del Sprint Review.

Para que el paso de JSON Server a Spring Boot no implique cambios en los componentes Angular, los endpoints del backend real deben respetar los mismos paths, estructuras de response y códigos de estado ya documentados en la tabla de servicios del Sprint 2. Con ese contrato preservado, la transición se reduce a actualizar la URL base en el `environment.ts` de Angular sin tocar ningún servicio ni componente existente.

## Bibliography

<p style="padding-left: 30px; text-indent: -30px;">DINGG Team. (2025, 26 de noviembre). *Your 5-step operational plan to handle equipment failures*. DINGG. https://dingg.app/blogs/your-5-step-operational-plan-to-handle-equipment-failures</p>

<p style="padding-left: 30px; text-indent: -30px;">Maintainnow. (2025, 19 de octubre). *MRO: Maintenance, repair, & operations - A practical guide*. https://www.maintainnow.app/learn/guides/mro-maintenance-repair-operations-a-practical-guide</p>

<p style="padding-left: 30px; text-indent: -30px;">Energym. (2023). *Why do gym members cancel their memberships?* https://energym.io/blogs/braingains/why-do-gym-members-cancel-their-memberships</p>

<p style="padding-left: 30px; text-indent: -30px;">Oxmaint. (2023). *Corrective vs. preventive work orders*. https://www.oxmaint.com/blog/post/corrective-vs-preventive-work-orders</p>

<p style="padding-left: 30px; text-indent: -30px;">Fitness Store. (2024). *Commercial & professional treadmills*. https://www.topfitness.com/collections/commercial-treadmills</p>


## Annexes

### Annex A : Videos de Exposiciones

| Entrega | Título de la Exposición | Hipervínculo al Video (Microsoft Stream) |
| :--- | :--- | :--- |
| **AV1** | Sprint Review - Semana 4 | [Enlace al video AV1 - SpotTrack](URL_AQUI) |
| **TB1** | Stage Review - Semana 7 | (Pendiente) |
| **AV2** | Sprint Review - Semana 12 | (Pendiente) |
| **TB2** | Release Review - Semana 15 | (Pendiente) |

### Annex B : Video unificado entrevistas
[Enlace al video unificado de entrevistas - SpotTrack](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202413214_upc_edu_pe/IQDpYTdDwbM1QZOtdJPZIbsQASLFAmK8moRkLLD7ZudoVtM?e=unt1Xd&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)



