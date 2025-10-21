# Practica 1 Complejidad
**Alumna:** 117001778 del Valle Vera Nancy Elena

Esta práctica fue realizada en el lenguaje de programación _Python_ y está pensada para ejecutarse en entornos como **Jupyther Notebook**, **Google Colab**, entre otros _IDE_’s similares. No necesita ningún elemento externo o archivo para funcionar de manera correcta.

El programa presentado hace uso de las bibliotecas de _Python_: `Random`, `Networkx` y `Matplotlib.pyplot`. De ser necesario instalar las bibliotecas con el comando `pip install <NombreBiblioteca>`.

Se dan dos ejemplos para probar la funcionalidad del algoritmo no determinista para la **Coalición Sospechosa**, el primero fue abordado durante la sesiones de ayudantía y el segundo es un ejemplo inventado. Si se desea probar con otro ejemplo se deben dar los siguientes datos

- **acc** : Un diccionario donde sus claves son los usuarios y su contenido está dado por una lista de tuplas que nos indican el minuto y la _ip_ a la que se accedió, en ese orden.
        `acc = {usuario1 : [(minuto1, ip1), … (minutoN, ipN)], …, usuarioN : […]}`
        
- **ipA** : Una lista de las _Ip_’s que fueron atacadas.
        `ipA = [ip1, …, ipN]`
        
- **K**: El tamaño máximo de la coalición sospechosa.

A su vez, para la reducción desde **Vertex Cover** se da un ejemplo revisado durante la ayudantía, más el ejemplo solicitado con _15_ vértices y _20_ aristas. Para este último, se dibujo la gráfica con ayuda de la biblioteca `Networkx`, se imprime la instancia del problema reducido a la **Coalición Sospechosa** y finalmente un resultado de la ejecución del algoritmo no determinista más la verificación de que al ingresar el conjunto de vértices para su cubierta como una coalición obtenemos una respuesta afirmativa (en este caso, _‘True’_).
Si se desea probar con otros ejemplos se deben dar los siguientes datos:

- **grafica**: Un diccionario donde sus claves son los vértices de la gráfica y su contenido son las listas de adyacencias para cada uno de ellos.
        `grafica = {vertice1 : [u1, …, uN], …, vérticeN : […]}`
        
- **K**: El tamaño de la cobertura de vértices.

El uso de diccionario tanto para representar la gráfica como lista de adyacencias, así como, para registrar los accesos de cada usuario a las _ip_’s, permite una gran flexibilidad y rapidez al acceder a sus contenidos para manipularlos, lo que simplifica los procesos de verificación y reducción dentro del programa.

