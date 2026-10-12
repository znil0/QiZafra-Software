---
title: A04.2 Requisitos No Funcionales
---


# Requisitos No Funcionales

## I. Rendimiento
Requisitos para fijar el rendimiento que se considera aceptable.

| ID | Requisito |
|:---|:---|
| `RNF-01` | El sistema debe responder a consultas comunes en menos de 3 segundos con hasta 10,000 registros por módulo. |
| `RNF-02` | La renderización de mapas y polígonos de las parcelas no debe sobrepasar los 4 segundos en conexiones móviles promedio (4G/5G). |
| `RNF-03` | Debe soportar al menos 30 usuarios concurrentes sin degradación significativa. |
| `RNF-04` | La generación de reportes complejos no debe exceder 10 segundos. |


## II. Disponibilidad y Confiabilidad
Establecer reglas de seguridad y confiabilidad para evitar pérdidas, fallos o problemas en el negocio relacionados con la aplicación.

| ID | Requisito |
|:---|:---|
| `RNF-05` | Disponibilidad mínima del 99% en horario laboral (6:00–20:00). |
| `RNF-06` | Respaldos automáticos diarios con retención mínima de 30 días. |
| `RNF-07` | Recuperación ante fallos en menos de 4 horas (RTO) y pérdida máxima de 1 hora de datos (RPO). |


## III. Seguridad
Establecer mecanismos para brindar capas de seguridad al sistema.

| ID | Requisito |
|:---|:---|
| `RNF-08` | Contraseñas cifradas y política de complejidad. |
| `RNF-09` | Control de acceso basado en roles (RBAC). |
| `RNF-10` | Registro de auditoría inalterable para operaciones sensibles. |
| `RNF-11` | Comunicación cifrada mediante HTTPS/TLS. |


## IV. Usabilidad
Facilitar el uso del sistema implementando interfaces, lenguajes y entornos amigables con el usuario.

| ID | Requisito |
|:---|:---|
| `RNF-12` | Interfaz en español, con lenguaje adaptado al sector cañero. |
| `RNF-13` | Diseño responsivo para uso en computadora y teléfono en campo. |
| `RNF-14` | Curva de aprendizaje mínima: un usuario nuevo debe poder registrar una labor básica en menos de 15 minutos con capacitación breve. |
| `RNF-15` | Mensajes de error claros y en español, con sugerencias de solución. |
| `RNF-16` | Compatible con Android 9+ e iOS 13+. |


## V. Mantenibilidad y Escalabilidad
Permitir el desarrollo posterior del sistema en caso de ser necesario.

| ID | Requisito |
|:---|:---|
| `RNF-17` | Arquitectura modular que permita agregar nuevos módulos sin reescribir el sistema. |
| `RNF-18` | Código documentado y con pruebas automatizadas. |
| `RNF-19` | Escalabilidad horizontal para crecer en número de parcelas, usuarios y ciclos. |
| `RNF-20` | Registro de logs del sistema para diagnóstico de errores. |
