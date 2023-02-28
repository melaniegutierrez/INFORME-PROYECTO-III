# INFORME PROYECTO III

## 1. OBJETIVOS

Analizar el funcionamiento del Interruptor controlado por luz (LDR y 741), mediante la creación de circuito a escala de la instacion electrica para poder analizar desde un circuito ya realizado los componentes y su correcta conexión al circuito y a las fuentes de alimentacion.

### OBJETIVO ESPECIFICO

- Realizar el proceso de ingeniería inversa mediante el desallorro del Interruptor controlado por luz (LDR y 741) con el fin de conocer cómo fluyen las diferentes conexiones en los circuitos.

- Determinar la correcta conexión de los diferentes componentes utilizados en el proyecto mediante el análisis visual-físico de cada componente con el fin de evitar dañar un componente en proyectos futuros por mala conexión.

- Recrear un circuito con la función del Interruptor, mediante la guía de un circuito sistemático e investigación previa, para poner a prueba los conocimientos en conexiones físicas aprendidos en clase.

## 2. MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/117778782/221691165-91fb7665-1d71-43c1-bb5c-784413dba8dd.png)

![image](https://user-images.githubusercontent.com/117778782/221741459-dadd0385-e6d1-4363-90e6-da9d0b0ea52b.png)






SISTEMA AC
![image](https://user-images.githubusercontent.com/117778782/221742703-b1797ce7-ef52-46ae-beed-1f33e199c949.png)

TRANSISTOR
![image](https://user-images.githubusercontent.com/117778782/221742743-090ca393-f16b-4ab7-9eee-78557c9a0cc0.png)

POTENCIOMETRO
![image](https://user-images.githubusercontent.com/117778782/221742797-8d67fc6d-56e9-47ce-a87b-7133e1736401.png)

MICROCONTROLADOR
![image](https://user-images.githubusercontent.com/117778782/221742875-4b567005-da1a-441f-bd0c-9eb530540365.png)

RELE
![image](https://user-images.githubusercontent.com/117778782/221742932-cf2cfbb8-3645-487e-a8c0-053e960456b6.png)

## 3. EXPLICACION DEL CIRCUITO

![image](https://user-images.githubusercontent.com/117778782/221740964-6606ca7f-70b3-499a-8a32-b35b82a02a5b.png)

Se ha utilizado el simulador Proteus para el armado del diagrama del circuito, todos los componentes se encuentran presentes, adicionalmente se observa que en el potenciómetro se ha colocado un voltímetro, el cual nos permite ver la variación del voltaje al mover la perilla, permitiéndonos ver el correcto funcionamiento del mismo.
Este circuito conmutador activado por luz activará un relé en presencia de la luz. Tiene muchas aplicaciones, podría actuar como fotocelda y apagar la luz de una habitación o encender la radio cuando está amaneciendo.

CIRCUITO FISICO

![image](https://user-images.githubusercontent.com/117778782/221743296-3db0064c-4768-452f-933f-432f9e735e80.png)

![image](https://user-images.githubusercontent.com/117778782/221743323-b784b770-bec9-4da1-a153-2d2f2a753392.png)

![image](https://user-images.githubusercontent.com/117778782/221743344-77094ea6-cc00-4a47-8461-c49bd3381c4b.png)

**FUNCIONAMIENTO DEL CIRCUITO**

-  El principio principal de este circuito se basa en el funcionamiento del sensor LDR, es decir la resistencia dependiente de la luz y para encender o apagar la luz en función de la intensidad de iluminación a la que está sometido el LDR. La fotorresistencia / LDR varía su valor en ohmios dependiendo de la cantidad de luz que incida sobre ella.

La fotorresistencia / LDR varía su valor en ohmios dependiendo de la cantidad de luz que incida sobre ella. Una red de 2 resistencias (R1 y R2) del mismo valor, hace que el voltaje en el terminal no inversor del operacional sea de 6 voltios.

Cuando el LDR no está iluminado, su resistencia es alta y causa que el voltaje en el terminal no inversor del amplificador operacional, disminuya por debajo de los 6 voltios. La salida del amplificador operacional estará en alto, el transistor Q1 no conduce, el relé no recibe voltaje y no se activa.

La fotorresistencia / LDR varía su valor en ohmios dependiendo de la cantidad de luz que incida sobre ella. Una red de 2 resistencias (R1 y R2) del mismo valor, hace que el voltaje en el terminal no inversor del operacional sea de 6 voltios.
Cuando el LDR no está iluminado, su resistencia es alta y causa que el voltaje en el terminal no inversor del amplificador operacional, disminuya por debajo de los 6 voltios. La salida del amplificador operacional estará en alto, el transistor Q1 no conduce, el relé no recibe voltaje y no se activa.

![image](https://user-images.githubusercontent.com/117778782/221741297-03351664-1289-45b0-9089-118754d42ae2.png)

Cuando el LDR es iluminado, la resistencia y el voltaje entre sus terminales disminuye, causando que el voltaje en el terminal inversor del operacional aumente superando los 6 voltios. La salida del amplificador operacional pasa a un nivel bajo haciendo que el transistor Q1 conduzca (se sature), el relé recibe voltaje y se activa.

![image](https://user-images.githubusercontent.com/117778782/221741562-906a27ed-43ee-43ee-8593-c23da51a0fda.png)

El valor del LDR no es crítico. El potenciómetro P se regula para que tenga el mismo valor resistivo que el LDR, en condiciones normales. La batería puede ser de 12 o 9 voltios, que es la que hemos utilizado para esta práctica.

**GRÁFICA OSCILOSCOPIO:**

![image](https://user-images.githubusercontent.com/117778782/221741680-0f85bee6-7dee-4bdf-9232-470b9ae3caa4.png)

La presente gráfica nos presenta, una onda sinusoidal como ya la habíamos estudiado, se muestra el voltaje pico que toma, en este caso es de 110 V AC, es decir, que utilizamos una fuente de voltaje doméstica, en este caso también al ver la gráfica podemos determinar la frecuencia que utilizamos, (que con el cursor se marcó el tiempo en milisegundos en la que la onda tarda en realizar un ciclo), y la que es comúnmente en Ecuador, mediante la formula:

![image](https://user-images.githubusercontent.com/117778782/221741771-efc025d8-3400-43f4-9fbb-31de78b91b3e.png)

En este caso, vemos que se utilizó la frecuencia de 60 Hz, que es la común que tenemos en los tomacorrientes.

**APLICACIONES DEL CIRCUITO**

- Este circuito Interruptor controlado por luz (LDR y 741) activará un relé cuando no hay presencia de la luz. Tiene muchas aplicaciones, podría actuar como fotocelda y apagar la luz de una habitación o encender la radio cuando está amaneciendo. Sin embargo el uso mas comun de esto es el alumbrado e las vias publicas al captar poca luminidad del ambiente, los fotocensores activaras la iluminacion publica automaticamente. 

- Este circuito es ampliamente utilizado en el encendido-apagado automático de las farolas del alumbrado público o la iluminación externa de casas o chalets particulares.

- También podemos ver este control en las puertas automáticas de garaje, cuando un objeto interrumpe un emisor de luz y no le llega esa luz al receptor (célula fotoeléctrica) se acciona un circuito eléctrico (relé) que desconecta la alimentación del motor que abre o cierra la puerta y además podría indicárnoslo mediante una alarma sonora.

## 4. VIDEO

Link: https://youtu.be/5AG-xqYOkic

## 5. CONCLUSIONES

- La utilización de fotorresintencias LDR es algo importante en dispositivos electrónicos debido a su gran campo de aplicación. Gracias al efecto fotoeléctrico que presentan los materiales con los cuales se elaboran estos componentes, podemos construir aplicaciones que dependen de la luminosidad del ambiente. Un ejemplo práctico podría ser un sistema de detección de proximidad.

## 6. BIBLIOGRAFIA
