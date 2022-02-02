
# Spark - Transacciones de Ventas en Línea

En este proyecto se utilizará el conjunto de datos de compras en línea, para explorar la segmentación de los clientes con el negocio, dado que el conjunto de datos contiene todas las transacciones ocurridas entre el 2009 y el 2011 para un comercio minorista en línea registrado en el Reino Unido.

<p align="center">
  <img src="./images/online.jpg" />
</p>

En primera instancia se realiza un **Análisis Exploratorio de Datos**, preparándolos para el **algoritmo a priori**, a través de la interesante tarea del método de aprendizaje no supervisado, es decir aplicando el enfoque de minería de **reglas de asociación** para encontrar reglas y patrones interesantes en esta base de datos de transacciones, con el fin de realizar _decisiones interesantes y útiles en lo que respecta al interés del usuario_.

Para la fuente de datos, se recurrió al repositorio [Kaggle](https://www.kaggle.com/puneetbhaya/online-retail).


## Problema
Se tiene la información de compras en línea de clientes con sus respectivas interacciones con el negocio sin explotar dicha información. En la mayoría de los casos, esta interacción esta en términos de su comportamiento de compra, es decir: la segmentación del cliente a descubrir.


## Objetivo
Explorar las características de los clientes con respecto a sus compras en línea para observar el comportamiento y patrones de compra.

* Realizar a priori un **EDA** para la descripción del conjunto de datos utilizando _**PySpark**_ de la herramienta de _**Spark**_.
* Y finalmente, aplicar **Reglas de Asociación** con la ayuda de la librería _**MLlib**_ de _**Spark**_, para encontrar reglas y patrones de comportamiento.


## Descripción del conjunto de Datos

_Dimensiones:_ 1000000 x 8

_Formato:_ csv

_Descripción de las columnas:_

* **InvoiceNo:** código de la compra
* **StockCode:** código del producto
* **Description:** nombre del producto
* **Quantity:** cantidad del producto
* **InvoiceDate:** fecha de la compra
* **UnitPrice:** precio unitario del producto
* **CustomerID:** identificación del cliente
* **Country:** país del cliente

- [x] Para ver el desarrollo del proeyecto, ingrese a la carpeta **“notebooks”**.


