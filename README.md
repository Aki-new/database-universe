# Universe Database - freeCodeCamp Certification

Este proyecto es parte del currículo de **Relational Database** de freeCodeCamp. El objetivo principal fue diseñar y poblar una base de datos relacional utilizando **PostgreSQL** para representar diversos elementos del universo conocido.

## 🚀 Características del Proyecto

La base de datos se llama `universe` y contiene una estructura jerárquica que conecta galaxias con sus respectivos sistemas y lunas.

### Estructura de la Base de Datos:
* **Galaxy**: Información sobre diferentes galaxias (espirales, elípticas, etc.).
* **Star**: Estrellas vinculadas a una galaxia específica.
* **Planet**: Planetas que orbitan dichas estrellas.
* **Moon**: Satélites naturales asociados a cada planeta.
* **Galaxy Types**: Una tabla adicional para categorizar la morfología galáctica.

## 🛠️ Detalles Técnicos

* **Motor de Base de Datos:** PostgreSQL.
* **Relaciones:** Implementación de llaves primarias (`PRIMARY KEY`) y llaves foráneas (`FOREIGN KEY`) para mantener la integridad referencial.
* **Tipos de Datos:** Uso de `INT`, `NUMERIC`, `TEXT`, `VARCHAR` y `BOOLEAN`.
* **Restricciones:** Uso de `UNIQUE`, `NOT NULL` y autoincrementos (`SERIAL`).

## 📊 Estadísticas de la Base de Datos

Para cumplir con los requisitos de la certificación, la base de datos incluye:
- **6** Galaxias.
- **6** Estrellas.
- **12** Planetas.
- **20** Lunas.

## ⚙️ Cómo reconstruir la base de datos

Si deseas replicar este proyecto localmente, asegúrate de tener PostgreSQL instalado y sigue estos pasos:

1. Crea la base de datos:
   ```bash
   createdb universe
2. Importa el archivo SQL:
```
   psql universe < universe.sql
