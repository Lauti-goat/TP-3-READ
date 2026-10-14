# Cierre – análisis de READ con POO

## 1) ¿Qué representa cada objeto dentro de estos sistemas?

Cada objeto representa un elemento concreto del sistema, con sus propios atributos y valores. Por ejemplo, un objeto `TicketSoporte` representa un ticket particular, mientras que un objeto `Reparacion` representa una reparación registrada.

## 2) ¿Qué diferencia existe entre buscar un único objeto y filtrar varios objetos?

Buscar un único objeto consiste en localizar un registro que cumpla una identificación determinada, como un código o número. La función puede devolver ese objeto o `None` si no existe. Filtrar consiste en recorrer los registros y mostrar todos los que cumplen una o más condiciones; por eso puede haber varios resultados o ninguno.

## 3) ¿Qué ventaja aporta return cuando se busca un objeto por código, número u orden?

`return` permite devolver el objeto encontrado a la parte del programa que hizo la búsqueda. Así, el programa puede utilizarlo después para mostrar sus datos o realizar otra consulta. Si no hay coincidencia, se puede devolver `None` para reconocer el caso.

## 4) ¿Qué función cumple una lista de objetos durante una operación READ?

La lista almacena en memoria varios objetos y permite recorrerlos para consultar su información. Con un ciclo `for` se examina cada objeto y, mediante condiciones `if`, se determina cuáles cumplen los criterios de búsqueda o filtro.

## 5) ¿Qué ventaja tiene colocar ciertas consultas dentro de métodos de la clase?

Los métodos reúnen comportamientos relacionados con los objetos y permiten reutilizar la lógica. Por ejemplo, `es_del_genero()` determina si un videojuego pertenece a un género, y `mostrar_datos()` organiza la presentación de la información. Esto evita repetir lógica fuera de la clase.

## 6) ¿Por qué los ejercicios realizados siguen siendo READ aunque utilicen clases, métodos, funciones, for e if?

Porque esas herramientas se usan para buscar, recorrer, comparar, filtrar, contar y mostrar datos ya cargados. No se cambia ni se elimina la información de los objetos, por lo que las operaciones siguen siendo consultas de lectura.

## 7) ¿Qué diferencia observás entre consultar registros representados con diccionarios y consultar objetos?

Un diccionario organiza la información mediante pares de clave y valor. Un objeto reúne atributos y también puede ofrecer métodos que representan comportamientos relacionados con esa información. En ambos casos se pueden consultar datos, pero con objetos es posible integrar los datos y operaciones relacionadas dentro de una clase.
