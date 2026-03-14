# Registro de Trabajo en Clase - Taller 5

## Fecha de la sesión
14 de Marzo de 2026

## Integrantes
- Juan David González  
- Julián Barragán  
- Josué Sarmiento  

---

# Actividades realizadas en clase

Durante la sesión se analizó el caso base EdukIT, una plataforma de educación virtual utilizada para la gestión de cursos, contenidos académicos, evaluaciones y pagos por suscripción.

El objetivo del trabajo fue aplicar el modelo de análisis de amenazas STRIDE para identificar posibles riesgos de seguridad dentro de uno de los procesos críticos del sistema.

El equipo inició la actividad revisando el funcionamiento general de la plataforma EdukIT y los distintos actores involucrados en el sistema:

- Estudiantes
- Docentes
- Administradores

A partir de este análisis se identificaron los procesos sensibles del sistema, tales como:

- Acceso de estudiantes a cursos y materiales
- Publicación de contenidos por parte de docentes
- Procesamiento de pagos
- Almacenamiento de datos personales y notas académicas

Luego de discutir las opciones, el equipo decidió analizar el flujo crítico acceso de estudiantes a cursos y materiales, debido a que este proceso involucra autenticación de usuarios, control de acceso y manejo de información académica.

Posteriormente se aplicó el marco STRIDE para identificar amenazas en seis categorías principales:

- Spoofing (Suplantación de identidad)
- Tampering (Manipulación de datos)
- Repudiation (Repudio de acciones)
- Information Disclosure (Divulgación de información)
- Denial of Service (Denegación de servicio)
- Elevation of Privilege (Escalada de privilegios)

Para cada una de estas categorías se analizaron posibles vulnerabilidades del sistema, los escenarios de ataque que podrían presentarse, el impacto que tendrían sobre la plataforma y las estrategias de mitigación recomendadas.

Entre las principales amenazas identificadas se encuentran:

- Suplantación de identidad mediante credenciales robadas.
- Manipulación de registros académicos en la base de datos.
- Filtración de información personal de los estudiantes.
- Ataques de denegación de servicio que afecten la disponibilidad de la plataforma.
- Escalada de privilegios que permita a un estudiante obtener permisos administrativos.

Durante la clase se construyó una tabla de análisis STRIDE donde se documentaron las amenazas identificadas, el nivel de riesgo asociado y los controles de seguridad existentes o recomendados.

Esta tabla permite visualizar de forma estructurada los riesgos de seguridad del sistema y facilita la definición de medidas de protección para mejorar la seguridad de la plataforma EdukIT.

El análisis de la Parte 1 del taller fue desarrollado por Juan David González y Julián Barragán, quienes se encargaron de identificar el flujo crítico del sistema y aplicar el modelo STRIDE para el análisis de amenazas.

---

# Boceto inicial del modelo

El boceto inicial corresponde a la tabla de análisis STRIDE desarrollada durante la sesión de clase, donde se registraron las amenazas identificadas para el flujo de acceso de estudiantes a los cursos.

La tabla incluye las categorías STRIDE, la descripción de las amenazas, los posibles escenarios de ataque, el impacto sobre el sistema, la probabilidad de ocurrencia y las medidas de mitigación recomendadas.

Este análisis permitió identificar riesgos de seguridad relevantes dentro de la arquitectura de la plataforma EdukIT.

---

# Tareas definidas para complementar el taller

| Tarea asignada | Responsable | Fecha estimada |
|---|---|---|
| Aplicación del modelo STRIDE al caso base EdukIT | Juan David González, Julián Barragán | Realizado en clase |
| Documentación del análisis de amenazas | Juan David González, Julián Barragán | Realizado en clase |
| Desarrollo de la Parte 2 del taller (análisis del cliente real) | Josué Sarmiento | Antes de la entrega |

---

Este documento resume el trabajo colaborativo realizado durante la sesión del **Taller 5 – Evaluación de Seguridad con STRIDE** en el curso de **Arquitectura Empresarial de la Universidad de La Sabana**.
