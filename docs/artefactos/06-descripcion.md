---
title: A06 Descripción
---

A continuación se presenta un bosquejo de la descripción de nuestro proyecto. En esta actividad se prioriza la exactitud por encima de la concisión, por lo que se intenta describir el software de la manera más exhaustiva que en la presentada en el Charter.

# Descripción del Proyecto Propuesto Actual

El sistema de gestión QiZafra permite al usuario mantener un control sobre los diferentes procesos que componen la siembra y cosecha de caña. Particularmente, sus funciones cubren las siguientes áreas:

- **Gestión de recursos:** semillas, herramientas, fertilizantes, insecticidas y otros.
- **Administración de personal:** sueldos y asignación de labores.
- **Monitoreo del riego:** registro y consulta de horarios.
- **Estadísticas:** Cálculo del progreso actual según hectáreas, madurez de los cultivos según fechas de plantación.
- **Proyecciones:** ingresos esperados, gráficos de rendimiento y otras informaciones de índole financiera.
- **Bitácora digital:** registros para garantizar la integridad y la accesibilidad de la información dentro del negocio.
- **Seguimiento de liquidaciones:** control de pagos por parte del molino.

Se desea que el sistema sea accesible mediante teléfono móvil y computadora sin necesidad de internet 24/7, dado que su uso será principalmente en el campo en el caso de los trabajadores, y en la oficina, para el dueño.

Al ejecutar el software, el sistema muestra una pantalla de acceso donde se proporcionarán las credenciales necesarias para ingresar, siendo éstas el usuario y contraseña. A primera instancia, no hay pantalla de registro, dado que el dueño es quien se encarga de registrar y dar de alta a los usuarios del sistema a través de una pantalla especializada dentro de la sección Personal, mencionada más adelante.

Una vez se accede, el sistema presenta en su pantalla principal un resumen generalizado del estado del proceso, incluyendo principalmente:
- Un calendario de actividades donde se resalten eventos como el riego, la cosecha, quema, y otros.
- Estadísticas breves respecto al progreso y fase en la que se encuentra, proporcionando información sobre la cantidad de hectáreas faltantes por regar, por cosechar, o por preparar.
- Anotaciones y advertencias respecto a puntos del proceso que requieren atención, como por ejemplo, baja cantidad de material, necesidad de mantenimiento de herramientas, o incidencias en general.

En el menú de módulos, localizado en una barra inferior o en una barra lateral dependiendo del dispositivo en el cual que se acceda, se pueden seleccionar las siguientes pantallas.
1. **Inicio:** la pantalla principal mencionada con anterioridad, misma que solo contiene información referente al progreso actual.
2. **Inventario:** una sección con los materiales y herramientas desglosados en un listado y que permite gestionar las existencias de los mismos. 
	- De manera global, cuenta con funciones que permiten realizar la búsqueda de materiales individuales y organización según diferentes criterios, como la especialidad del trabajador.
	- Aquí los trabajadores pueden consultar información y actualizar cantidades respecto a su uso en el desempeño de sus labores, como por ejemplo, en el uso del insecticida o fertilizante.
	- Mientras que el dueño puede registrar la compra de materiales, mantenimiento de herramientas, y gestionar de manera general las existencias dentro del negocio. Esta sección también permite llevar un control respecto al costo de las compras, mismas que se consideran como egresos.
3. **Personal:** una sección especializada en la administración de personal, donde se incluye la información de los trabajadores. Muestra la información en un listado y permite realizar búsquedas individuales según diferentes criterios, como especialidad, disponibilidad, nombre, entre otros.
	- Esta sección le permite al dueño dar de alta o baja a personal mediante un menú, almacenar información y documentos, y proporcionar acceso como Trabajador o Dueño a aquellos que lo requieran.
4. **Bitácora:** una sección que permite registrar labores, agregar registros y anotaciones de manera similar a una bitácora escrita. Las opciones mostradas dependen del rol que posea el usuario.
	- En esta sección, el dueño puede actualizar las actividades planeadas para el día y asignar labores a los diferentes trabajadores.
	- Por otra parte, los trabajadores pueden registrar el resultado de sus labores y realizar anotaciones generales.
5. **Métricas:** otra sección especializada en información recopilada sobre el proceso, mostrando estadísticas y proyecciones sobre el rendimiento, cantidad esperada de tonelaje, KARBE, KATC, y más parámetros relevantes.
6. **Cuenta:** Registro de ingresos y egresos de la empresa, incluyendo aquí un seguimiento de las liquidaciones del molino.
	- Aquí el dueño podrá consultar un desglose de los movimientos ordenados por fecha y descripción en un formato de lista, y también podrá capturar información relacionada; como las liquidaciones del molino, ingresos y gastos adicionales que no se hayan considerado en las secciones.
	- Además, también estarán disponibles gráficos respecto al rendimiento y el porcentaje de ganancia.

En el caso de los trabajadores, algunas secciones estarán limitadas solamente para el dueño, como en el caso de las secciones de Cuenta, Personal y Métricas.