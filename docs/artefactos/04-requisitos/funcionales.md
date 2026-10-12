---
title: A04.1 Requisitos Funcionales
---


# Requisitos Funcionales

## I. Gestión de Recursos
El módulo del proyecto que se encarga de mantener un inventario del material.

| ID | Requisito |
|:---|:---|
| `RF-01` | Registrar entradas y salidas de insumos con fecha, cantidad, unidad de medida, proveedor y responsable. |
| `RF-02` | Controlar inventario mínimo por insumo y generar alertas cuando el stock baje del umbral definido. |
| `RF-03` | Asociar cada insumo aplicado a una parcela, lote o ciclo de cultivo específico (trazabilidad). |
| `RF-04` | Registrar costos unitarios y calcular el costo total por hectárea de los insumos utilizados. |
| `RF-05` | Gestionar proveedores: datos de contacto, historial de compras, precios y tiempos de entrega. |
| `RF-06` | Controlar el mantenimiento y la vida útil de herramientas y maquinaria (fechas de servicio, reparaciones). |
| `RF-07` | Manejar fechas de caducidad de fertilizantes, insecticidas y semillas, con alertas previas. |
| `RF-08` | Registrar dosis y método de aplicación de agroquímicos por parcela (para cumplimiento normativo). |


## II. Administración de Personal
El módulo del proyecto que registra, administra y coordina al personal del negocio familiar.

| ID | Requisito |
|:---|:---|
| `RF-09` | Registrar datos personales, documentos, puesto y tipo de contratación de cada trabajador. |
| `RF-10` | Calcular nómina considerando sueldos base, horas extra, bonos, deducciones y prestaciones. |
| `RF-11` | Registrar asistencia por día, turno y labor (puede integrarse con checador o captura manual). |
| `RF-12` | Asignar labores por trabajador, parcela, fecha y tipo de actividad (siembra, riego, corte, etc.). |
| `RF-13` | Generar reportes de productividad por trabajador o cuadrilla. |
| `RF-14` | Gestionar vacaciones, permisos, incapacidades y ausencias justificadas. |
| `RF-15` | Controlar seguridad social y vigencias de contratos. |
| `RF-16` | Historial laboral por trabajador (labores realizadas, pagos, evaluaciones). |


## III. Herramientas Auxiliares
Los módulos que se especializan en partes concretas del ciclo de siembra y cosecha de la caña. Particularmente, solo se contempla el proceso de riego, el cual cubre los horarios y la coordinación del mismo.

| ID | Requisito |
|:---|:---|
| `RF-17` | Programar horarios y turnos de riego por parcela, considerando clima y tipo de suelo. |
| `RF-18` | Notificar al personal responsable antes de cada turno de riego. |
| `RF-19` | Registrar incidencias (fallas de bomba, fugas, cortes de energía) y su resolución. |
| `RF-20` | Consultar histórico de riegos por parcela, fecha y responsable. |


## IV. Estadísticas y Proyecciones
El módulo encargado de generar gráficos, analizar rendimientos, y producir reportes acerca de la información recabada de la empresa.

| ID | Requisito |
|:---|:---|
| `RF-17` | Programar horarios y turnos de riego por parcela, considerando clima y tipo de suelo. |
| `RF-21` | Calcular avance de siembra, crecimiento y cosecha en hectáreas y porcentaje por lote. |
| `RF-22` | Estimar madurez del cultivo a partir de fecha de plantación, variedad y condiciones climáticas. |
| `RF-23` | Proyectar rendimiento (toneladas por hectárea) e ingresos esperados por ciclo. |
| `RF-24` | Generar gráficos comparativos entre ciclos, parcelas y variedades. |
| `RF-25` | Calcular indicadores clave: costo por tonelada, margen por hectárea, eficiencia de riego, rendimiento por trabajador. |
| `RF-26` | Exportar reportes a PDF y Excel, y permitir filtros por fecha, parcela, ciclo o variedad. |
| `RF-27` | Comparar producción real vs. proyectada y explicar desviaciones. |


## V. Registros Digitales
El módulo encargado de generar gráficos, analizar rendimientos, y producir reportes acerca de la información recabada de la empresa.

| ID | Requisito |
|:---|:---|
| `RF-28` | Almacenar documentos digitales (facturas, contratos, certificados, análisis de suelo, etc.) asociados a entidades del sistema. |
| `RF-29` | Versionar documentos y registrar quién los modificó y cuándo. |
| `RF-30` | Búsqueda avanzada por texto, fecha, tipo de documento o entidad relacionada. |
| `RF-31` | Respaldo automático y recuperación de información. |
| `RF-32` | Control de acceso por rol para consulta y edición de registros. |


## VI. Seguimiento de Liquidaciones
El módulo que mantiene un seguimiento de las liquidaciones y permite tener un control respecto a los ingresos directos del negocio.

| ID | Requisito |
|:---|:---|
| `RF-33` | Registrar cada liquidación recibida: folio, fecha, peso, calidad (KATC, sacarosa, humedad, impurezas). |
| `RF-34` | Comparar peso/calidad entregado por el rancho vs. lo reportado por el molino. |
| `RF-35` | Calcular ingresos netos por liquidación aplicando precios, cuotas y retenciones. |
| `RF-36` | Detectar y registrar diferencias o inconformidades con el molino, con seguimiento de su resolución. |
| `RF-37` | Historial de liquidaciones por ciclo, parcela y tipo de caña. |


## VII. Funciones Generales
Funcionalidades que son fundamentales para el programa, sin tener relación con algún módulo o área en particular.

| ID | Requisito |
|:---|:---|
| `RF-38` | Autenticación de usuarios con roles diferenciados (administrador, capataz, contador, consulta). |
| `RF-39` | Panel de inicio con indicadores resumidos y alertas pendientes. |
| `RF-40` | Gestión de catálogos: parcelas, lotes, variedades de caña, tipos de labor, unidades de medida. |
| `RF-41` | Notificaciones internas y por correo/WhatsApp para eventos críticos. |
| `RF-42` | Modo offline o sincronización diferida para zonas sin cobertura en campo. |
