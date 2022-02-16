# Programacion-web
ACTIVIDAD 3
REPORTE

![1](https://user-images.githubusercontent.com/98380795/154207074-74197674-4455-428c-a83e-da0662beb302.png)

En esta parte se cargaron todos los sprites que van a conformar nuestro juego,desde el fondo, personaje, accesorios y plataformas



![2](https://user-images.githubusercontent.com/98380795/154207607-1d295dc1-0f0a-499c-9f6a-d8b82191171e.png)



En esta parte se crean los objetos, se observa que las plataformas seran estaticas, ya que en ellas se les agregara una colision fisica. Al mismo tiempo los sprites
se pueden escalar y acomodar en las cordenas x,y.



![3](https://user-images.githubusercontent.com/98380795/154207972-80942bdd-27d5-49a7-9e04-7a66bc553e58.png)

Se crean las animaciones del personaje cuando se mueve a la izquierda, derecha, asi mismo dependiendo  que sprite sea, se seleccionan el rango que hacen el movimiento.


![4](https://user-images.githubusercontent.com/98380795/154208638-b4b9c800-7631-4b3e-9db5-98c4215c06e4.png)

Se crean las 12 estrellas y al mismo tiempo se hace una separacion de 70 pixeles entre ellas, hacemos que las bombas se hagan de tipo  fisica para que se puedan
hacer colisiones y añadimos el marcador 
Al mismo tiempo añadimos las colisiones que existen  entre objetos y  tambien las funciones de que pasarian  si hay colisiones entre objetos especificos.


![5](https://user-images.githubusercontent.com/98380795/154209156-27042b89-c47e-4a60-b421-93a4f6fbf12d.png)

LINK AL VIDEO DEL JUEGO FUNCIONANDO
https://drive.google.com/file/d/1RvltQfwvSAJdp1m51dp6C22dSRKWhdBz/view?usp=sharing



Aqui le damos movimiento al personaje dependiendo el evento al momento de presionarlo.


![6](https://user-images.githubusercontent.com/98380795/154209384-a26b3f87-cecd-419b-8596-6f465b6cd4c4.png)


Al momento de colisionar el jugador con el objeto estrella  va aumneta el score del jugador y cuando estas se agoten  se crearan mas, que al mismo tiempo se creara una
bomba cada vez que suceda este evento


![7](https://user-images.githubusercontent.com/98380795/154209676-06576462-24c8-4388-9f3b-415b4222bd9a.png)


Para finalizar en la funcion donde se colisiona el jugador con la bomba, hace que el jugado se pause, se pinte de rojo  y que haga perder el juego
Lo mismo pasa cuando cae al precipicio .
