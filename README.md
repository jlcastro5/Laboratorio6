# Laboratorio 6
1. OBJETIVOS 

   Objetivo general
   
   * Analizar y comprobar de forma teorica y experimental veracidad que tiene el Teorema de Maxíma Transferencia de Potencia, como este se relaciona directamente con una resistencia Rl  y como se comporta al tener una resistencia interna similar a la resistencia de la fuente, esto se llevara a cabo mediante el desarrollo del presente laboratorio que abordará temas conocidos en la asignatura aplicado en un circuito eléctrico mixto planteado por el tutor de la asignatura, cabe recalcar que el presente circuito ya ha sido resuelto mediante un simulador virtual por lo que se espera resultados similares, se utilizara Tinkerkad y se establecera el porcentaje de error que tiene el metodo con respecto a los datos obtenidos mediante la simulacion.
 

   Objetivos específicos
   
   * Identificar el circuito electrico y elaborar un circuito simplificado.
   * Comprender la relacion de la resistencia de carga y la resistencia Thevenin
   * Conocer la resistencia equivalente o la resistencia Thevenin y como estas interactúa con la RL en dicho circuito.
   * Comparar todas las resistencias y obtener datos para el calculo de la maxima transferenci de potencia
   * Identificar la maxima transferencia de potencia y emitir en resultados el porcentaje de error.
   
2. MARCO TEORICO

   ![](https://github.com/jlcastro5/Laboratorio6/blob/9bb494dd060e5fad889899d3800de6e52ef50b14/LABOA3.jpeg)


3. EXPLICACION DEL PROCEDIMIENTO

   Primeramente analizamos nuestro ejercicio y planteamos lo siguiente:
   Armamos el circuito mostrado en la figura1. Utilizando laboratorio virtual tinkercad para realizar las representacion adecuada.

   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/Circuito.PNG)
   
   *Figura 1. Circuito esquematico*
   
   Armamos el circuito en nuestro protoboard mostrado en la figura 2. Para realizar el procedimiento establecido.

   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/Protoboard.PNG)
   
   *Figura 2. Circuito en protoboard*
   
   Tomamos en cuenta el teorema de la maxima transferencia de potencia establece que, dada una fuente, con una resistencia de fuente fijada de antemano, la resistencia de carga que maximiza la transferencia de potencia es aquella con un valor óhmico igual a la resistencia de fuente.
   En el cual nuestras resistencia en analizar en este teorema son las siguientes
   
   R1=220,R2=470,R3=680,R4=820,R5=1000,R6=1500,R7=1800,R8=2200,R9=3900,R10=4700 
   
   Datos del circuito simplificado es que tenemos una fuente de 15v y una resistencia de 1.2k ohm, en el cual la resistencia RL , analizaremos con cada resistencia para comprobar el teorema y mediante dos multimetros medideremos la corriente y voltaje de cada resistencia conectado al circuito simplficado.
   
   En las siguientes figuras 3-12 son mediciones respectivamente de la corriente y voltaje de cada una de las resistencias 
   
   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/R220.PNG)
   
   *Figura 3. Resistencia de 220.*

   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/R470.PNG)
   
    *Figura 4. Resistencia de 470.*
   
   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/R680.PNG)
   
    *Figura 5. Resistencia de 680.*
   
   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/R820.PNG)
   
    *Figura 6. Resistencia de 820.*

   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/R1K.PNG)
   
    *Figura 7. Resistencia de 1000.*

   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/R1.5.PNG)
   
    *Figura 8. Resistencia de 1500.*
   
   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/R1.8K.PNG)
   
    *Figura 9. Resistencia de 1800.*
   
   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/R2.2K.PNG)
   
    *Figura 10. Resistencia de 2200.*
   
   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/R3.9K.PNG)
   
   *Figura 11. Resistencia de 3900.*
   
   ![](https://github.com/jlcastro5/Laboratorio6/blob/9bb494dd060e5fad889899d3800de6e52ef50b14/R4.7K.PNG)
   
   *Figura 12. Resistencia de 4700.*
    
4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

   Una vez obteniendo nuestras mediciones y tomando en cuentra la teoria de maxima tranferencia de potencia, llenamos los datos respectivamente en la tabla1. en el cual colocaremos los valores de las intensidades y voltajes medido por el multimetro, con cada resistencia respectivamente.

   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/Circuito.PNG)
   
   *Figura 1. Circuito esquematico*
   
   Para este informe relizamos el siguiente analisis mediante la formula P = I^2*RL 
  
   Encontes para encontrar la intensidad mediante calculo hacemos una suma de la resistencia establecida con cada una de las resistencias, para encontrar una    
   RT(resistencia total), en el cual aplicaremos la ley de ohm, para encontrar la intensidad de cada circuito cambiando si RL, correspondient mostrado en la figura 13.

   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/Intesindades.PNG)
   
   *Figura 13. Intesidades*
   
   Luego de obtener las intensidades colocamos los valores en la formula P=I^2*RL para encontrar la potencia que pasa por cada resistencia prevista en el circuito 
   simflicado, para locual dichos valores colocaremos en la tabla1.
   
   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/Potencia.PNG)
   
   *Figura 14. potencia*
   
   Los datos de las anteriores potencias son obtenidas mediante calculo, ahora la potencia mostrado en la figura 15, son obtenidos con los valores medidos por el 
   multimetro y colocados en la tabla 1.

   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/PotenciaMultimetro.PNG)
   
   *Figura 15. Potencia teorica*
   
   TABLA DE DATOS
   
   En la siguiente tabla colocamos valores medidos por el multimetro tanto la corriente y su voltaje y respectivamente con el proceso adecuado encontramos su potencia
   para analizar la maxima tranferencia de potencia.
   
   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/Tabla6.1.PNG)
   
   *Tabla 1. Datos obtenidos en el simulador Tinkercad*
   
   CALCULO DE ERROR
   
   En el calculo de error de las potencia tanto con valores medidos con el multimetro y la potencia con valores calculados la cual su diferencia de error es mostrado
   en la figura 16.
   
   ![](https://github.com/jlcastro5/Laboratorio6/blob/f57156e79eac5cbe2fdc8aea7f24c8ddef4f9643/CalculoError.PNG)
   
   *Figura 16. Calculo de error potencia*
   
   **PREGUNTAS**
   *Cumple el teorema de la maxima tranferencia de potencia?
   
   
   
   
   Cual es la potencia maxima en RL ?
   
   46.51 mW
   
   Para que valor de RL se obtiene la MTP? 
   
   1000Ω
   
   


5. VIDEO

    https://www.youtube.com/watch?v=EvEktHmMQ_E

6. CONCLUSIONES

     *	El teorema de Thevenin han permitido obtener buenos resultados, entre los datos obtenidos mediante el desarrollo teórico y la simulación, mismos que fueron recopilados desde tinkercad. Considerando que los elementos son ideales, podemos concluir que los datos obtenidos en este circuito eléctrico a partir del teorema de Thevenin son precisos, llegando a tener 99.9% de exactitud con respecto a la corriente y un 99.6% de exactitud en el voltaje, por lo que concluimos que el método es muy fiable para resolver este tipo de circuitos eléctricos.

7. BIBLIOGRAFÍA 

   Latam, M. (2020, 6 julio). Leyes de Kirchhoff. Mecatrónica LATAM. https://www.mecatronicalatam.com/es/tutoriales/teoria/leyes-de-kirchhoff/
 
   Floyd,T. L. (2007). Principios de circuitos electricos. Mexico: Octava Edicion.
 
   Charles K & Sadiku M. (2006).Fundamentos de Circuitos eléctricos: Tercera Edición. 
