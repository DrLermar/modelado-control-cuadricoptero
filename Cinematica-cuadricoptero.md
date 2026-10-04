# Cinemática de un Cuadricóptero

Los cuadricópteros o drones están compuestos por un cuarpo principal, motores sin escobillas y propelas o hélices.

<div align="center">
  <img src="imagenes/Drone.png" alt="Cuadricóptero y sus partes" width="500">
</div>

## Configuraciones
Existen dos configuraciones principales para el manejo de un dron:
* De forma "+"
* De forma "X"

Se debe de definir esta orientación para saber cual es el frente ya que en cada caso el control de los motores es diferente.

<div align="center">
  <img src="imagenes/DroneConf.png" alt="Configuraciones de vuelo" width="500">
</div>

De estas configuraciones se trabajará con la forma en "+" ya que la matemática es más digerible y no es complicado ir de esa configuración a la configuración en "X".

## Principio de funcionamiento

Para que el cuadricóptero vuele es necesario que dos de sus motores giren en el sentido de las manesillas del reloj (CW) y los otros dos en contra de las manesillas del reloj (CCW) intercaladamente, como se observa en la imagen.

<div align="center">
  <img src="imagenes/DroneGiro.png" alt="Configuraciones de vuelo" width="500">
</div>