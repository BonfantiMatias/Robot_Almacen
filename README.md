# Q-Learning.
<br/>
<img align='center' alt="Fuente" src="https://raw.githubusercontent.com/BonfantiMatias/Robot_Almacen/main/Recursos/istockphoto-1314882649-612x612.jpg"/>
<br/>

En este proyecto decidi implementar un algoritmo de Q-learning en Python para un robot que recorre un almacén con 11 posibles posiciones identificadas con las letras de la A a la L. Utilicé la ecuación de Bellman y el proceso de decisión de Markov para generar el código necesario.

<br/>
<img align='center' alt="Fuente" src="https://raw.githubusercontent.com/BonfantiMatias/Robot_Almacen/main/Recursos/Almacen.png/>
<br/>


Mi objetivo principal era optimizar los flujos de trabajo del robot en el almacén. Para ello, definí los estados del entorno y las posibles acciones que el robot podía realizar. Además, definí las recompensas asociadas a cada estado para que el robot aprendiera qué acciones eran más beneficiosas.

<br/>
<img align='center' alt="Fuente" src="https://raw.githubusercontent.com/BonfantiMatias/Robot_Almacen/main/Recursos/Captura%20desde%202023-03-25%2020-39-57.png"/>
<br/>


Luego, utilicé la ecuación de Bellman para actualizar los valores de Q en cada iteración. Esto me permitió obtener la política de decisión óptima para el robot, es decir, la secuencia de acciones que maximizaba la recompensa total.
<br/>
<img align='center' alt="Fuente" src="https://raw.githubusercontent.com/BonfantiMatias/Robot_Almacen/main/Recursos/Teoria.png"/>
<br/>


Finalmente, puse en producción el modelo implementando una función que devolvía la ruta óptima entre dos posiciones dadas. Estoy muy satisfecho con el resultado de mi proyecto y creo que puede ser de gran utilidad para optimizar los flujos de trabajo en cualquier almacén
