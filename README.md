# Proyecto-Semana-2-Pandas-Data-Cleaning-


El propósito de este proyecto fue la limpieza de un set de datos que trata sobre los ataques de tiburón. Para el proyecto, recibimos un archivo .csv que contenia 23 columnas con información relevante. Por ejemplo, venia que especie de tiburón fue el que ataco, el nombre de la persona afectada, la fecha, la fatalidad, entre otras.  

Los datos no venían bien ordenados así que se aplicó una limpieza y organización con la librería pandas de python. Para dar un poco de contexto, comenzamos con 26,000 filas aprox y termiamos con 1,500 filas. Todo esto fue porque eliminamos las filas duplicadas, las cuales tenían todos sus valores vacíos. 

Después de eliminar estas filas duplicadas, se aplicaron otros métodos de limpieza, nos quedamos solamente con el top 10 de países, que llegan a representar el 80% de los ataques. También eliminamos todos los registros del siglo pasado. 

Algunos métodos de limpieza que se aplicaron fue el eliminar espacios para homogenizar las categorías, filtrar para quedarnos con ciertos países y ciertos años, eliminar ciertas palabras que no eran relevantes, rellenar columnas vacías con datos relevantes, etc..

Finalmente para visualizar los datos se usó la librería de seaborn. Para este caso, únicamente se utilizó los pie charts sobre el porcentaje y no sobre el número total de casos, esto es porque al final de la limpieza, eliminamos muchos registros así que comparar las variables en el gráfico sobre el total de registros no era muy acertado. 

Para clarificar un poco el porque se uso pie charts sobre el porcentaje total, imaginemos que sobre un año hay un millón de contagios de COVID, pero si perdemos 400,000 registros porque faltaban datos, no podemos decir que hubo 600,000 contagios, eso no sería acertado. Lo que si podríamos hacer es ver esos datos como si fueran un sample, podemos ver que porcentaje del 100% son mujeres y hombres, que porcentaje de ese 100% fueron fatatles. Eso fue lo que se hizo para graficar este data set de tiburones. 