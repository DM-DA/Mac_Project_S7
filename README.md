# Mac_Project_S7
Integrated Project for Sprint 7
Trabajas para la tienda online Ice que vende videojuegos por todo el mundo. R
eseñas de usuarios y expertos, los géneros, las plataformas (por ejemplo, Xbox o PlayStation) y los datos históricos sobre las ventas de juegos están disponibles en fuentes abiertas. 
Tienes que identificar patrones que determinen si un juego tiene éxito o no. 

Datos que se remontan a 2016. Imaginemos que es diciembre de 2016 y estás planeando una campaña para 2017.

El dataset contiene una columna "rating" que almacena la clasificación ESRB de cada juego. El Entertainment Software Rating Board (la Junta de clasificación de software de entretenimiento) evalúa el contenido de un juego y asigna una clasificación de edad como Adolescente o Adulto.

1. Configuracion
    - Se creo repositorio en Github con el nombre Mac_Project_S7
    - Se loo repositorio en VS
    - Se creo un archivo Project_S7.ipynb
    - Se creo n entorno con en nombre Project_env
    - Se instalo pandas, streamlit y matplotlip

2. Archivo con tabla de datos
    - Se descargo el archivo games.csv y se guardo en la carpeta mac_project_s7


3. Preparacion de los datos
    - Se hizo la importación de pandas, numpy y matplotlip
    - Se se leyo el archivo cargado y se hizo lo siguiente:
        1. Se convirtio en minuscula todos los nombres de las columnas
        2. Se cambio el formato de la clumna year_of_release de float a int
        3. Limpiar los nombres de las columnas y corregir los tipos de datos
        4. Convertir la columna year_of_release en int y eliminar valores ausentes
        5. Reemplazar TBD en user_score con NaN
        6  Agregar la columna total_sales

