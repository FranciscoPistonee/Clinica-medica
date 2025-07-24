# Sistema de Gestión de Clínica Médica – Aplicación de Escritorio en C#
Desarrollé una aplicación de escritorio en C# (.NET Framework) con SQL Server para la gestión integral de pacientes, citas, profesionales y reportes. Siguiendo una arquitectura en 3 capas (Presentación, Lógica de Negocio y Acceso a Datos) para lograr un diseño modular y fácil de mantener. Este proyecto fue realizado como Trabajo Final de la materia Laboratorio de Computación III en la Universidad Tecnológica Nacional (UTN).

# 📌 Características principales
🔹 Modelo y Base de Datos

Base de datos en SQL Server con tablas para Pacientes, Citas, Profesionales, Usuarios, etc.

Validaciones en la capa de negocio para asegurar integridad de datos (p. ej. evitar citas duplicadas).

🔹 Interfaz de Usuario (Presentación)

Windows Forms para pantallas de login, gestión de pacientes, citas y reportes.

Controles DataGridView para listados dinámicos y formularios con validaciones en tiempo real.

Diseño sencillo y claro para mejorar la experiencia del usuario.

🔹 Lógica de Negocio (Capa Intermedia)

Servicios que encapsulan reglas de negocio (intermediario entre la conexión de datos y la UI).

Implementación de patrones y Clean Architecture: casos de uso independientes de la UI y la BD.

🔹 Acceso a Datos

Conexión con la BD para obtención de datos y escritura sobre la misma.

# 📌 Funcionalidades implementadas
✔ Login con roles (Admin, Médico).
✔ CRUD de Pacientes: alta, baja, modificación y listado.
✔ Gestión de turnos.
✔ Generación de Reportes.

# 📌 Tecnologías utilizadas
✅ C# (.NET Framework 4.x)
✅ Windows Forms
✅ SQL Server 2017/2019
✅ Entity Framework 6 (Code First / Migrations)

Este proyecto demuestra mi capacidad para diseñar y desarrollar soluciones de escritorio robustas, aplicando principios de Clean Architecture, separación de capas y buenas prácticas de programación orientada a objetos.
