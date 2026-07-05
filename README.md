# Curso
Ejercicio Maquina Virtual

Parte I: Procedimiento para la creacion de un laboratorio 

Nota: previamente debemos tener instalado VirtualBox y La ISO del sistema a trabajar.

1. Ingresar a la aplicacion de VirtualBox
2. Hacer Click sobre nueva para proceder a configurar la maquina virtual, como se muestra en la siguiente img:

<img width="573" height="354" alt="image" src="https://github.com/user-attachments/assets/d4d01ad7-e40a-48b9-915f-90319be4ea82" />
 
3. Procedemos a configurar el nombre de la maquina virtual, seleccionamos la ISO del sistema operativo, Colocamos en el detalle el OS y su version, como se muestra en la siguiente imagen

<img width="784" height="554" alt="image" src="https://github.com/user-attachments/assets/d80e55fe-1b01-433d-81f5-9ad3f7e3305b" />

4.Continuando la configuracion de la VM, ajustamos los recursos minimos necesarios para que el sistema corra establemente, como se muestra en la siguiente imagen.

<img width="783" height="302" alt="image" src="https://github.com/user-attachments/assets/246706d2-ea03-4d38-964b-384bd10c8f46" />

5.Culminado la configuracion y la instalacion del OS, procedemos a configurar el usuario "Guest" (Invitado).
6. Ir al apartado de Administracion de equipos -> Usuarios locales y grupos -> Usuarios -> Habilitar el usuario Guest.

<img width="649" height="217" alt="image" src="https://github.com/user-attachments/assets/87f60603-81c2-4c41-a699-5d4a1581aba5" />

7. Hemos finalizado la habilitacion de minimo privilegios en el equipo de laboratorio.

Parte II:

Crear red aislada:

Para trabajar en laboratorio es necesario trabajar de forma aislada este con el objetivo de mitigar la propagacion ante practicas que puedan compremeter la integridad del sistema.

Debemos ir al apartado de configuracion de la VM -> Red -> Ajustar el adaptador y seleccionar Red Interna, Como se observa en la siguiente imagen:
<img width="815" height="505" alt="image" src="https://github.com/user-attachments/assets/003d6ed3-f991-404d-bbfe-a09e43923b4e" />

Importante: La Maquina Virtual no se recomienda colocar la red como Bridged (Modo puente), debido a que la maquina va estar en nuestra misma red lo cual puede ocasionar en caso realizar pruebas de malware, virus , ransoware, etc. puedan propagarse en nuestra red.

Parte III:

Creando un Snapshot:

El objetivo de un Snapshot, es realizar una captura de la configuracion incial antes de comenzar a realizar pruebas. Este con el objetivo de analisis y realizar restauracion a un punto espesifico si el sistema se corrompe.

Para realizar un Snapshot, debemos apagar el equipo 
<img width="607" height="313" alt="image" src="https://github.com/user-attachments/assets/dc6106aa-9482-4e6c-a580-4f9208ef63ed" />
Hacemos click sobre tomar y colocamos una descripcion de la captura como se muestra en la siguiente imagen
<img width="687" height="413" alt="image" src="https://github.com/user-attachments/assets/554cb360-f913-46f0-bce8-3959341cb474" />
Culminado el Snapshot indicara fecha y hora de la captura lo cual indicaria que se realizo la captura correctamente como se muestra en la siguiente imagen a continuacion:
<img width="771" height="116" alt="image" src="https://github.com/user-attachments/assets/0bdb2bae-6790-46f3-999d-4c926c885ec6" />





