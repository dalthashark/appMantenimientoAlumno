# appMantenimientoAlumno - Gestión Académica ☕

Aplicación de escritorio diseñada para automatizar y optimizar el control de registros estudiantiles mediante un sistema completo de persistencia de datos relacional. Desarrollado como proyecto práctico de clase dentro de mi formación técnica en la carrera de Ingeniería de Software con IA en SENATI.

## 📌 Características Principales

* 🗂️ **Gestión Completa (CRUD):** Creación, lectura, actualización y eliminación lógica de registros de estudiantes.
* 🐬 **Persistencia Eficiente:** Conexión directa y mapeo de datos estructurados hacia un servidor relacional local.
* 🛑 **Validación de Negocio:** Control estricta de campos obligatorios, formatos de correo, documentos y estados de matrícula.
* 🛡️ **UX Defensiva:** Manejo robusto de excepciones (try-catch) para evitar caídas del sistema ante fallos de conexión.

## 🏗️ Arquitectura del Proyecto

El código fuente está estructurado mediante el patrón de arquitectura limpia para asegurar la separación de responsabilidades:

* 📁 **views:** Interfaces de usuario y componentes gráficos para el mantenimiento.
* 📁 **controllers:** Controladores lógicos que gestionan los eventos y el flujo de la aplicación.
* 📁 **dao:** Clases de acceso a datos que manejan las sentencias SQL y la comunicación con el servidor.
* 📁 **models:** Entidades de datos del sistema que representan la estructura del Alumno.

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Java (Core / POO)
* **Entorno de Desarrollo Local:** Laragon 🐘 (Gestión integrada de servidores)
* **Base de Datos:** MySQL / SQL Relacional 🐬
* **Control de Versiones:** Git & GitHub

## ⚙️ Instalación y Ejecución

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/dalthashark/appMantenimientoAlumno.git
   ```
