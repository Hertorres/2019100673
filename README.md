
# Turtle Unida

Es un proyecto realizado por Diego Franco, en donde se utiliza un paquete de Ros llamado **turtlesim**


## Instalacion de Ros

Para este proyecto es necesario contar instalado ROS en la maquina a utilizar. En caso de no contar instalado, seguir esta guia. 


[Documentación](https://wiki.ros.org/Installation)


## Pasos para la utilización
**1.** Una vez tengamos nuestro ambiente de trabajo y creado el package, dentro del mismo copiar del repositorio con: 



```bash
  git clone https://github.com/Hertorres/2019100673.git 
```



**2.** Compilar el proyecto: 



```bash
  catkin_make 
```

**3.** Iniciar ROS: 



```bash
  roscore 
```

**4.** Iniciar en una nueva terminal la tortuga: 



```bash
  rosrun turtlesim turtlesim_node
```


**5.** Ejecutar en una nueva terminal y en el directorio del entorno de trabajo ejecutar: 



```bash
  devel\setup.bat
```

**6.** Por ultimo, para realizar el movimiento de la tortuga, ejecutar: 



```bash
  rosrun nombre_package src/mover2.py
```
