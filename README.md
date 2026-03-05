 **Proyecto Integral Haasten**

Sistema de gestión integral de componentes, equipos e instalaciones.

Este proyecto centraliza el manejo de stock, producción, logística e instalaciones, integrándose con herramientas ya utilizadas por la operación diaria.

---

** 🧩 Descripción general**

La aplicación permite:

* Gestionar componentes, subconjuntos, kits, placas y equipos.
* Controlar movimientos de stock internos y externos.
* Registrar producción (equipos completos e incompletos).
* Mantener trazabilidad por número de serie.
* Acompañar el flujo real de ventas, instalaciones y servicio técnico.

Está pensada para escalar e integrar múltiples áreas de la empresa sin perder historial ni consistencia de datos.

---

 **👥 Roles del sistema**

* **Administración**: gestión de componentes, estructuras, stock y configuraciones globales.
* **Producción**: armado de placas y equipos, checklist de componentes, registro de defectuosos.
* **Logística**: preparación, embalaje y despacho de equipos y kits.
* **Coordinación**: asignación de instalaciones y seguimiento operativo.
* **Instaladores / Técnicos**: uso de stock asignado, registro de tareas, horas y kilómetros.
* **Gerencial**: acceso completo a todos los módulos.

---

 **🔌 Integraciones externas**

 Airtable

Airtable es una herramienta **actualmente utilizada en la operación real** por el área de **Coordinación de Instalaciones**.

* Cada instalación registrada genera un **número de serie** para el equipo.
* El sistema sincroniza esta información para mantener consistencia entre la herramienta operativa existente y la aplicación.
* La integración evita duplicación de datos y permite una trazabilidad unificada de los equipos instalados.

Airtable funciona como parte del flujo operativo y no como un entorno de prueba.

---

 **🔄 Flujo general del sistema**

1. Coordinación registra una venta / instalación.
2. Se asigna número de serie al equipo.
3. Producción fabrica el equipo (completo o incompleto).
4. Logística embala y despacha.
5. Instalación o servicio técnico ejecuta la tarea.
6. El sistema registra movimientos, stock y trazabilidad histórica.

---

 **🛠️ Tecnologías**

* Backend: Java + Spring Boot
* Base de datos: Relacional
* Control de versiones: Git / GitHub
* Contenedores: Docker
* Diseño UI/UX: Figma

---

 **🌱 Ramas del repositorio**

* `main`: rama estable.
* `dev-*`: ramas de desarrollo por persona o feature.

Se recomienda mantener los cambios aislados en ramas de desarrollo y realizar merge a `main` una vez validados.

---

** 🚀 Estado del proyecto**

Proyecto en desarrollo activo, con foco en:

* Robustez del flujo real
* Escalabilidad
* Claridad de roles y permisos

---

** 📌 Notas**

Este README describe el comportamiento funcional del sistema. Los detalles técnicos de implementación se documentan en la capa correspondiente (código, configuración o documentación técnica específica).
