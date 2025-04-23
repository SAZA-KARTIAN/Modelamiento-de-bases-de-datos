# Portafolio de Modelamiento de Bases de Datos SQL

¡Bienvenido a mi portafolio dedicado al modelamiento de bases de datos en SQL! Aquí encontrarás mis proyectos y prácticas sobre diseño conceptual, lógico y físico de bases de datos, así como scripts de creación y ejemplos de consultas.

## 📖 Descripción
Este repositorio recopila mis trabajos en:

- Diseño de diagramas entidad-relación (ER).
- Transformación de modelos conceptuales a lógicos (normalización, relaciones).
- Implementación física en distintos motores SQL (MySQL, PostgreSQL, SQL Server).
- Scripts de creación de esquemas y poblado de datos de ejemplo.
- Ejemplos de consultas complejas (joins, subconsultas, índices y optimización).

## 📂 Estructura del Repositorio

```
/ diagrams/                      # Archivos de diagramas ER (diagrams.net, PNG, SVG)
/models/                         # Modelos organizados por etapa
  ├── conceptual/                # Diagrama ER y descripciones de entidades
  ├── logical/                   # Tablas, atributos, claves primarias y foráneas
  └── physical/                  # DDL específico por motor y optimizaciones
/scripts/                       # Scripts SQL de creación y carga de datos
/ examples/                      # Ejemplos de consultas y casos de uso
  ├── JOINS/                     # Consultas con diferentes tipos de joins
  ├── SUBQUERIES/                # Subconsultas y CTEs
  └── PERFORMANCE/               # Índices, EXPLAIN y optimización
README.md                        # Este archivo de presentación
LICENSE                          # Licencia del repositorio
```

## ⭐ Proyectos Destacados

- **Base de Datos de Capacitación Técnica**  
  Diseño de un sistema para gestionar capacitaciones, personal técnico y cursos.

- **Base de Datos de Equipos de Transporte Vertical Certificados**  
  Estructura de tablas para Equipo, Instaladores, Certificación, etc.

- **Sistema de Gestión de Mantenimiento**  
  Esquema para registrar ascensores, técnicos, intervenciones y piezas.

## 🚀 Cómo Usar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/sql-modeling-portfolio.git
   ```
2. Revisa los diagramas en `diagrams/` para entender el modelo conceptual.
3. Abre los archivos DDL en `models/physical/` y ejecuta los scripts SQL en tu motor:
   ```sql
   -- MySQL
   source models/physical/mysql/schema.sql;
   source scripts/load_sample_data.sql;
   ```
4. Explora ejemplos de consultas en `examples/` para ver patrones de uso.

## 🤝 Contribuciones
Si tienes sugerencias de mejora de modelos, recomendaciones de normalización u optimización de consultas, abre un _issue_ o envía un _pull request_. ¡Aprecio tu feedback!

## 📝 Licencia
Este repositorio está bajo la licencia MIT. Consulta `LICENSE` para más detalles.

## 📫 Contacto
- **Autor**: Sebastián Zúñiga Alfaro
- **Email**: sebastian.zunigaa@sansano.usm.cl  
- **LinkedIn**: [https://www.linkedin.com/in/sebastian-zuniga](https://www.linkedin.com/in/sebastianzunigaalfaro/)

---

> _«Un buen modelo de datos es la base para información confiable y decisiones acertadas.»_

