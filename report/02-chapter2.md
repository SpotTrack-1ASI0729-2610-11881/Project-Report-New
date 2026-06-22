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

### Entrevista 1: Julio Cardenas

| Campo | Detalle |
| :--- | :--- |
| **Entrevistado** | Julio Cardenas |
| **Imagen** | ![EntrevistaJulio](../assets/Interview-iniciaI.png){width=80%} |
| **Edad** | 45 |
| **Ocupación** | Administrador de Gimnasio |
| **Link** | [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410344_upc_edu_pe/IQDZ7_STc-2lQ79wKz-WoFdQAQQcErVhHwv0uZMYZBpl_r8?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=UxgRBS](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202410344_upc_edu_pe/IQDZ7_STc-2lQ79wKz-WoFdQAQQcErVhHwv0uZMYZBpl_r8?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=UxgRBS) |
| **Resumen** | La entrevista presenta a Julio Cardenas, Administrador de gimnasio en B2 de sede Pardo, quien comenta que el mantenimiento actual es rápido, salvo cuando requieren repuestos importados. Reconoce que gestionan la congestión en horas pico ofreciendo ejercicios alternativos o pesos libres a los clientes. Señala que un mapa de calor le ayudaría a prever la demanda específica de ciertos días, y que las alertas automáticas de mantenimiento predictivo serían magníficas para anticipar el desgaste de piezas clave (como las fajas de las trotadoras) antes de que se rompan. En cuanto al panel de control, Julio valora métricas sobre asignación de rutinas, ingreso de invitados y comentarios de post-venta. Considera que la tecnología de cámaras podría generar reservas en adultos mayores, aunque sería bien aceptada por los jóvenes. Finalmente, destaca que un piloto gratuito lo convencería de pagar la suscripción si en 30 días arroja datos precisos sobre los horarios pico y el uso de máquinas de alta demanda, justificando así futuras compras y optimizando la gestión del local. | 


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
| 1 | 00:00:00 | Julio Cardenas |
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

* Rango Etario y Perfil Profesional (100%): El 100% de los entrevistados (Julio, Luis y Percy) son hombres que se desempeñan como administradores de gimnasios. Sus edades fluctúan entre los 30 y 51 años (Julio con 45, Luis con 51 y Percy con 30), representando un segmento con experiencia directa en la gestión operativa de instalaciones deportivas.  
* Gestión Operativa de la Congestión (100%): El 100% del segmento implementa estrategias manuales de mitigación durante las horas pico. Para manejar la saturación, recurren a ofrecer ejercicios alternativos, promover el uso de pesos libres, fomentar que se compartan las máquinas o realizar "gestión de piso".  
* Dependencia de Mantenimiento y Repuestos (100%): El 100% lidia con la logística y los tiempos del mantenimiento de equipos. Un 66.7% (Julio y Luis) diferencia operativamente entre la rapidez de obtener repuestos de marcas nacionales frente a las demoras logísticas que implican los repuestos importados, especialmente en máquinas de cardio como las trotadoras.  
* Apertura a la Implementación Tecnológica (100%): El 100% de los entrevistados está dispuesto a integrar tecnologías como mapas de calor, paneles de control y sensores/cámaras para medir el uso real del local. Asimismo, un 66.7% (Luis y Percy) enfatiza el uso de procesamiento "Edge" en las cámaras como condición operativa para asegurar la supervisión sin vulnerar la privacidad de los usuarios.  
* Condicionamiento para la Adopción de Software (100%): El 100% coincide en que la decisión de pagar por una nueva plataforma tecnológica depende de un piloto gratuito (por ejemplo, de 30 días). Exigen que este piloto demuestre datos precisos sobre afluencia, horarios pico y uso de máquinas (o logre una reducción medible de quejas) para justificar la inversión comercial.  
  
2. **Características Subjetivas (Pain Points, Emociones y Percepciones)**

* Frustración y Preocupación por Fuga de Clientes (100%): El 100% reconoce que las fallas en los equipos generan cuellos de botella y quejas inmediatas. Un 66.7% (Luis y Percy) señala con preocupación que estas fallas afectan negativamente la percepción del cliente y son un factor crítico que impacta directamente en la no renovación de las membresías.  
* Urgencia por Anticipación y Control (100%): El 100% valora profundamente el concepto de "mantenimiento predictivo". Perciben que poder anticipar el desgaste de piezas clave antes de que se rompan "cambiaría las reglas del juego" o sería "magnífico", ya que su principal dolor es el tiempo de inactividad de las máquinas (downtime) y el alto costo del mantenimiento correctivo.  
* Necesidad de Certeza frente a la Subjetividad (66.7%): Para el 66.7% (Julio y Percy), existe el deseo de dejar atrás la intuición para pasar a los datos reales. Sienten la necesidad de contar con mapas de calor para prever demandas, optimizar el mix de máquinas y redistribuir al staff de manera fundamentada, sin depender de percepciones subjetivas.  
* Empatía Tecnológica con el Socio (66.7%): Un 66.7% (Julio y Percy) proyecta que las herramientas visuales beneficiarían emocionalmente al usuario final. Consideran valioso que el socio pueda visualizar la disponibilidad del local o reservar espacios a través de una app, ayudando a que el cliente entienda la capacidad del lugar y gestione mejor sus expectativas.  
  
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

![Event storming Big Picture.png](../assets/BigPicture-EventStorming.png)

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

