#  ELECTRÓNICA DIGITAL 1 2019 -2
## UNIVERSIDAD NACIONAL DE COLOMBIA 


## TRABAJO 01- EVALUACIÓN DE MEMORIA  MÁXIMA 


### Introducción 

En las proximas 6 semana se estara trabajando en la adquición , procesamiento y visualización de  imagenes. para ellos  se hara uso de:

* Camara OV7970 sin FIFO la cual :
	* Matriz fotosensible: 640 x 480, el tañama de la image   se puede configurar 
	* Formato de salida RGB, RGB (GRB4: 2: 2, RGB565 / 555/444) sin formato, YUV (4: 2: 2) e YCbCr (4: 2: 2) Admite VGA, CIF y de CIF a formato 40 x 30.
	* Se configura  por medio del  bus SCCB (compatible con I2C), para obtener los modos de  configuración se recomienda leer la hoja de datos de la camara.
* Tarjeta STM o Arduino, En primera instancia  y para las pruebas iniciales, se hara uso de la tarjeta de procesamiento comerciales, como Arduino o STM32 , 
* Tarjeta de desarrollo FPGA, Nexys4, quacho-basic 
* Sistema de visualización 
* Sistema de Capura,  sistema manual apra inicar la captura de imfrmación

En resumen se muestra la configuración del dispositivo que se implementará.

![Diagrama](https://github.com/unal-edigital1-2019-2/work1-ram/blob/master/docs/figs/diagramaGeneral.png)

Como se observa en el diagrama anterior se debe  diseñar por  parte de cada grupo  de trabajo el contenido del bloque en verde  el cual se describr a cotinuación:


![Diagrama 2](https://github.com/unal-edigital1-2019-2/work1-ram/blob/master/docs/figs/estructura_fpga.png)


En este sentido cada grupo debe trabajar en los bloques internos verdes junto con las interconexiones.  Se proporcionará los bloques se proporcionan  en naranja .

En este setido el plan de trabajo propuesto es:

* WP01: Buffer de memoria  
	* Semana 1: Buffer de memoria  Simulación (TestBench).  Analizar la máxima memoria ram que podemos alojar en la FPGA,  y planear el método de adquisición de los datos de la cámara 
* WP02  Captura de Datos
	* Semana 2: Captura de datos Construcción del bloque de captura de datos y divisor de frecuencias según hoja de datos de la cámara.
	* Semana 3: Captura de datos Pruebas físicas con cámara 
* WP03: Procesador
	* Semana 4: Introducción al procesador *
* WP04: envio de información 
	* Semana 5: Comunicación serial, gpio 
* WP05: integración
	* Semana 6: Integración del proyecto y pruebas funcionales
Semana 7: Presentación  






### Desarrollo de  paquete de trabajo 01


Simulación (TestBench).  

Analizar la máxima memoria ram que podemos alojar en la FPGA,  y planear el método de adquisición de los datos de la cámara 

