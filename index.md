# SimonTec
## Descripción del problema

SimonTec es un juego de memoria que consiste en un círculo compuesto de 
cuatro cuadrantes, cada uno con un color: verde, rojo, azul y amarillo. 
El juego de forma aleatoria va iluminando los cuadrantes de colores. 
Después de esperar, el usuario debe ir introduciendo las ecuencia mostrada 
en el orden correcto. Si lo consigue, este responderá con una secuencia 
más larga, y así sucesivamente.Si falla, perderá el juego y deberá empezar 
de nuevo

## Historias de Usuario

Se dividen en dos tipos. 
<br>
De Interfaz:<br>
* Cuatro botones de colores
* Contador de nivel
* Circulo relleno

De lógica:
* Elegir aleatoriamente un color
* Agregar el color al patron
* Comparar patrones
* Aumentar velocidad
* Reiniciar valores

## Clasificación según criticidad y frecuencia de uso
![alt text][logo1]

[Logo1]: https://github.com/Tzornti/SimonTec/raw/main/Imagenes/Organizacion.png "Logo Title Text 2"

## Minimal System Span
![alt text][logo2]

[logo2]: https://github.com/Tzornti/SimonTec/raw/main/Imagenes/minimal.png "Logo Title Text 3"

## Plan de Iteración
El plan de iteracion consite en ir resolviendo los procesos en un orden de izquierda a derecha, de arriba 
hacia abajo como mostrado en el siguiente diagrama

![alt text][logo3]

[logo3]: https://github.com/Tzornti/SimonTec/raw/main/Imagenes/Iteracion.png "Logo Title Text 4"

## Diagrama conceptual
El juego iluminara un cuadrante de la siguiente manera

![alt text][logo5]

[logo5]: https://github.com/Tzornti/SimonTec/raw/main/Imagenes/rojo.png "Logo Title Text 6"

si el jugador acierta el juego subira de nivel repetira el patron e iluminara al final un nuevo cuadrante

![alt text][logo6]

[logo6]: https://github.com/Tzornti/SimonTec/raw/main/Imagenes/verde.png "Logo Title Text 7"

en caso contrario se iluminara el centro y se volvera a empezar

![alt text][logo7]

[logo7]: https://github.com/Tzornti/SimonTec/raw/main/Imagenes/fail.png "Logo Title Text 8"

## Diagrama de Clases
![alt text][logo4]

[logo4]: https://github.com/Tzornti/SimonTec/raw/main/Imagenes/diagramclass.png "Logo Title Text 5"