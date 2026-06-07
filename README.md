# SQL_Final_Project
## 1. Análisis de Base de Datos Sakila mediante SQL 📊💾

## 2. Descripción del Proyecto 📖
Este proyecto representa el trabajo final del módulo de SQL, donde se realizan consultas avanzadas sobre la base de datos **Sakila**, una base de datos de muestra que simula el sistema de gestión de una tienda de alquiler de películas (DVD rental store).

El objetivo principal es demostrar el dominio de conceptos fundamentales y avanzados de SQL, incluyendo:
- Consultas básicas (SELECT, WHERE, ORDER BY)
- Funciones de agregación (COUNT, SUM, AVG, MAX, MIN)
- Joins entre múltiples tablas
- Subconsultas
- Agrupaciones (GROUP BY, HAVING)
- Análisis estadístico (VARIANCE, STDDEV)
- Manipulación de fechas y strings

📊 **Objetivo:** Resolver más de 50 consultas SQL de complejidad creciente para extraer información valiosa de una base de datos relacional, demostrando habilidades en análisis de datos mediante SQL.

## 3. Estructura del Proyecto 📝
A continuación, explico la estructura del proyecto realizado, así como los distintos archivos utilizados:

### Archivos principales:

**BBDD_Proyecto_shakila_sinuser.sql:**
- Base de datos completa de Sakila con todas las tablas necesarias
- Incluye: actor, film, category, customer, rental, payment, inventory, store, staff, address, city, country, language, film_actor, film_category
- Script para crear el esquema completo de la base de datos

**queries_sakila.sql:**
- Archivo principal con todas las consultas SQL resueltas
- Más de 50 ejercicios organizados y comentados
- Cada consulta incluye explicación del objetivo y la solución

**EnunciadoDataProject_SQL.Lógica.pdf:**
- Documento con todas las preguntas y requisitos del proyecto
- Guía de los ejercicios a resolver

**README.md:**
- Descripción del proyecto
- Estructura y explicación del trabajo realizado
- Conclusiones y aprendizajes obtenidos

## 4. Instalación y Requisitos 🛠️
Para trabajar con este proyecto he utilizado las siguientes herramientas y plataformas:

**Software necesario:**
- **MySQL / MySQL Workbench** → Para ejecutar las consultas SQL y gestionar la base de datos
- **Visual Studio Code** → Para editar archivos SQL y trabajar con el README
- **Git / GitHub Desktop** → Para control de versiones y subir el trabajo final

**Pasos para ejecutar el proyecto:**
1. Instalar MySQL o cualquier sistema gestor de bases de datos compatible
2. Ejecutar el archivo `BBDD_Proyecto_shakila_sinuser.sql` para crear el esquema de la base de datos
3. Ejecutar las consultas del archivo `queries_sakila.sql` para obtener los resultados

## 5. Contenido de las Consultas SQL 📊

El archivo `queries_sakila.sql` contiene consultas que cubren los siguientes temas:

### Consultas básicas:
- Filtrado de datos con WHERE
- Ordenamiento con ORDER BY
- Búsqueda de patrones con LIKE
- Operadores lógicos (AND, OR, NOT)
- Rangos con BETWEEN

### Funciones de agregación:
- COUNT() - Conteo de registros
- SUM() - Suma total de ingresos
- AVG() - Promedios de duración y precios
- MAX() / MIN() - Valores máximos y mínimos
- VARIANCE() / STDDEV() - Análisis estadístico

### Joins y relaciones:
- INNER JOIN - Relacionar actores con películas
- Consultas con múltiples tablas
- Análisis de categorías y clasificaciones

### Agrupaciones y filtros avanzados:
- GROUP BY - Agrupación por categorías, fechas, etc.
- HAVING - Filtrado de grupos
- Análisis temporal (por día, mes, año)

### Subconsultas:
- Películas con duración superior al promedio
- Consultas anidadas para análisis complejos

## 6. Resultados y Conclusiones 📊

Tras completar este proyecto, he adquirido y demostrado las siguientes competencias:

✅ **Dominio de SQL:** Capacidad para escribir consultas SQL complejas que extraen información valiosa de bases de datos relacionales

✅ **Análisis de datos:** Habilidad para responder preguntas de negocio utilizando consultas SQL, como:
- ¿Cuánto dinero ha generado la empresa en total?
- ¿Cuáles son los días con más alquileres?
- ¿Qué categorías de películas tienen mayor duración promedio?

✅ **Optimización:** Comprensión de cómo estructurar consultas eficientes utilizando joins apropiados y evitando redundancias

✅ **Pensamiento analítico:** Capacidad para descomponer problemas complejos en consultas SQL manejables

**Aprendizajes clave:**
- La base de datos Sakila es un excelente ejemplo de modelo relacional normalizado
- Las funciones de agregación son fundamentales para el análisis de negocio
- Los joins permiten combinar información de múltiples fuentes
- SQL es una herramienta imprescindible para cualquier analista de datos

## 7. Próximos Pasos 🔄

Con las habilidades adquiridas en este proyecto, los siguientes pasos incluyen:

📈 **Proyectos futuros:**
- Integrar SQL con herramientas de visualización (Power BI, Tableau)
- Trabajar con bases de datos más grandes y complejas
- Optimización avanzada de consultas
- Aprender sobre índices y performance tuning
- Implementar procedimientos almacenados y triggers

💼 **Aplicaciones profesionales:**
- Análisis de datos empresariales
- Generación de reportes automáticos
- ETL (Extract, Transform, Load) processes
- Business Intelligence

---

**Autor:** Diego Hernández Pellegrini  
**Proyecto:** SQL Final Project - Sakila Database Analysis  
**Fecha:** 2026
