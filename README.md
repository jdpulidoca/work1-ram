# ELECTR�NICA DIGITAL 1 UNIVERSIDAD NACIONAL DE COLOMBIA 


## TRABAJO 01- EVALUACI�N DE MEMORIA  MAXOMA 


### Introducci�n 

En las proximas 6 semana se estara trabajando en la adquici�n , procesamiento y visualizaci�n de  imagenes. para ellos  se hara uso de:

* Camara OV7970 sin FIFO la cual :
	* Matriz fotosensible: 640 x 480, el ta�ama de la image   se puede configurar 
	* Formato de salida RGB, RGB (GRB4: 2: 2, RGB565 / 555/444) sin formato, YUV (4: 2: 2) e YCbCr (4: 2: 2) Admite VGA, CIF y de CIF a formato 40 x 30.
	*Se configura  por medio del  bus SCCB (compatible con I2C), para obtener los modos de  configuraci�n se recomienda leer la hoja de datos de la camara.
 *Tarjeta STM o Arduino, En primera instancia  y para las pruebas iniciales, se hara uso de la tarjeta de procesamiento comerciales, como Arduino o STM32 , 
* Tarjeta de desarrollo FPGA, Nexys4, quacho-basic 
* Sistema de visualizaci�n 
* Sistema de Capura,  sistema manual apra inicar la captura de imfrmaci�n

En resumen se muestra la configuraci�n del dispositivo que se implementar�.

Colocar la foto


Como se observa en el diagrama anterior se debe  dise�ar por  parte de cada grupo  de trabajo el contenido del bloque en verde  el cual se describr a cotinuaci�n:


colocar la segunda foto


En este sentido cada grupo debe trabajar en los bloques internos verdes junto con las interconexiones.  Se proporcionar� los bloques se proporcionan  en naranja .

En este setido el plan de trabajo propuesto es:

WP01 Semana 1: Buffer de memoria  Simulaci�n (TestBench).  Analizar la m�xima memoria ram que podemos alojar en la FPGA,  y planear el m�todo de adquisici�n de los datos de la c�mara 
WP02 Semana 2: Captura de datos Construcci�n del bloque de captura de datos y divisor de frecuencias seg�n hoja de datos de la c�mara.
Semana 3: Captura de datos Pruebas f�sicas con c�mara 
WP03 Semana 4: Introducci�n al procesador *
WP04 Semana 5: Comunicaci�n serial, gpio 
WP05 Semana 6: Integraci�n del proyecto y pruebas funcionales
Semana 7: Presentaci�n  






### Desarrollo de  paquete de trabajo 01


Simulaci�n (TestBench).  

Analizar la m�xima memoria ram que podemos alojar en la FPGA,  y planear el m�todo de adquisici�n de los datos de la c�mara 

