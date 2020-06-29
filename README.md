# Tutorial de Microsoft Azure, para generación de máquinas virtuales

<br>

**1.	MARCO TEÓRICO**

<br>

**A.	MÁQUINAS VIRTUALES EN AZURE**

El uso de máquinas virtuales (o VM, por Virtual Machines) en las empresas está creciendo con la popularización de la nube y las aplicaciones móviles. Con este tipo de sistemas, las empresas pueden adquirir versatilidad a la hora de desplegar los programas de gestión interna de la empresa o desarrollar aplicaciones móviles para sus clientes. Microsoft ofrece un servicio para el uso de este tipo de sistemas en su plataforma Azure.
 
 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/m1.jpg)
 
 

**B.	MICROSOFT AZURE**

Es un software en línea para la generación de máquinas virtuales de Azure permiten la implementación de una serie de aplicaciones y programas informáticos en un sistema virtualizado. Además, Azure también permite la virtualización de sistemas operativos Linux y de aplicaciones de Oracle, SAP o IBM, entre otros. Sin embargo, las máquinas virtuales de Azure no tienen una disponibilidad completa con todas las aplicaciones y programas para empresas. 

  ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/m2.jpg)
  
 
**VENTAJAS Y DESVENTAJAS**

Las máquinas virtuales de Azure ofrecen una serie de ventajas:

-	Interfaz y administración sencillas

- Aislamiento de fallos

- Mayor protección de los datos

- Acceso remoto

-	Aplicaciones de Microsoft integradas con más facilidad 

Desventajas en estos sistemas como:

-	Aplicaciones más lentas

-	Interoperabilidad reducida: no contar con dos equipos físicos que puedan conectarse entre sí.

-	Problemas de compatibilidad

<br>

**C.	CLOUD COMPUTING** 

De una manera simple, la computación en la nube (cloud computing) es una tecnología que permite acceso remoto a softwares, almacenamiento de archivos y procesamiento de datos por medio de Internet, siendo así, una alternativa a la ejecución en una computadora personal o servidor local. En el modelo de nube, no hay necesidad de instalar aplicaciones localmente en computadoras.

La computación en la nube ofrece a los individuos y a las empresas la capacidad de un pool de recursos de computación con buen mantenimiento, seguro, de fácil acceso y bajo demanda.

La computación en la nube utiliza una capa de red para conectar los dispositivos de punto periférico de los usuarios, como computadoras, smartphones y accesorios portátiles, a recursos centralizados en el data center. Antes de la computación en la nube, la ejecución confiable de software por las empresas que ofrecían servicios solo era posible si ellas podían también pagar por el mantenimiento de la infraestructura de los servidores necesarios

  ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/m3.jpg)


**2.	LISTA DE COMPONENTES** 

- Computador con  Sistema Operativo Windows 8 ó 10


 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/m4.jpg)

<br>

<br>

**3.	EJECUCIÓN DEL PROYECTO**

<br>

1.	Ingresamos a la página oficial de Microsoft Azure versión para estudiantes en el siguiente link:

                https://azure.microsoft.com/es-es/free/students/

   Le damos clic en Activar ahora

  ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e1.jpg)

2.	Aparece una ventana donde se debe validar nuestra identidad por medio de un correo electrónico, este correo puede ser institucional o particular, ingresamos el correo y clic en Siguiente

  ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e2.jpg)

3.	Ingresamos la contraseña correspondiente al correo electrónico proporcionado en el paso anterior y le damos clic en Registrarse
 
  ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e3.jpg)
 
4.	Aceptamos el acuerdo de suscripción y le damos clic en Registrarse
 
 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e4.jpg)

5.	Una vez que estamos registrados somos re direccionados al portal oficial de Azure, le damos clic en Inicio para iniciar la creación de nuestra máquina virtual 

 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e5.jpg)
 
6.	Nos aparece una nueva ventana, nos dirigimos a la parte superior izquierda y le damos clic en “Crear un recurso” 

 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e6.jpg)
 
7.	En este paso podemos elegir el sistema operativo que deseamos para nuestra máquina virtual.
Nota: En el caso que la creación de la máquina virtual sea por motivos pedagógicos y se vaya a hacer uso solo mediante la suscripción gratuita, el sistema operativo que se vaya a elegir debe estar dentro de los términos de gratuidad caso contrario se pueden generar costos innecesarios.
 
  ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e7.jpg)
 

8.	Una vez seleccionado el sistema operativo en este caso: Windows Server 2016

En la siguiente ventana procedemos a llenar los campos de información en tipo de suscripción es muy importante colocar “Azure for Students” y en región lo más aconsejable es colocar una región cercana a la nuestra.

En tamaño seleccionamos el tamaño estándar debido a que es la única opción dentro del acuerdo de gratuidad, en esta opción está predeterminado:

 **Procesador: Intel Xeon R platinum**	

**RAM: 3,5 GB**


 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e8.jpg)
 

9.	Escribimos un nombre de Usuario y proporcionamos una contraseña la cual nos servirá para ingresar a nuestra máquina virtual una vez que sea creada.
 
  ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e8.1.jpg)
 
10.	En la casilla de Reglas de Puerto de entrada seleccionamos todos los recuadros esto va ha permitir que se pueda acceder a la máquina virtual desde cualquier computador, una vez configurado este parámetro le damos clic en Siguiente Discos 
 
 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e9.jpg)




11.	En tipo de disco del sistema operativo podemos seleccionar cualquiera de las tres opciones siendo el disco duro de mejores características el SSD Premium o disco sólido Premium pero para nuestra implementación se eligió el HDD estándar.
Las siguientes casillas las dejamos por defecto y le damos clic en Siguiente: Redes
 
 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e10.jpg)


 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e10.1.jpg)
 

 

12.	En esta ventana nos aseguramos que se encuentre activado la casilla de “Habilitar plan básico de forma gratuita”, el resto de casillas las dejamos por defecto y le damos clic en Siguiente: Opciones Avanzadas
 
 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e.11.jpg)


13.	Al menos que se necesite que nuestra máquina virtual se desarrolle en un tipo de formato o extensión diferente le damos clic en Siguiente: Etiquetas


 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e12.jpg)


14.	Este vendría a ser el paso final de la interfaz de creación simplemente le damos clic en Siguiente: Revisar y Crear

  ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e13.jpg)


15.	En la Ventana de Crear podemos observar todas las características que posee nuestra máquina virtual simplemente le damos clic en CREAR

 
  ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e14.jpg)

 

16.	Una vez que la máquina Virtual fue creada podemos observar el mensaje “Se completó la implementación”, nos dirigimos a la parte inferior del y le damos clic en: Ir al Recurso

 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e15.jpg)
 
 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e15.1.jpg) 
 



17.	En esta ventana le damos clic en Conectar y seleccionamos RDP
 
 
 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e16.jpg) 

 

18.	Le damos Clic en Descargar archivo RDP y seleccionamos la ubicación donde deseamos que se guarde el archivo en este caso seleccionamos el Escritorio, este archivo es el ejecutable de nuestra máquina virtual

 
 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e17.jpg)


19.	Una vez descargado el archivo RDP se muestra el siguiente icono le damos doble clic y seleccionamos Conectar

 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e18.jpg) 


20.	Ingresamos el Usuario y la contraseña que escribimos al momento de la creación de la máquina virtual y le damos clic en Aceptar
 
 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e19.jpg)
 
 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e19.1.jpg)
 

21.	En la nueva ventana emergente le damos clic en Sí y esperamos que la interfaz se cargue.


 ![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e20.jpg)



 

22.	Como se puede observar la máquina virtual se creó de manera correcta 


![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e21.jpg)


![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e21.1.jpg)
 
 

23.	Como paso final si deseamos ver las características de la máquina virtual nos dirigimos a información del sistema y podemos observar todos los atributos del sistema operativo y la capacidad de memoria RAM de la misma
 

![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e22.jpg)
 

![](https://github.com/bvalvarado/TRABAJO-EXTRA-3/blob/master/Img/e22.1.jpg)









**4.	BIBLIOGRAFÍA**

- https://azure.microsoft.com/es-es/services/virtual-machines/


- https://www.ticportal.es/temas/cloud-computing/microsoft-cloud/microsoft-azure/maquinas-virtuales-azure

- https://www.salesforce.com/mx/cloud-computing/
