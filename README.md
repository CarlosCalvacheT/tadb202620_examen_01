# tadb202620_examen_01
# Examen No. 1 – Lógica Almacenada en Base de Datos

## Tópicos Avanzados de Base de Datos

**Universidad Pontificia Bolivariana**
**Facultad de Ingeniería**
**Programa:** Ingeniería en Ciencia de Datos
**Periodo:** 202620

---

### Descripción

Este repositorio contiene la solución del Examen No. 1 del curso Tópicos Avanzados de Base de Datos, cuyo dominio de problema corresponde a la cadena de frío de medicamentos de la empresa Distri-Cold.

El proyecto comprende el diseño e implementación de un modelo de datos relacional, scripts SQL, consultas de exploración, funciones, procedimientos, resultados de consultas y la documentación asociada al proceso de implementación.


---

## Integrantes

| Nombre completo                       | ID de SIGAA | DBMS utilizado | NRC                                  |
| ------------------------------------- | ----------- | ---------------|------------------------------------- |
| Jeronimo Galvez Vallejos              | 000540184   |  |         | 21260 |
| Carlos Alberto Calvache Torres        | 000540169   | PostregSQL | 21463 |


---


## Contenido del repositorio

El repositorio contiene los siguientes entregables:

### Documentación

* Documento PDF correspondiente al proceso de abastecimiento e instalación de la infraestructura seleccionada.
* Documento PDF correspondiente a la configuración de conectividad y conexión desde el IDE utilizado.
* Documento PDF con la interacción realizada con la herramienta de inteligencia artificial utilizada durante el desarrollo del examen.
* Diagrama relacional del modelo de datos en formato PNG o JPEG.

### Scripts SQL

* Script de implementación del modelo de datos, incluyendo la creación del usuario/esquema, privilegios, tablas, vistas, secuencias, funciones y procedimientos.
* Script de implementación de las consultas SQL solicitadas en el examen.
* Funciones y procedimientos utilizados como apoyo para las operaciones CRUD.
* Función que utiliza **Window Functions** y **Common Table Expressions (CTE)**, junto con la consulta SQL correspondiente.

### Resultados

* Archivos de salida generados a partir de la ejecución de las consultas SQL.
* Archivo de resultados correspondiente a la consulta desarrollada mediante Window Functions y CTE.

### Configuración del repositorio

* `.gitignore`: contiene las reglas para excluir archivos que no deben almacenarse en el repositorio.
* `README.md`: documento actual con la descripción y organización del proyecto.

---


## Organización del repositorio

La estructura general del repositorio es la siguiente:

```text
tadb202620_examen_01/
│
├── README.md
├── .gitignore
│
├── documentos/
│   ├── abastecimiento_infraestructura.pdf
│   ├── conectividad_IDE.pdf
│   └── interaccion_IA.pdf
│
├── diagrama/
│   └── diagrama_relacional.png
│
├── scripts/
│   ├── implementacion_modelo.sql
│   ├── consultas.sql
│   └── funciones_procedimientos.sql
│
└── resultados/
    ├── resultado_consulta_A.xlsx
    ├── resultado_consulta_B.xlsx
    ├── resultado_consulta_C.xlsx
    └── resultado_window_cte.xlsx
```
