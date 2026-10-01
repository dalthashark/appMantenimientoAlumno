# ☕ appMantenimientoAlumno

### 🚀 Sistema Core de Gestión Académica (CRUD) con Java y Base de Datos Relacional

Este proyecto es una aplicación de escritorio diseñada para automatizar y optimizar el control de registros estudiantiles. Implementa un sistema completo de **CRUD** (Crear, Leer, Actualizar, Eliminar) interactuando directamente con un motor de bases de datos relacionales. Demuestra la aplicación práctica de la arquitectura de software y los patrones de diseño orientados a objetos.

*Desarrollado como proyecto práctico de clase dentro de mi formación técnica en la carrera de Ingeniería de Software con IA en SENATI.*

---

## 🎯 Problema de Negocio Solucionado
La gestión manual de información académica en instituciones educativas suele generar duplicidad de datos, pérdida de registros y lentitud en los procesos administrativos. **appMantenimientoAlumno** resuelve este problema centralizando la información en una base de datos segura, garantizando la integridad de los datos de los estudiantes y reduciendo el tiempo de respuesta en consultas operativas.

## 📋 Características Principales del Sistema
* **CRUD Completo de Alumnos:** Registro de nuevos estudiantes, actualización de perfiles académicos, consultas avanzadas mediante filtros y eliminación lógica de registros.
* **Persistencia de Datos Eficiente:** Conexión y mapeo de datos estructurados directamente hacia un servidor relacional.
* **Control de Reglas de Negocio:** Validación estricta de campos obligatorios, formatos de correo electrónico, documentos de identidad y estados de matrícula.
* **Patrón de Arquitectura Limpia:** Separación clara entre la interfaz de usuario, los controladores lógicos y la capa de acceso a datos (DAO).

## 🛠️ Stack Tecnológico Utilizado
* **Lenguaje de Programación:** Java (Core / Programación Orientada a Objetos) ☕
* **Entorno de Desarrollo Local:** Laragon 🐘 (Gestión integrada de servidores y MySQL)
* **Motor de Base de Datos:** MySQL / SQL Relacional 🐬
* **Control de Versiones:** Git & GitHub

## ⚙️ Arquitectura & Buenas Prácticas de Ingeniería
El desarrollo de este sistema sigue las directrices técnicas y metodológicas del plan de estudios de SENATI:
* **Encapsulamiento y Abstracción:** Uso riguroso de clases, interfaces y modificadores de acceso para proteger el flujo de datos.
* **Manejo de Excepciones:** Bloques `try-catch` robustos para prevenir caídas del sistema ante fallos de conexión o ingreso de datos erróneos.
