# Proyecto: Alura Stores

![portadaAluraStores](https://github.com/user-attachments/assets/bc1511de-815e-42e5-837c-fd1d236c58f6)


## Índice 📋

1. Descripción del proyecto.
2. Acceso al proyecto
3. Etapas del proyecto.
4. Descripción de los datos
5. Resultados y conclusiones
6. Tecnologías utilizadas.
7. Agradecimientos.
8. Desarrollador del proyecto.

## 1. Descripción del proyecto 📚

Este proyecto se basa en un escenario de negocio en el cual el propietario de una empresa de artículos multi-rubro busca evaluar el desempeño de sus cuatro tiendas físicas, con el objetivo de decidir cuál de ellas debería ser vendida.

Para ello, se realiza un análisis de datos exhaustivo, considerando múltiples aspectos que influyen en el rendimiento de cada tienda, tales como facturación, satisfacción de los clientes, ubicación geográfica, entre otros.

A lo largo del análisis surgen observaciones relevantes que permiten no solo identificar la tienda menos eficiente, sino también detectar oportunidades de mejora y áreas que requieren intervención estratégica.

El proyecto concluye con un informe detallado, donde se presentan las principales conclusiones y se brinda una recomendación clara y justificada al propietario sobre qué tienda vender.

## 2. Acceso al proyecto 📂

Para obtener el proyecto existen dos opciones:

1. Clonar el repositorio utilizando la línea de comandos. Solo debes dirigirte al directorio donde deseas clonar el mismo e ingresar el comando:
   `git clone https://github.com/ignaciomajo/challenge_alura_stores`

2. O puedes descargarlo directamente desde el repositorio en GitHub en el siguiente enlace:
   <p><a href="https://github.com/ignaciomajo/challenge_alura_stores">https://github.com/ignaciomajo/challenge_alura_stores</p>

   Esto te llevará a la siguiente pantalla, donde deberás seguir los siguientes pasos:

![image](https://github.com/user-attachments/assets/76340301-a845-4ea9-91bb-e4f24c1730fa)
   
Esto descargará un archivo comprimido `.zip`, que podrás alojar en el directorio que desees.


## 3. Etapas del proyecto 📝

1. Descripción del proyecto
2. Importación de librerías iniciales y extracción de datos (ETL)
3. Funciones
4. EDA *(Exploratory Data Analysis)*
5. Data Analysis:
   - Analisis de facturacion
   - Ventas por categoría
   - Calificación promedio de la tienda
   - Productos más y menos vendidos
   - Costo promedio de envío por tienda
       - Análisis Geográfico de Ventas
6. Análisis Geoespacial  
7. Conclusiones y recomendación

## 4. Descripción de los datos

La base de datos utilizada para el proyecto está compuesta por 4 archivos csv, que se encuentran dentro del repositorio:

`tienda_1.csv`
`tienda_2.csv`
`tienda_3.csv`
`tienda_4.csv`

En cada uno de ellos, encontramos los siguientes campos referente a las ventas de cada tienda:

* `Producto`: Producto vendido en el registro correspondiente
* `Categoría del Producto`: Categoría a la que pertenece el producto vendido
* `Precio`: Precio que el cliente pagó por el producto
* `Costo de envío`: Costo de envío (afrontado por la empresa)
* `Fecha de Compra`
* `Vendedor`
* `Lugar de Compra` (Ciudad)
* `Calificación`: Otorgada por el cliente
* `Método de pago`
* `Cantidad de cuotas`
* `lat` y `lon`: Coordenadas de la ciudad destino del envío.

## 5. Resultados y Conclusiones ✍️

Algunas observaciones clave:

* Bogotá es la ciudad con mayor volumen de facturación, lo que sugiere una fuerte concentración del negocio en dicha ciudad.

* Productos y categorías:
     - Existen 4 categorías que aportan aproximadamente solo el 7% de los ingresos de la empresa en conjunto. Evaluar si estos productos resultan rentables para el negocio.
     - Entre los 5 productos más vendidos, 3 de ellos pertenecen a dos categorías predominantes de la empresa: **Muebles** y **Electrodomésticos**. Al ser ambas *mobiliario doméstico*, se pueden desarrollar estrategias de marketing para impulsar los productos pertenecientes a estas categorías en conjunto.

* Las calificaciones varían significativamente entre tiendas y ciudades, indicando posibles diferencias en atención o logística.

* El análisis geoespacial no permite inferir con precisión la ubicación exacta de las tiendas, por lo que se recomienda un estudio más detallado de la distribución geográfica de clientes y puntos de venta.

Estas conclusiones pueden servir como base para decisiones estratégicas enfocadas en mejorar la experiencia del cliente, reducir costos logísticos y expandirse de forma más inteligente.

***Nota:** Para conocer la tienda recomendada para su venta y su justificación detallada, consultar el informe final incluido en el proyecto.*



## 6. Tecnologías utilizadas 🛠️

![Static Badge](https://img.shields.io/badge/Python-3.11.7-blue) <br>
![Static Badge](https://img.shields.io/badge/Numpy-1.26.4-green) ![Static Badge](https://img.shields.io/badge/pandas-2.2.2-green) ![Static Badge](https://img.shields.io/badge/matplotlib-3.10.0-green)
![Static Badge](https://img.shields.io/badge/seaborn-0.13.2-green) ![Static Badge](https://img.shields.io/badge/folium-0.19.5-green) ![Static Badge](https://img.shields.io/badge/scikit_learn-1.5.2-green)

* `Jupyter Notebook`
* `Git and GitHub`

En caso de encontrarse con un error al correr el notebook debido a que alguna de las librerías no está instalada, puede ejecutar el siguiente comando en una primera celda del notebook:

`!pip install -r requirements.txt`

o desde la terminal:

`pip install -r requirements.txt`

Esto ejecutará la instalación de todas las librerías necesarias para el proyecto con sus respectivas versiones presentes en el archivo  **requirements.txt**📄 que se encuentra en el respositorio.

## 7. Agradecimientos 🤝

Quiero agradecer a Oracle y Alura LATAM por proporcionar las bases y el material necesarios para la realización de este proyecto, y por su alianza que hace posible este programa de capacitación para el desarrollo del futuro en tecnología.

![Alura LATAM](https://github.com/user-attachments/assets/92a155ab-bcbb-41c6-8bbc-a0e8f552eb0f) ![Oracle](https://github.com/user-attachments/assets/f399257d-d637-44be-809e-4bac2232fe25)

![ONE](https://github.com/user-attachments/assets/368ff23a-e3f2-4f08-a987-0f736996779c)

## 8. Desarrollador del proyecto 👷

![imagen-readme](https://github.com/user-attachments/assets/133bc743-0424-4120-a7a6-7245d2f28f8c)

**| Ignacio Majo | Data Scientist Junior | RPA Developer Junior |**

📫 Contacto: ignacio.majoo@gmail.com | 💻[LinkedIn](https://www.linkedin.com/in/ignacio-majo/)
