Un crawler es un pequeño programa informático que analiza las páginas web de forma automática. Su principal objetivo es seguir cada uno de los enlaces que se encuentra en cada sitio web; posteriormente, almacenará en sus bases de datos una copia de todo lo que encuentra
Obtén la URL inicial. La URL inicial es un punto de entrada para el rastreador web, que enlaza con la página web que debe rastrearse, mientras rastreamos la página web, debemos obtener el contenido HTML de la página y luego analizarlo para obtener las URL de todas las páginas vinculadas a esta página; coloque estas URL en una cola.
Recorra la cola, lea las URL de la cola una por una, para cada URL, rastree la página web correspondiente, luego repita el proceso de rastreo anterior.
Compruebe si se cumple la condición de parada. Si no se establece la condición de detención, el rastreador seguirá rastreando hasta que no pueda obtener una nueva URL.

**Codigo ejecutado**

entrantes = 0
salientes= 6
entrantes = 0
salientes= 3
entrantes = 0
salientes= 2
entrantes = 0
salientes= 1
entrantes = 0
salientes= 2
entrantes = 1
salientes= 10
[[1.0, 'https://ucsp.edu.pe/cs111/python.html'],
 [0.5, 'https://ucsp.edu.pe/cs111/implementacion.html'],
 [0.5, 'https://ucsp.edu.pe/cs111/guido.html'],
 [0.3333333333333333, 'https://ucsp.edu.pe/cs111/peter.html'],
 [0.16666666666666666, 'https://ucsp.edu.pe/cs111/index.html'],
 [0.1, 'https://ucsp.edu.pe/cs111/pseudocodigo.html']]
