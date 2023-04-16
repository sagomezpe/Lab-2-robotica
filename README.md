# Laboratorio 2 - Robótica.
En este repositorio, se realiza el desarrollo del laboratorio 2 de la asignatura robótica por el profesor: Pedro Fabian Cárdenas Herrera Dr.-Ing. Y el profesor:
Msc-Ing. Jhoan Sebastián Rodríguez Rodríguez

### Integrantes:
- Julián Felipe Medina Veira <jmedinave@unal.edu.co>
- Santiago Andrés Gómez Pena <sagomezpe@unal.edu.co>
- Santiago Dleon Sánchez Romero <ssanchezro@unal.edu.co>

#### Introducción:
El laboratorio tiene como objetivo general el adecuar diversas rutinas de movimiento con un mayor uso de rutinas de rapid y del uso de entradas y de salidas

#### Descripción:
En esta práctica se desarrollarán 2 ejes temáticos:
- **Programación intermedia de rapid:** Se busca ahondar en el lenguaje de programación rapid mediante la implementación de condicionales y bucles para acelerar el desarrollo de código.
- **Manejo del módulo de entradas y salidas:** Se realizara la comunicación necesaria con el controlador para accionar rutinas de movimiento predefinidas mediante el uso de pulsadores.

#### Desarrollo:
##### Código:
El archivo de Robot Studio inicial donde esta descrita la trayectoria que se selecciono se encuentra adjunto con el nombre  <a href="https://github.com/jmedinave/Lab-1-robotica/blob/main/InicialesRobotStudio.rar">código.</a>

##### Programación intermedia de rapid:
Con el fin de establecer la comunicación entre las señales y las rutinas que se querian implementar se modifico el codigo <a href="https://github.com/sagomezpe/Lab-2-robotica/blob/1071a0cf60660b91e042c0234a4326fb5c97ba62/Main_modificado.txt">Main</a>, en donde se puede identificar que se agrego un condicional para poder ejecutar la rutina una vez se cumpla la condicion esperada. El nuevo programa completo se encuentra <a href="https://github.com/sagomezpe/Lab-2-robotica/blob/1071a0cf60660b91e042c0234a4326fb5c97ba62/InicialesJM.rspag">aqui</a>.
##### Comunicación con el módulo de entradas y salidas:

##### Videos practica en robots reales
Con el codigo diseñado en la practica anterior se realizo la correcta sincronizacion con el flex pendant y la respectiva configuración para sincronizarlo con los botones para realizar la rutina.

Por cuestiones de tiempo se implemento sin el uso de la herramienta verificando la correcta comunicacion del codigo con el modulo de entradas y salidas

https://user-images.githubusercontent.com/94912111/232251762-403a92f0-4c58-4f6a-ab7f-3c562370715f.mp4


##### Conclusiones:
-Se puede concluir con esta practica es factible el control de los brazos robóticos con sistemas de comunicación, como PLC’s, finales de carreras, sistemas de swiches y también diferentes clases de sensores.
- La implementación de los módulos de salidas y entradas digitales permiten otro tipo de automatización del proceso de ejecución de la trayectoria, lo que permite entender que hay una manera diferente para la administración de las tareas y rutinas que se pueden predeterminar en la programación del brazo robótico.
-Con esta practica se puede identificar que es esencial la interacción con las señales externas con las cuales tiene interacción un sistema robotizado ya que estas nos permiten programar contemplando medidas de seguridad, modificar el desempeño de los robots según las condiciones críticas del medio, etc 

