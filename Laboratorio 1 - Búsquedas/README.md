# Práctica de búsquedas
Las técnicas de búsqueda constituyen una serie de esquemas de representación del conocimiento, que a través de diversos algoritmos nos permite resolver ciertos problemas desde el punto de vista de IA.
En este trabajo se implementarán 2 algoritmos: 1 algoritmo de búsqueda ciega y 1 algoritmo de búsqueda heurística. Todos los nodos estarán conectados entre sí, asu vez, se define un nodo inicial y final. Por último, el programa grafica la ruta para los algoritmo implementados.

## Comenzando ⚙️
El programa recibe dos entradas que son el tamaño de la matriz o grilla. Se debe ingresar el tamaño de x y luego el de y. A continuación, se mostrará la interfaz gráfica con el camino encontrado.
Nuestro grupo implementó el algoritmo Hillclimbing (algoritmo de búsqueda ciega) y A* (algoritmo de búsqueda heurística).
En este trabajo se trabajó con el lenguaje de programación C++, la API OpenGL y Zinjai.

### Instalación 🔧
Para instalar y correr el proyecto descargue la carpeta la carpeta completa y ejecute el programa en el IDE Zinjai.

### Demo 🔧
El programa pide como entrada el tamaño de la grilla, tal y como se ve en la figura de abajo. 
<img src="https://github.com/YahairaGomez/IA/blob/main/Images/input.png">

En este caso nosotros el valor del eje x será igual a 300, mientras que el eje y será igual a 500. Una vez ingresado el tamaño de la grilla el programa mostrará la grilla dibujada y lista para utilizar.

<img src="https://github.com/YahairaGomez/IA/blob/main/Images/grilla.png">
A continuación, procederemos a darle un punto de inicio y de llegada haciendo click izquierdo sobre los puntos que queramos (punto de inicio y de llegada)

<img src="https://github.com/YahairaGomez/IA/blob/main/Images/ini.png">

Luego, podemos borrar los puntos; es decir, bloquear caminos haciendo click derecho sobre los puntos que deseemos eliminar (sin  soltar el mouse)

<img src="https://github.com/YahairaGomez/IA/blob/main/Images/borrado.png">

Después presionamos 1 si queremos una búsqueda haciendo uso de Hill climbing o 2 si queremos usar A*, tal y como se ve en las imagenes (respectivamente).


<img src="https://github.com/YahairaGomez/IA/blob/main/Images/hillclimbing.png">
<img src="https://github.com/YahairaGomez/IA/blob/main/Images/a_star.png">
Si queremos hacer una nueva búsqueda simplemente seleccionamos los nuevos puntos y listo. En caso quiera borrar nuevos caminos o validar los que antes estaban bloqueados puede hacer click en la tecla 3, esto hará que nuestro grafo se resetee.
## Autor ✒️

* **Yahaira Gomez Sucasaca** - *Documentación* - [YahairaGomez](https://github.com/YahairaGomez)
* **Anel Veliz Choque** - *Documentación* - [alexa1999](https://github.com/alexa1999)
* **Rayza Rodriguez Injante** - *Documentación* - [RayzaRodriguez](https://github.com/RayzaRodriguez)

## Expresiones de Gratitud 🎁

* Agradecimiento especial a YouTube, computación gráfica y a la cafeína ☕
