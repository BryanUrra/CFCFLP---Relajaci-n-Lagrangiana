# CFCFLP---Relajación-Lagrangiana

Utilizando el solver Gurobi, se resuelve el Problema de Localización de Instalaciones de Carga Fija con Capacidad (CFCFLP, por sus siglas en inglés). Para crear parámetros
aleatorios se utiliza una semilla fija y se define la latitud y longitud según las coordenadas de la región de Coquimbo, Chile. La formulación matemática y los resultados de 
la optimización para una instancia de 20 clientes se visualizan en las 3 primeras imagenes.

Para conocer el comportamiento de la relajación lagrangiana frente a un problema NP-Hard, se utiliza el método del subgradiente relajando la primera restricción (ver imagenes
de los subproblemas). La heurística se ejecuta con cotas iniciales eficientes e ineficientes definidas por Daskin (1995). Los resultados obtenidos se grafican en "Cotas de
dualidad" y "Duality GAP". Finalmente, las conclusiones y resultados computacionales obtenidos se visualizan en la última imagen. 

Este trabajo fue desarrollado como parte de un trabajo del curso de Programación Lineal del Magíster en Ciencias de la Ingenieria Industrial de la Universidad Católica del 
Norte, Chile. El archivo "CFCFLP - Relajación Lagrangiana.ipynb" contiene la derivación computacional del problema que puede ser usado para probar instancias mayores o 
incluir nuevas variables y restricciones al modelo. Así mismo, se puede relajar otra restricción para comparar los resultados obtenidos.
