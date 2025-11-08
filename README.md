**Unidad 1 - Evidencia de Aprendizaje 1**
Creación de una Base de Datos Analítica

Integrantes del equipo

Raul Alberto Niño Cuervo
Jhoan Sebastian Zamudio

Profesor: Andrés Callejas

 **Objetivo**

Aplicar los conceptos de la Unidad 1 para formular una problemática real que requiera una base de datos analítica, diseñar el modelo entidad–relación, crear la base de datos, insertar información y documentar el proceso dentro de un Jupyter Notebook alojado en un repositorio de GitHub*

Instrucciones:

1. Buscar una problemática real que requiera una base de datos analítica.  
2. Crear la base de datos, introducir información y evidenciar consultas.  
3. Subir el notebook completo con evidencias al repositorio de GitHub.  
4. No se aceptan entregas en Word o PDF.  
5. Todas las evidencias (imágenes, consultas, gráficos y explicaciones) deben integrarse en el notebook.  
6. Documentar correctamente con celdas de texto y código ejecutables.

-

Estructura mínima del desarrollo

1. **Problema y dataset (Kaggle)**  
2. **Modelo entidad–relación (ERD)**  
3. **Creación de la base de datos + carga de datos**  
4. **Evidencias con consultas SQL**  
5. **Estructura mínima del repositorio**

---

 **Problema planteado**

La empresa **AutoMercado**, dedicada a la compra y venta de vehículos usados, necesita una **base de datos analítica** que centralice la información de los automóviles disponibles para la venta.  
Actualmente, los datos están **dispersos y sin estructura**, lo que dificulta:

- Comparar precios entre modelos.  
- Identificar disponibilidad de vehículos.  
- Consultar el historial del automóvil.  
- Analizar tendencias de mercado.  

---

 **Solución propuesta**

Desarrollar una **base de datos estructurada** para **AutoMercado Select** que permita:

- Almacenar, consultar y analizar información de vehículos usados.  
- Comparar precios y características como año, transmisión, combustible y kilometraje.  
- Evaluar tendencias de demanda del mercado.  
- Apoyar decisiones comerciales basadas en datos reales.  

Este sistema facilitará la toma de decisiones, aumentará la eficiencia comercial y mejorará la competitividad en el sector automotriz.

---

**Dataset seleccionado**

Nombre: Datos de coches usados ​​en sitios web  
Fuente:(https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=CAR+DETAILS+FROM+CAR+DEKHO.csv)  

Motivo de selección:  
El dataset contiene información real del mercado de vehículos usados, ideal para analizar cómo factores como marca, modelo, año, kilometraje, tipo de combustible y transmisión** influyen en el recio de venta.  
Además, ofrece datos variados y suficientes para construir un **modelo entidad–relación (ER)**, realizar **normalización** y generar **consultas analíticas** útiles para la gestión comercial.

---

**Contenido del Notebook**

El notebook incluye:

- Descripción del problema y del dataset.  
- Diseño del modelo entidad–relación (ERD).  
- Sentencias SQL para la creación de tablas e inserción de datos.  
- Consultas SQL para evidenciar resultados.  
- Visualización y análisis exploratorio de datos con Python.  

---

*** Tecnologías utilizadas**

-**Python** (Jupyter Notebook)  
-**MySQL / Databricks Community Edition**  
-**Pandas**, **SQLAlchemy**, **Matplotlib**, **Seaborn**, **PySpark**  
-**SQL** para creación y consulta de datos  

---

###  Variables Relevantes

| Variable (ES) | Variable (EN)     | Tipo         | Descripción                                                                 |
|----------------|-------------------|--------------|------------------------------------------------------------------------------|
| Make           | Brand             | Categórica   | Marca del vehículo.                                                         |
| Model          | Model             | Categórica   | Modelo específico del vehículo.                                             |
| Year           | Year              | Numérica     | Año de fabricación del vehículo.                                            |
| Price          | Price             | Numérica     | Precio de venta actual del vehículo.                                        |
| Kilometer      | Mileage           | Numérica     | Kilometraje recorrido por el vehículo (nivel de uso y desgaste).            |
| Fuel_Type      | Fuel Type         | Categórica   | Tipo de combustible utilizado.                                              |
| Transmission   | Transmission      | Categórica   | Tipo de transmisión (Manual o Automática).                                  |
| Owner          | Previous Owners   | Categórica   | Cantidad de dueños anteriores.                                              |
| Seller_Type    | Seller Type       | Categórica   | Tipo de vendedor (Particular o Concesionario).                              |


###  Modelo ER

El modelo entidad relacion es el archivo ERD de la carpeta actividad 1

![Modelo ER](ERD.PNG)


