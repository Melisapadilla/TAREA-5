# TAREA-5
Ejercicio 1
Para el primer mapa se hizo uso de la función cx para seleccionar ciudades situadas debajo del centroide de un país, visualizando este subconjunto en un mapa con el contorno del país como fondo. Luego, en el segundo mapa empleamos clip para recortar los ríos que cruzan las divisiones administrativas situadas por encima del centroide, mostrando solo las partes de los ríos dentro de estas áreas. Por último, visualizamos los resultados en dos mapas y verificamos que los tipos de geometría no se alteraron.

EJERCICIO 2
Para este ejercicio seleccionamos un subconjunto de municipios de un una unidad mayor, en este caso del Distrito Federal de los Urales, y luego aplicamos la operación UnaryUnion para combinar sus geometrías en una sola. Luego, obtuvimos un resultado similar utilizando el método dissolve() para agrupar los municipios en un nivel administrativo superior (el Distrito Federal de los Urales). Finalmente, aplicamos el mismo proceso para todos los municipios de Rusia. En cada caso, visualizamos los resultados mediante gráficos, mostrando las áreas combinadas de las unidades administrativas superiores.
