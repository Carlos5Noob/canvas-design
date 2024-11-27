# canvas-design

## Ejercicios de Canvas en HTML5 

1. Dibujar una línea recta
En este ejercicio se te pide que crees una línea recta que vaya entre los puntos de
coordenadas (50,50) y (350,350). La línea tendrá un grosor de 5 unidades y su color será
rojo. Para verlo pon al canvas un borde negro de 1 px de ancho.
2. Rectángulo simple
Ahora se trata de dibujar, dentro de un canvas de 300x200, una de las figuras geométricas
básicas: Un rectángulo sin relleno. O un contorno de forma rectangular. El origen del
rectángulo lo pones en el punto de coordenadas (50, 50) y las dimensiones serán 150 ancho
y 100 de alto. La línea ha de ser de 5 de ancho y color azul.
3. Rectángulo relleno
En este ejercicio se trata de dibujar un rectángulo relleno. El canvas tendrá unas
dimensiones de 300x200, mientras que el rectángulo tendrá una anchura de 150 y un alto
de 100. La esquina superior izquierda está en el punto (50,50). El color del relleno lo
ponemos en verde.
4. Un aro o circunferencia
En este ejercicio vas a empezar con las curvas, la curva básica es la circunferencia: Dibuja
una en un canvas de 400x400, el radio será de 100 situada en el centro del canvas y el grosor
de la línea lo pondremos a 2 en color rojo. Se trata de una circunferencia, no de un círculo,
y por tanto no va rellena.
5. Un círculo
Ahora vamos a crear un círculo o disco, algo así como una circunferencia rellena. El canvas
a utilizar es de 400x400, para el círculo el radio será de 100 situada en el centro del canvas
y el relleno (o sea el color del círculo) será azul.
6. Elipse
En este ejercicio se pide que, usando un canvas de 400x200, dibujes una elipse horizontal
con centro en el centro del canvas, los radios son 100 y 60, la línea es azul de 2px de ancho.
7. Elipse con relleno rojo
En este ejercicio se trata de crear una elipse horizontal en un canvas de 400x200. La elipse
se sitúa en el centro del canvas, siendo su ancho 400 y su alto 200. Será una elipse
horizontal y rellena en color rojo.
8. Triángulo
Este ejercicio pide crear una figura diferente a las básicas, concretamente un triángulo. El
canvas será de 300x200 y conoces los vértices del triángulo que son: (50,50), (200,50),
(50,150). La línea tendrá un grosor de 5 px y en color verde.
9. Triángulo relleno
Las figuras distintas a las básicas también se pueden rellenar: Dibuja un triángulo relleno
en un canvas de 300x200. Los vértices del triángulo son (50,50), (200,50), (50,150) y el
relleno será de color azul.
10. Dibujando texto
Dibuja las palabras “Ejercicio Final” verticalmente centradas en un canvas de 300x200. El
estilo del texto será negrita y Arial, con un tamaño de 40px. Las letras rellenas, deben ir en
color azul y situadas a 10x del lado izquierdo del canvas.
11. Gráficos Canvas.
Para practicar creando gráficos Canvas más complejos te proponemos realizar un gráfico
como el que ves a continuación:
Puedes comenzar el ejercicio a partir del archivo .html a continuación, que crea un lienzo
Canvas de 550 x 350, dibuja el contorno de un rectángulo con esas medidas para que te
sirva de referencia. Una vez acabado el ejercicio puedes borrar este rectángulo.
Hay distintas formas de resolver este ejercicio, para comprobar la solución te aconsejamos
que lo hagas siguiendo los pasos que hemos escrito como comentarios en el fichero .html
de referencia, de la siguiente manera:
• Un gradiente para el cielo que daremos como fondo de un rectángulo.
• Un gradiente para el suelo que daremos como fondo de un rectángulo.
• Un gradiente para las montañas el cielo que daremos como fondo de un trazado.
• Un gradiente radial para la nube que dibujaremos como un trazado con curvas Bezier.
Para dibujar las gotas de lluvia podemos utilizar dos bucles "for" anidados, el interior
dibujará n gotas y el exterior dibujará m filas. Cada gota será un trazado compuesto por una
línea. Para el texto hemos utilizado las fuentes Verdana y Arial.

```html
<!doctype html>
<html lang="es">
<head>
<title>Propuesto Canvas </title>
<script type="text/javascript">
function dibujarCanvas(){
var canvas = document.getElementById('miCanvas');
var contexto = canvas.getContext('2d');
contexto.strokeRect (0, 0, 550, 350);
// gradiente lineal vertical para el cielo
// gradiente lineal vertical para el suelo
// gradiente lineal vertical para las montañas
// trazado para montañas
// degradado radial para la nube
// dibujar lluvia
// texto
}
</script>
</head>
<body onLoad="dibujarCanvas();">
<canvas id="miCanvas" width="550" height="350">Su navegador no soporta
Canvas.</canvas>
</body>
</html>
```