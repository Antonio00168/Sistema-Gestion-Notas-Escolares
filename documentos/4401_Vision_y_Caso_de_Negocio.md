Visión y Caso de Negocio
Sistema de Gestión de Notas Escolares

1. Visión
Introducción
En las instituciones educativas, la gestión de información académica representa una actividad fundamental para el seguimiento del desempeño de los estudiantes. El registro de calificaciones, la administración de materias y el cálculo de promedios son procesos que requieren precisión, organización y disponibilidad de la información.

En muchos casos, estas actividades se realizan mediante documentos físicos, hojas de cálculo o procedimientos manuales que pueden provocar errores, pérdida de información y retrasos en la consulta de resultados académicos. Esta situación dificulta el trabajo de los docentes y limita el acceso oportuno a la información por parte de estudiantes y personal administrativo.

Ante esta necesidad surge el proyecto denominado Sistema de Gestión de Notas Escolares, una solución informática orientada a centralizar y administrar la información académica de manera eficiente.

Visión del Producto
El Sistema de Gestión de Notas Escolares será una aplicación que permita registrar, almacenar, consultar y administrar información relacionada con estudiantes, materias y calificaciones dentro de una institución educativa.

La finalidad principal del sistema es proporcionar una herramienta confiable y fácil de utilizar que simplifique el control académico, reduzca errores en el manejo de datos y facilite la consulta de información relevante para el seguimiento del rendimiento escolar.

El sistema permitirá a los usuarios gestionar de manera organizada los registros académicos, manteniendo la información actualizada y disponible cuando sea requerida.

Usuarios Objetivo
Los principales usuarios del sistema serán:

Docentes encargados del registro y actualización de calificaciones.
Personal administrativo responsable de la gestión académica.
Instituciones educativas interesadas en mejorar el control de información escolar.
Estudiantes que requieran consultar su desempeño académico.
Necesidades que Cubrirá el Sistema
El proyecto busca satisfacer las siguientes necesidades:

Mantener un registro organizado de estudiantes.
Gestionar las materias impartidas dentro de la institución.
Registrar calificaciones de manera rápida y segura.
Consultar la información académica cuando sea necesaria.
Calcular automáticamente los promedios de los estudiantes.
Reducir errores asociados con procesos manuales.
Mejorar la disponibilidad y confiabilidad de los datos académicos.
Visión a Futuro
Se espera que el sistema sirva como base para futuras mejoras, incorporando funcionalidades adicionales como reportes académicos, generación de historiales escolares, control de asistencia y acceso web para estudiantes y docentes.

De esta manera, el proyecto podrá evolucionar hasta convertirse en una plataforma integral de gestión académica.

2. Caso de Negocio
Situación Actual
Actualmente, muchas actividades relacionadas con el control de calificaciones se realizan mediante procedimientos manuales o herramientas que no se encuentran integradas entre sí. Esta situación genera problemas como:

Duplicidad de información.
Errores en el registro de calificaciones.
Dificultad para consultar información histórica.
Mayor tiempo para realizar cálculos de promedios.
Riesgo de pérdida de información académica.
Estas limitaciones afectan tanto a docentes como a estudiantes y personal administrativo.

Oportunidad de Negocio
La digitalización de los procesos académicos representa una oportunidad para mejorar significativamente la gestión de la información escolar.

Un sistema centralizado permitirá que las actividades relacionadas con estudiantes, materias y calificaciones se realicen de forma rápida, organizada y confiable.

La implementación de una herramienta tecnológica reducirá las tareas repetitivas y permitirá destinar más tiempo a actividades académicas de mayor valor.

Problema a Resolver
La ausencia de un sistema especializado para la administración de notas escolares dificulta el control eficiente de la información académica, provocando posibles errores en los registros y retrasos en la obtención de resultados.

El problema principal radica en la falta de centralización de los datos y en la dependencia de procesos manuales para la gestión de la información.

Solución Propuesta
Se propone desarrollar el Sistema de Gestión de Notas Escolares, una aplicación que permita registrar estudiantes, administrar materias, capturar calificaciones y calcular automáticamente los promedios obtenidos por cada alumno.

La solución proporcionará una base de datos organizada y herramientas de consulta que facilitarán el acceso a la información académica de manera rápida y segura.

Beneficios Esperados
La implementación del sistema proporcionará los siguientes beneficios:

Beneficios Operativos
Reducción del tiempo empleado en registrar calificaciones.
Automatización del cálculo de promedios.
Organización centralizada de la información académica.
Disminución de errores humanos.
Beneficios para los Docentes
Mayor facilidad para registrar información.
Consulta rápida del desempeño de los estudiantes.
Mejor control de grupos y materias.
Beneficios para los Estudiantes
Acceso más rápido a sus resultados académicos.
Mayor transparencia en los registros de evaluación.
Seguimiento más claro de su desempeño escolar.
Beneficios para la Institución
Mejor administración de la información académica.
Mayor confiabilidad en los registros escolares.
Disponibilidad de información para la toma de decisiones.

Justificación
El Sistema de Gestión de Notas Escolares constituye una solución viable para modernizar el manejo de información académica dentro de una institución educativa.

La automatización de procesos permitirá incrementar la eficiencia operativa, mejorar la calidad de los registros y brindar un servicio más confiable a docentes y estudiantes.

Debido a los beneficios obtenidos en términos de organización, precisión y disponibilidad de información, la implementación de este proyecto representa una inversión tecnológica con impacto positivo en la gestión educativa.
El caso de uso sigue el formato completamente vestido propuesto por Alistair Cockburn, donde cada sección (alcance, nivel, actor principal, stakeholders, precondiciones, escenario principal y extensiones) se 8documenta con precisión. Este formato permite capturar tanto los requerimientos funcionales como los no funcionales, y facilita la trazabilidad entre los artefactos del Unified Process (UP): modelo de negocio, requisitos y diseño. 
2.	Perspectiva del contenido 
La perspectiva es actor-sistema, centrada en el Cajero como actor principal que interactúa con el sistema POS para cumplir el 2objetivo del Cliente. El caso de uso se ubica en el nivel objetivo del usuario, pues describe un proceso completo de negocio elemental (EBP). El modelo de casos de uso dentro del UP actúa como contrato entre las partes interesadas, garantizando que los intereses del cliente, la empresa y los sistemas externos estén satisfechos. 
3.	Observaciones importantes 
•	El caso UC1 es arquitectónicamente significativo, base para otros casos como Handle Payment o Manage Inventory. 
•	La estructura numerada (1–10) del flujo principal y la notación de extensiones (3a, 3b, *a, *b) permiten una lectura clara y sistemática. 
•	Los flujos alternos representan excepciones y variaciones del proceso principal, esenciales para la robustez del sistema. 
•	Los requerimientos especiales (por ejemplo, interfaz táctil, tiempo de respuesta, internacionalización) se registran junto al caso de uso, siguiendo las recomendaciones del UP. 
4.	Notación de flujos alternos 
Según la lectura, las extensiones se numeran respecto al paso del flujo principal: 
•	3a, 3b, 3c… indican variaciones específicas del paso 3. 
•	\a, \b…** indican condiciones que pueden ocurrir en cualquier momento del escenario. 
Cada extensión tiene dos partes: Condición y Manejo. Ejemplo del flujo alterno A1 (producto inexistente): 
Conclusión 
 
• 	El caso de uso UC1: Process Sale ejemplifica la aplicación del Unified Process para conectar los niveles de negocio, requisitos y diseño. Su formato estructurado, perspectiva centrada en el actor y notación clara de flujos alternos lo convierten en un modelo ideal para documentar requerimientos funcionales y garantizar la trazabilidad del sistema. 


Casos de Uso
Los casos de uso representan las funcionalidades que el sistema ofrecerá a los usuarios.

Para este proyecto, algunos casos de uso identificados son:

CU01. Registrar Estudiante
Permite almacenar la información de un nuevo estudiante dentro del sistema.

CU02. Registrar Materia
Permite crear y administrar las materias disponibles.

CU03. Registrar Calificación
Permite capturar las notas obtenidas por un estudiante en una materia específica.

CU04. Consultar Calificaciones
Permite visualizar las calificaciones registradas.

CU05. Consultar Promedio
Permite calcular y mostrar automáticamente el promedio de un estudiante.

Los casos de uso facilitan la comprensión de las necesidades del sistema desde la perspectiva de los usuarios finales.

Requerimiento Evolutivo
El proyecto se considera evolutivo debido a que puede ampliarse conforme surjan nuevas necesidades dentro de la institución educativa.

Entre las posibles evoluciones futuras se encuentran:

Control de asistencia.
Generación de reportes académicos.
Historial escolar.
Sistema de usuarios y roles.
Portal web para estudiantes.
Emisión de constancias académicas.
Notificaciones automáticas de desempeño.
Esta característica permite que el sistema continúe creciendo sin necesidad de ser reemplazado completamente.

Gestión del Cambio
Durante el desarrollo pueden surgir modificaciones en los requisitos inicialmente definidos.

Por ejemplo:

Nuevas reglas para el cálculo de promedios.
Inclusión de semestres o grupos.
Nuevos formatos de reportes.
Requisitos de seguridad adicionales.
La gestión del cambio permitirá analizar, documentar e incorporar estas modificaciones de manera controlada, evitando afectar la estabilidad del sistema.

Agile Unified Process (AUP)
El proyecto puede desarrollarse aplicando conceptos de Agile Unified Process, adoptando iteraciones cortas para construir funcionalidades progresivamente.

Cada iteración podrá incluir:

Diseño de funcionalidades.
Implementación.
Pruebas.
Retroalimentación.
Esto permitirá obtener resultados visibles desde etapas tempranas y mejorar continuamente el producto.

Unified Process (UP)
El Sistema de Gestión de Notas Escolares sigue los principios fundamentales del Unified Process:

Desarrollo dirigido por casos de uso.
Desarrollo iterativo e incremental.
Gestión de riesgos.
Enfoque centrado en la arquitectura.
Gracias a este enfoque, el proyecto podrá evolucionar de forma organizada, asegurando la calidad del software y la correcta satisfacción de las necesidades académicas de la institución.

Debido a los beneficios obtenidos en términos de organización, precisión y disponibilidad de información, la implementación de este proyecto representa una inversión tecnológica con impacto positivo en la gestión educativa.
