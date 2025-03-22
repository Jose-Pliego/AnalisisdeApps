# Análisis de Factores de Éxito en Apps de Google Play

## Propósito del Proyecto

Este proyecto tiene como objetivo analizar los factores que influyen en las calificaciones y valoraciones de las aplicaciones móviles en Google Play. Mediante un análisis detallado de diversas variables como el tipo de aplicación (gratuita o de pago), su tamaño, el precio, la categoría y las calificaciones de los usuarios, se busca identificar los elementos clave que contribuyen al éxito de una aplicación en esta plataforma.

## Datos Utilizados

El análisis se realizó utilizando dos conjuntos de datos principales:

1. **apps.csv**: Contiene información sobre las aplicaciones en Google Play, como su nombre, categoría, precio, número de instalaciones, calificación, tamaño, tipo (gratuita o de pago), entre otros.
2. **user_reviews.csv**: Incluye comentarios y calificaciones de los usuarios sobre las aplicaciones, junto con la polaridad de los sentimientos expresados en las reseñas.

Los datos fueron procesados y limpiados para eliminar duplicados, manejar valores nulos y transformar las variables necesarias para el análisis.

## Técnicas Aplicadas

Para realizar el análisis y generar las conclusiones, se utilizaron las siguientes técnicas y herramientas:

- **Análisis Exploratorio de Datos (EDA)**: Se exploraron las distribuciones de variables clave, como las calificaciones y los precios, y se analizaron las relaciones entre ellas (por ejemplo, entre el tamaño de la app y su calificación).
  
- **Visualización de Datos**: Se utilizaron herramientas de visualización como `matplotlib` y `seaborn` para crear gráficos como histogramas, gráficos de barras, diagramas de dispersión y cajas, lo que permitió identificar patrones y tendencias en los datos.

- **Análisis de Sentimientos**: A través de la polaridad de los comentarios de los usuarios, se analizó si el tipo de aplicación (gratuita o de pago) influía en los sentimientos de los usuarios.

- **Modelos de Clasificación (Decisión y Regresión Logística)**: Se implementaron modelos de Machine Learning para clasificar y predecir el éxito de las aplicaciones en función de las variables seleccionadas, utilizando algoritmos como el árbol de decisión y la regresión logística.

## Conclusiones

Algunas de las principales conclusiones obtenidas del análisis incluyen:

1. **Categorías Populares**: Las aplicaciones en categorías como "Juegos" y "Productividad" fueron las más comunes, y en general, las aplicaciones de estas categorías obtuvieron mejores calificaciones.
   
2. **Relación entre Tamaño y Calificación**: En general, no se observó una relación directa clara entre el tamaño de la aplicación y su calificación, pero algunas aplicaciones más pequeñas y especializadas lograron mejores valoraciones.

3. **Impacto del Precio en las Calificaciones**: Para las aplicaciones de pago, el precio parecía estar relacionado con calificaciones más altas, pero solo en ciertos rangos de precios. Las aplicaciones extremadamente caras no mostraron un aumento significativo en la calificación.

4. **Sentimientos de los Usuarios**: Las aplicaciones gratuitas y las de pago no parecían generar diferencias significativas en la polaridad de los sentimientos de los usuarios, aunque las aplicaciones de pago tendían a recibir comentarios más positivos en general.

5. **Distribución de Precios**: Las aplicaciones de pago en categorías populares tienden a tener precios más altos, aunque algunas categorías tienen un rango de precios más amplio, lo que permite tanto aplicaciones económicas como premium.

## Herramientas y Librerías Utilizadas
- **pandas**: Para la manipulación de datos.
- **matplotlib y seaborn**: Para la visualización de datos.
- **sklearn**: Para la implementación de modelos de machine learning como el árbol de decisión y la regresión logística.
- **warnings**: Para manejar advertencias y facilitar la visualización.

## Resultados
![image](https://github.com/user-attachments/assets/7b2e5737-5ece-48aa-8525-9080af12b3e9)
![image](https://github.com/user-attachments/assets/664e3aee-6f3a-486b-b4f7-51f1d40f4997)
![image](https://github.com/user-attachments/assets/8f211a81-368c-4bb9-8531-fd3068cee676)
![image](https://github.com/user-attachments/assets/08747569-e602-4be4-959a-95a9dd2b2c74)
![image](https://github.com/user-attachments/assets/d0e81235-ffed-42ad-945a-0c539175aab4)
