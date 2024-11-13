# TAREA-5
EJERCICIO 1

Para el primer mapa se hizo uso de la función cx para seleccionar ciudades y aeropuertos situados debajo del centroide de Rusia, visualizando este subconjunto en un mapa con el contorno del país como fondo. Luego, en el segundo mapa empleamos clip para recortar los ríos que cruzan las divisiones administrativas situadas por encima del centroide, mostrando solo las partes de los ríos dentro de estas áreas. Por último, visualizamos los resultados en dos mapas y verificamos que los tipos de geometría no se alteraron.

EJERCICIO 2

Para este ejercicio seleccionamos un subconjunto de municipios de un una unidad mayor, en este caso del Distrito Federal de los Urales, y luego aplicamos la operación UnaryUnion para combinar sus geometrías en una sola. Luego, obtuvimos un resultado similar utilizando el método dissolve() para agrupar los municipios en un nivel administrativo superior (el Distrito Federal de los Urales). Finalmente, aplicamos el mismo proceso para todos los municipios de Rusia. En cada caso, visualizamos los resultados mediante gráficos, mostrando las áreas combinadas de las unidades administrativas superiores.

EJERCICIO 3

En este ejercicio, usamos la función dissolver para agregar datos por región y crear mapas coropléticos. Luego, calculó los envolventes convexas (convex_hull) para subconjuntos de aeropuertos en Rusia, utilizando primero la disolución y la unión (union_all) de geometrías para generar un solo polígono representativo y visualizarlo sobre el mapa.

EJERCICIO 4

Se utilizó técnicas de superposición espacial para dividir los municipios de Rusia en cuatro regiones (norte, sur, este y oeste) basadas en los centroides. Luego, aplicamos operaciones geoespaciales como intersección para obtener las áreas comunes entre el norte y sur, así como entre el este y oeste. Usamos unión para combinar estas intersecciones, creando una región central unificada, y realizamos una limpieza de datos. Finalmente, aplicamos diferencia para obtener áreas que no están en la región central y diferencia simétrica para identificar geometrías exclusivas de cada región, visualizando los resultados en mapas.
