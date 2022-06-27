# INFORME TAREA 4
## OBJETIVO GENERAL

Comprender el funcionamiento y composición de los circuitos en serie-paralelo, por medio de análisis, conversiones de fuentes de voltaje y corriente, y la aplicación de teoremas como: Superposición, Thévenin, Norton y Transferencia de potencia máxima, por medio de la investigación en fuentes confiables, resolución de ejercicios de los temas antes previstos y la elaboración de un informe explicando los temas, para así lograr tener una visión clara del funcionamiento de circuitos en serie-paralelo, como las distintas mediciones y relaciones dentro de un circuito serie-paralelo, así como los teoremas y conversiones necesarias para calcular sus componentes.

## OBJETIVOS ESPECÍFICOS: 

-	Definir que es un circuito en serie-paralelo.
-	Demostrar como se calculan las resistencias y divisores de voltaje y corriente, dentro de un circuito serie-paralelo.
-	Explicar que son las fuentes de voltaje y corriente, y su conversión.
-	Explicar los teoremas de Superposición, Thevenin, Norton y Transferencia de potencia máxima.
-	Determinar que son los circuitos Delta y Y, y su conversión.

## MARCO TEÓRICO

### CIRCUITO SERIE-PARALELO

Los circuitos en serie-paralelo, también son conocidos como circuitos mixtos, los cuales se caracterizan por que es una combinación de circuitos en serie y en paralelo, es decir, si los elementos de un circuito están conectados en serie y otros en paralelo, sería un circuito eléctrico mixto.

Las características del Circuito Mixto son las siguientes:

•	Se caracteriza por estar compuesta por la combinación de circuitos en serie y paralelo.
•	El voltaje, varía dependiendo de la caída de tensión entre cada nodo.
•	La intensidad de la corriente varía dependiendo de la conexión.
•	Existen dos fórmulas para calcular la resistencia total del circuito mixto.

Ejemplo de circuito serie-paralelo:

![image](https://user-images.githubusercontent.com/105565683/175838793-d7d51cc0-6339-4a96-b39d-c8e2796d4733.png)

#### RESISTENCIA TOTAL

Para poder comprender correctamente como funciona un circuito en serie-paralelo, es muy útil comprender como se calcula la resistencia total, puesto que, la resistencia total se calcula como:

![image](https://user-images.githubusercontent.com/105565683/175838828-98573d01-60b1-488c-8ea9-61c57c96a5b1.png)

Cabe recalcar que para poder determinar que partes del circuito están en serie o paralelo, es necesario tener en cuenta la dirección de la corriente y la parte del circuito analizado, de la misma forma, en algunos casos es conveniente redibujar el circuito, para tener una mejor comprensión.

### DIVISORES DE VOLTAJE Y CORRIENTE

#### DIVISOR DE CORRIENTE

Para calcular la corriente total de un circuito en serie-paralelo se utiliza ley de ohm.

![image](https://user-images.githubusercontent.com/105565683/175838872-82dba79b-1b53-42ed-af94-474d5c7f9f6f.png)

Para calcular la corriente en una parte del circuito en específico, se usa un divisor de corriente, el cual se utiliza en las partes en paralelo del circuito, para ver la corriente que sale de un resistor.

![image](https://user-images.githubusercontent.com/105565683/175838881-3e8d24c3-54aa-458b-bde1-1e62fcce6681.png)

#### DIVISOR DE VOLTAJE

Para calcular el voltaje total de un circuito en serie-paralelo, solo se calcula el voltaje en serie, porque en paralelo, el voltaje es el mismo para cada resistor.

![image](https://user-images.githubusercontent.com/105565683/175838907-0084b6af-15b4-45c5-be7b-bffcb7341c07.png)

Para calcular el voltaje individual en un resistor en paralelo solo se utiliza la ley de ohm.

![image](https://user-images.githubusercontent.com/105565683/175838918-102045c2-3428-4fca-bc08-1002ced73d9b.png)

Para calcular el voltaje individual en un resistor en serie se utiliza divisor de voltaje, para poder calcular el voltaje de un resistor.

![image](https://user-images.githubusercontent.com/105565683/175838927-4f09d021-c313-41e7-baf4-930579bc73fe.png)

Esto sirve también para calcular el voltaje de salida, con o sin carga de una parte del circuito, el voltaje de salida se representa así:

##### Sin carga:

![image](https://user-images.githubusercontent.com/105565683/175838940-29610452-6351-461d-bf89-835ee8cb3dd7.png)

##### Con carga:

![image](https://user-images.githubusercontent.com/105565683/175838952-c37f0a73-5648-4519-9523-a188b6e894b0.png)

Para calcular el voltaje de salida sin carga se calcula el divisor de voltaje entre dos resistores en serie, basándose en la dirección de la corriente.

![image](https://user-images.githubusercontent.com/105565683/175838963-27de41c5-0366-4ed3-b938-c82fb282a5cf.png)

Para calcular el voltaje de salida con carga se calcula el divisor de voltaje entre todos los resistores, basándose en la dirección de la corriente.

![image](https://user-images.githubusercontent.com/105565683/175838980-f9eb087f-0bb9-465e-bde9-3adeb6a687ef.png)

### EFECTO DE CARGA DE UN VOLTÍMETRO (MEDICIÓN REAL)

Cuando un voltímetro se conecta a un circuito, su resistencia interna aparece en paralelo, es decir, que esta afecta a la medida real del voltaje, porque siempre existirá una variación dependiendo del voltímetro. Por ejemplo:

![image](https://user-images.githubusercontent.com/105565683/175838992-3b6d85a3-9495-46ed-933d-dff68fc1b06c.png)

De forma que para calcular el voltaje real de una resistencia solo su calcula teniendo en cuenta la resistencia interna y usando un divisor de voltaje:

![image](https://user-images.githubusercontent.com/105565683/175839007-8165a68a-9327-45f5-8651-6bdb66ee3baa.png)

### REDES ESCALERA

Una red escalera es esta:

![image](https://user-images.githubusercontent.com/105565683/175839025-d29d5dce-5b57-4ced-a9e4-7e7db186f675.png)

Para calcular la corriente y voltaje de un circuito en serie se realiza de la misma forma de un circuito en serie-paralelo, pero sirve para analizar un circuito en serie-paralelo, por medio del calculo de la resistencia en una zona específica de forma que:

![image](https://user-images.githubusercontent.com/105565683/175839028-341a11a1-2c35-440b-9c62-90d5dca298e8.png)

La resistencia total se calcularía en serie de forma: 

![image](https://user-images.githubusercontent.com/105565683/175839046-ed00c303-011d-43ce-8f60-44759bee6c54.png)

Para calcular la resistencia en cualquier nodo para reducirlo de forma simple analizamos en el sentido de la corriente, por ejemplo, para el nodo B R4 esta en paralelo con R5 y R6, y estos están en serie, y se calcula así:

![image](https://user-images.githubusercontent.com/105565683/175839069-a2cbdd91-f283-44e4-87c3-df60cda64baa.png)

Para las redes en escalera el proceso normal es reducir el circuito calculando las resistencias totales de casa sección del circuito.

### PUENTE DE WHEATSTONE 

Es un circuito con una configuración normalmente de: cuatro resistores y una fuente de voltaje de cd entre los puntos superior e inferior del “diamante”.

![image](https://user-images.githubusercontent.com/105565683/175839086-7825ef18-8867-4c3c-9b0b-681f39d3d7dc.png)

Existen dos formas en que puede estar:

#### Equilibrado:

![image](https://user-images.githubusercontent.com/105565683/175839094-e36b0307-d637-4a2f-9e28-e2a0862481c0.png)

#### Desequilibrado:

![image](https://user-images.githubusercontent.com/105565683/175839101-230cef5c-36a3-4279-aa4f-82458a288861.png)

### FUENTE DE VOLTAJE

Una fuente de voltaje es un dispositivo que tiene dos terminales encargadas de generar un voltaje de salida, independientemente de las cargas que reciba, se representa asi:

![image](https://user-images.githubusercontent.com/105565683/175839120-7c5b7cdc-9d5d-43ed-bad3-be267f438b04.png)

### FUENTE DE CORRIENTE

Una fuente de corriente es un equipo que suministra corriente eléctrica a una carga, se representa asi:

![image](https://user-images.githubusercontent.com/105565683/175839131-cc5581fd-1122-4529-b1ea-900c8f652b97.png)

### CONVERSIÓN DE FUENTE

Esta es una técnica para el análisis de un circuito, principalmente sirve al momento de hacer cálculos, cosiste en convertir una fuente de voltaje en una fuente de corriente o viceversa.

#### DE VOLTAJE A CORRIENTE

![image](https://user-images.githubusercontent.com/105565683/175839163-cd80d73f-7b28-4f43-8fb1-5f9e16afd7c2.png)

#### DE CORRIENTE A VOLTAJE

![image](https://user-images.githubusercontent.com/105565683/175839172-8e7f38f4-b7f5-4523-995b-86131d21866c.png)

### TEOREMA DE SUPERPOSICION

El método de superposición es una forma de determinar corrientes en un circuito con múltiples fuentes dejando una fuente a la vez y reemplazando las demás fuentes por sus resistencias internas. Siendo que para una fuente de voltaje ideal es cero (circuito cerrado), y para una fuente de corriente ideal es infinito (circuito abierto).

El teorema dice que: En cualquier rama dada de un circuito con múltiples fuentes, la corriente puede calcularse al determinar en esa rama particular las corrientes producidas por cada fuente que actúa sola, con todas las demás fuentes reemplazadas por sus resistencias internas. La corriente total en la rama es la suma algebraica de las corrientes individuales presentes en dicha rama.

Sus pasos son:

![image](https://user-images.githubusercontent.com/105565683/175839200-f2dc47a3-282e-4812-a53c-c54fb022b4cc.png)

### TEOREMA DE THEVENIN 

La forma Thevenin equivalente de cualquier circuito resistivo de dos terminales consta de una fuente de voltaje equivalente (VTH) y una resistencia equivalente (RTH).

![image](https://user-images.githubusercontent.com/105565683/175839218-fe907368-7a6b-4ecb-8a2b-4644ee804d7d.png)

-	En un circuito eléctrico, el voltaje equivalente de Thevenin (VTH) es el voltaje de circuito abierto (sin carga) presente entre dos terminales de salida.
-	La resistencia equivalente de Thevenin (RTH) es la resistencia total que aparece entre dos terminales en un circuito dado que tiene todas las fuentes reemplazadas por sus resistencias internas.

Sus pasos son:

•	Paso 1. Abrir las dos terminales (eliminar cualquier carga) entre las que se desea encontrar el circuito equivalente de Thevenin. 
•	Paso 2. Determinar el voltaje (VTH) entre las dos terminales abiertas. 
•	Paso 3. Determinar la resistencia (RTH) entre las dos terminales abiertas con todas las fuentes reemplazadas por sus resistencias internas (fuentes de voltaje ideales en cortocircuito y fuentes de corriente ideales abiertas). 
•	Paso 4. Conectar VTH y RTH en serie para producir el equivalente de Thevenin completo del circuito original. 
•	Paso 5. Reemplazar la carga eliminada en el paso 1 entre las terminales del circuito equivalente de Thevenin. Ahora se pueden calcular la corriente y el voltaje que haya en la carga utilizando solamente la ley de Ohm. Tienen el mismo valor que la corriente y el voltaje presentes en la carga del circuito original.

![image](https://user-images.githubusercontent.com/105565683/175839236-b87c6c22-1e0b-4b8f-b0eb-81f4ffb86cfb.png)

### TEOREMA DE NORTON

El teorema de Norton es un método empleado para simplificar un circuito lineal de dos terminales en un circuito equivalente con sólo una fuente de corriente en paralelo con un resistor.

![image](https://user-images.githubusercontent.com/105565683/175839256-9960d0bc-a362-4085-9279-1266df1c3cfd.png)

La corriente equivalente de Norton (IN) es la corriente que se encuentra en cortocircuito entre dos terminales de salida de un circuito.

![image](https://user-images.githubusercontent.com/105565683/175839267-e031aab6-a03d-45b1-880d-c21d5cc42f43.png)

La resistencia equivalente de Norton, RN, es la resistencia total que aparece entre dos terminales de salida en un circuito dado que tiene todas las fuentes reemplazadas por sus resistencias internas.

![image](https://user-images.githubusercontent.com/105565683/175839277-cf6d6918-497b-4b30-8ef8-edf1bc689724.png)

Sus pasos son:

•	Paso 1. Poner con cortocircuito las dos terminales entre la cuales se desea determinar el circuito equivalente de Norton. 
•	Paso 2. Determinar la corriente (IN) a través de las terminales puestas en cortocircuito. 
•	Paso 3. Determinar la resistencia (RN) entre las dos terminales abiertas con todas las fuentes reemplazadas por sus resistencias internas (fuentes de voltaje ideales en cortocircuito y fuentes de corriente ideales abiertas). RN=RTH. 
•	Paso 4. Conectar IN y RN en paralelo para producir el circuito equivalente de Norton completo para el circuito original.

### TEOREMA DE TRANSFERENCIA DE POTENCIA MÁXIMA

Para una fuente de voltaje dada, la potencia máxima se transfiere desde una fuente hasta una carga cuando la resistencia de la carga es igual a la resistencia interna de la fuente.

La resistencia de la fuente, RS, de un circuito es la resistencia equivalente vista desde la terminal de salida utilizando el teorema de Thevenin.

![image](https://user-images.githubusercontent.com/105565683/175839304-ab80cdac-2bf2-4d4e-893f-f15286173bfa.png)

### CIRCUITOS DELTA Y Y

![image](https://user-images.githubusercontent.com/105565683/175839312-d4d0b7e6-b01e-46ae-8a44-b1d11ff619e4.png)

#### CONVERSIÓN DELTA A Y

Cada resistor localizado en la Y es igual al producto de los resistores incluidos en dos ramas delta adyacentes, dividido entre la suma de los tres resistores en delta.

![image](https://user-images.githubusercontent.com/105565683/175839328-9b800d8a-5a0b-4de4-b055-5ce96d5d33d8.png)

![image](https://user-images.githubusercontent.com/105565683/175839346-1b5ca77e-57f5-4cdf-9322-4f8004310bc2.png)

#### CONVERSIÓN DE Y A DELTA

Cada resistor incluido en la delta es igual a la suma de todos los posibles productos de resistores Y tomados dos a la vez, y divididos entre el resistor Y opuesto.

![image](https://user-images.githubusercontent.com/105565683/175839363-656642bb-f7c0-4df6-acc2-9113dd491155.png)

![image](https://user-images.githubusercontent.com/105565683/175839378-8cf72a2f-57f6-4c7a-a62f-a5c544851b30.png)

## EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

Resolución de ejercicios pares de los capítulos 7 y 8 del libro Principios de Circuitos Eléctricos - Floyd.

### CAPITULO 7 CIRCUITOS EN SERIE-PARALELO:

2. Visualice y trace los siguientes circuitos en serie-paralelo:

![image](https://user-images.githubusercontent.com/105565683/175537688-f217fde5-eabd-441c-8ea1-4e66f05e7b54.png)

![image](https://user-images.githubusercontent.com/105565683/175537738-5f31faa6-430c-43be-b0d1-87c9c21e098a.png)

4. En cada uno de los circuitos de la figura 7-63, identifique las relaciones en serie-paralelo de los resistores vistas desde la fuente

![image](https://user-images.githubusercontent.com/105565683/175537764-2ea66793-0e2a-46f8-9031-aeac9e5a1127.png)

![image](https://user-images.githubusercontent.com/105565683/175537806-352199f1-493f-469a-80f6-563bc8ccd7f3.png)

6. Desarrolle un diagrama esquemático de la tarjeta de circuito impreso de doble cara mostrada en la figura 7-65, y marque los valores de resistor.

![image](https://user-images.githubusercontent.com/105565683/175537838-ac8cc9db-5369-485f-8199-b9d528a2cebf.png)

![image](https://user-images.githubusercontent.com/105565683/175537857-f0b2b132-c2d8-41ca-b5c0-65a87c5f325e.png)

8. Un cierto circuito se compone de dos resistores en paralelo. La resistencia total es de 667 Ω. Uno de los resistores es de 1.0 kΩ. ¿Cuál es el otro resistor?

![image](https://user-images.githubusercontent.com/105565683/175537932-70d8cc12-f69c-4eb1-a333-19d6adcc8902.png)

10. Repita el problema 9 para cada uno de los circuitos mostrados en la figura 7-63. (Determine la resistencia total)

![image](https://user-images.githubusercontent.com/105565683/175538706-6eeb53d2-adaf-4523-aa3f-bea5839b3bcf.png)

![image](https://user-images.githubusercontent.com/105565683/175538394-08bd5907-5d59-4291-bf13-f836677ac81b.png)

![image](https://user-images.githubusercontent.com/105565683/175538440-e91aeaf3-b2bc-4403-a156-9fb65ca2428c.png)

![image](https://user-images.githubusercontent.com/105565683/175538481-a27a95d7-1e39-4c98-a0b1-a79d41a1c55c.png)

12. Determine la corriente a través de cada resistor en cada circuito de la figura 7-63; luego calcule cada caída de voltaje. 

![image](https://user-images.githubusercontent.com/105565683/175538518-284612be-5dd6-4928-97c6-10ed905ddbfc.png)

![image](https://user-images.githubusercontent.com/105565683/175538760-c873e3cc-2213-41c6-a950-3fbceba47f9e.png)

![image](https://user-images.githubusercontent.com/105565683/175538794-acaa8eba-e97d-4ecf-aeee-eb1c843f5b35.png)

![image](https://user-images.githubusercontent.com/105565683/175538910-384eb646-33f8-4c2b-8ceb-0acfce9400cc.png)

![image](https://user-images.githubusercontent.com/105565683/175538955-36bd5614-0392-447d-b34e-2a31e5611cde.png)

14. Determine la resistencia entre A y B en la figura 7-67 sin la fuente.

![image](https://user-images.githubusercontent.com/105565683/175538991-9e9c2716-26bc-4f2b-b14a-4c28ddaa4821.png)

![image](https://user-images.githubusercontent.com/105565683/175539050-962ba551-c746-4da1-8c49-6b0415946628.png)

16. Determine el voltaje en cada nodo con respecto a tierra en la figura 7-68.

![image](https://user-images.githubusercontent.com/105565683/175539092-da886114-cd2b-4f8a-b7dc-9a7978d84747.png)

![image](https://user-images.githubusercontent.com/105565683/175539131-9e46e79c-55db-42e3-aa93-b9cf2d9e409b.png)

![image](https://user-images.githubusercontent.com/105565683/175539164-78c331e4-bf43-4652-a0b3-d608a0678dec.png)

18. Determine la resistencia del circuito mostrado en la figura 7-67 como se ve desde la fuente de voltaje

![image](https://user-images.githubusercontent.com/105565683/175539191-f01cb43a-a919-4028-8441-55132e5b18ea.png)

![image](https://user-images.githubusercontent.com/105565683/175539222-13a37b33-be02-4182-9860-b7cbcee696a0.png)

20. Determine el voltaje, VAB, en la figura 7-69.

![image](https://user-images.githubusercontent.com/105565683/175539253-2c1ff8fd-6cd3-4af4-80d1-3824b069de60.png)

![image](https://user-images.githubusercontent.com/105565683/175539300-5736ec7d-19f6-4747-9bb9-c3d454c8d292.png)

![image](https://user-images.githubusercontent.com/105565683/175539344-9feaed23-4da6-4d4f-9512-3d48c6f452f4.png)

22. En la figura 7-71, determine la resistencia entre el nodo A y cada uno de los demás nodos (RAB, RAC, RAD, RAE, RAF, y RAG).

![image](https://user-images.githubusercontent.com/105565683/175539386-28fba404-d21f-494b-b245-5f90ac62d292.png)

![image](https://user-images.githubusercontent.com/105565683/175539475-2edbeb2a-c937-4a36-a858-7b9067c83f1c.png)

![image](https://user-images.githubusercontent.com/105565683/175539527-1acb7229-6ac2-4e6e-8935-e5a798b8b870.png)

24. Determine el valor de cada resistor mostrado en la figura 7-73.

![image](https://user-images.githubusercontent.com/105565683/175539573-8152394b-7d75-4f00-a540-70baebafa454.png)

![image](https://user-images.githubusercontent.com/105565683/175539624-abb4b9a4-47ea-415f-ad82-1632b90c099c.png)

![image](https://user-images.githubusercontent.com/105565683/175539674-efe25846-4a3d-4316-850e-884cc6b8fefc.png)

26. La salida de una batería de 12 V se divide para obtener dos voltajes de salida. Se utilizan tres resistores de 3.3 kΩ para proporcionar dos tomas. Determine los voltajes de salida. Si se conecta una carga de 10 kΩ a la más alta de las salidas, ¿cuál será su valor con carga?

Grafico:

![image](https://user-images.githubusercontent.com/105565683/175539727-bec108be-8f87-42ce-aaa5-242f0f89319b.png)

![image](https://user-images.githubusercontent.com/105565683/175539784-3d3f0f95-952b-4df9-b620-466a92211ae5.png)

28. En la figura 7-74, determine el voltaje de salida sin carga entre las terminales de salida. Con una carga de 100 kΩ conectada de A a B, ¿cuál es el voltaje de salida?

![image](https://user-images.githubusercontent.com/105565683/175539839-88759c23-60d2-4d59-93e1-edf26bf8b330.png)

![image](https://user-images.githubusercontent.com/105565683/175539930-6bde667d-010c-437e-ad6b-21536913b0ba.png)

30. En la figura 7-74, determine la corriente continua extraída de la fuente sin carga entre las terminales de salida. Con una carga de 33 kΩ, ¿cuál es la corriente extraída?

![image](https://user-images.githubusercontent.com/105565683/175539978-ae8b6fc6-1856-4291-b938-8ccc0476cd98.png)

![image](https://user-images.githubusercontent.com/105565683/175540032-3361362d-441a-4a55-a187-4669525211ed.png)

32. El divisor de voltaje de la figura 7-75 tiene una carga controlada por interruptor. Determine el voltaje en cada toma (V1, V2 y V3) para cada posición del interruptor.

![image](https://user-images.githubusercontent.com/105565683/175540067-0be328d5-3c05-46a1-b18f-628331d2ec4c.png)

![image](https://user-images.githubusercontent.com/105565683/175541462-e81a93b9-7e27-4fa6-80e2-537f9e39827e.png)

![image](https://user-images.githubusercontent.com/105565683/175541497-37da8064-3e5a-42ea-8ac2-ef200fbcc17e.png)

34. Diseñe un divisor de voltaje que produzca una salida de 6 V sin carga y un mínimo de 5.5 V entre los extremos de una carga de 1.0 kΩ. El voltaje de fuente es de 24 V y la corriente extraída sin carga no debe exceder de 100 mA.

![image](https://user-images.githubusercontent.com/105565683/175541567-d9cf3645-1d37-48a4-b69d-bb621227c91b.png)

![image](https://user-images.githubusercontent.com/105565683/175541608-2ba6292b-624b-4f98-87b2-17656e1fc5d6.png)

36. Determine la resistencia interna de un voltímetro de 20,000 Ω/V en cada uno de los siguientes ajustes de intervalo. 

![image](https://user-images.githubusercontent.com/105565683/175541673-fc2b0fc3-87fd-4623-9fea-3519fff1af8e.png)

38. Repita el problema 37 si se utiliza el voltímetro para medir voltaje entre los extremos de R4 en el circuito de la figura 7-62(b)

![image](https://user-images.githubusercontent.com/105565683/175541716-2d5cafec-c38f-4ea8-9545-5db226bff994.png)

![image](https://user-images.githubusercontent.com/105565683/175541766-936c6f9d-6305-4fd0-9f81-fb51160430c5.png)

![image](https://user-images.githubusercontent.com/105565683/175541799-9efbbf92-b750-4d59-9277-d2e7f19413a4.png)

40. Determine la resistencia total y el voltaje en los nodos A, B y C de la red en escalera mostrada en la figura 7-78.

![image](https://user-images.githubusercontent.com/105565683/175541915-1b113114-2668-44d7-964c-5dcc2db885b2.png)

![image](https://user-images.githubusercontent.com/105565683/175542038-6173eccb-abef-4223-86e4-9086f26b7b1f.png)

![image](https://user-images.githubusercontent.com/105565683/175542096-c340cc47-4ce8-4f4a-aa6c-87f0af66b338.png)

42. En la figura 7-79, ¿cuál es el voltaje entre los extremos de cada resistor con 10 V entre A y B?

![image](https://user-images.githubusercontent.com/105565683/175542134-7ec802ef-1389-48b5-9edf-c53e140ab8f6.png)

![image](https://user-images.githubusercontent.com/105565683/175542161-23262aaa-691e-4493-bac6-9325ffaa4854.png)

![image](https://user-images.githubusercontent.com/105565683/175542237-5974d88d-ab56-41a6-a73d-5f061005bd2b.png)

![image](https://user-images.githubusercontent.com/105565683/175542271-3106ce69-638c-43e2-b37e-d981025d9781.png)

44. Determine VSALIDA para la red R/2R en escalera mostrada en la figura 7-81 para las siguientes condiciones: 

![image](https://user-images.githubusercontent.com/105565683/175542293-6eacad23-e5b9-4592-b2f1-84469c39cdeb.png)

![image](https://user-images.githubusercontent.com/105565683/175542341-38a0dcbf-5c5f-4b83-af5d-5026cc62b000.png)

46. Se conecta un resistor de valor desconocido a un circuito puente Wheatstone. Los parámetros del puente en equilibrio se establecen como sigue: RV = 18 kΩ y R2/R4 = 0.02. ¿Cuál es RX?

![image](https://user-images.githubusercontent.com/105565683/175542382-9195454e-0bc6-44c0-948c-0f0ffd4ad53d.png)

48. Determine el voltaje de salida para el puente desequilibrado mostrado en la figura 7-83 a una temperatura de 60° C. La característica de resistencia según la temperatura del termistor se muestra en la figura 7-60.

![image](https://user-images.githubusercontent.com/105565683/175542416-cf0e4336-1b58-47df-b2ed-655a31edb8d9.png)

![image](https://user-images.githubusercontent.com/105565683/175542491-10818ec0-fb99-4056-b68c-0b05d2a4e798.png)

![image](https://user-images.githubusercontent.com/105565683/175542529-2021ce4c-6c26-4db4-969a-416640e64661.png)

50. ¿Son correctas las lecturas del medidor mostrado en la figura 7-85?

![image](https://user-images.githubusercontent.com/105565683/175542560-9640a28f-3ca4-49b1-aa76-6631efd36664.png)

Circuito redibujado:

![image](https://user-images.githubusercontent.com/105565683/175542586-0ab98154-8437-48e8-9961-e8cad3fa59c4.png)

![image](https://user-images.githubusercontent.com/105565683/175542664-cb2fb502-0b7e-4232-a703-345c34c5b556.png)

52. Vea los medidores ilustrados en la figura 7-87 y determine si hay una falla en el circuito. Si la hay, identifíquela.

![image](https://user-images.githubusercontent.com/105565683/175542686-940cced3-9419-4609-adcc-a12ff7fc5514.png)

Circuito redibujado:

![image](https://user-images.githubusercontent.com/105565683/175542747-694d00ac-4509-4df0-9483-8261a9e50e9d.png)

![image](https://user-images.githubusercontent.com/105565683/175542786-171ba8a5-01bd-4942-8df5-aacd3e4af9ec.png)

54. Si en la figura 7-89 R2 se abre, ¿qué voltajes se leerán en los puntos A, B y C?

![image](https://user-images.githubusercontent.com/105565683/175542845-9c8b9a1b-de0f-4571-8b79-905552d45a7e.png)

### CAPITULO 8 TEOREMAS DE CIRCUITOS Y CONVERSIONES:

2. Convierta las fuentes de voltaje prácticas de la figura 8-67 en fuentes de corriente equivalentes.

![image](https://user-images.githubusercontent.com/105565683/175542993-696772f2-dc69-4f7d-a8a4-fbd7a4fd1228.png)

![image](https://user-images.githubusercontent.com/105565683/175543015-0b9dd364-89b8-4ea6-a0e9-a9477d05bd1a.png)

4. Trace los circuitos equivalentes de fuentes de voltaje y corriente para la batería tipo D del problema 3.

![image](https://user-images.githubusercontent.com/105565683/175543067-1c250a69-2b8e-4462-ab5d-488b4081f971.png)

6. Convierta las fuentes de corriente prácticas de la figura 8-68 en fuentes de voltaje equivalentes.

![image](https://user-images.githubusercontent.com/105565683/175543132-4c82d66e-695d-4f69-b555-301b3c690eaf.png)

![image](https://user-images.githubusercontent.com/105565683/175543156-48f5b5dc-1607-4bed-8e02-8d6a92af724f.png)

8. Use el teorema de superposición para determinar la corriente a través, y el voltaje entre, los extremos de la rama R2 de la figura 8-69.

![image](https://user-images.githubusercontent.com/105565683/175543315-ee352327-152f-4b34-8af4-10c491b49da2.png)

Por el problema 7, sabemos que:

![image](https://user-images.githubusercontent.com/105565683/175543359-ce8971ec-b993-499d-b1d8-f6c0e274d368.png)

![image](https://user-images.githubusercontent.com/105565683/175543415-999f076c-57b3-4b92-b89b-194c94368ed2.png)

10. Con el teorema de superposición, determine la corriente de carga en cada uno de los circuitos mostrados en la figura 8-71.

![image](https://user-images.githubusercontent.com/105565683/175543496-b69c2a0b-390c-4092-9fb3-be25a27aea53.png)

Para el circuito a:

![image](https://user-images.githubusercontent.com/105565683/175697676-56719b1a-cc12-4317-8789-102d89f44913.png)

![image](https://user-images.githubusercontent.com/105565683/175697703-cd228655-7793-4134-8ed3-e9b00b3935ff.png)

Para el circuito b:

![image](https://user-images.githubusercontent.com/105565683/175697730-cc67a557-5a9d-40f0-a387-0d36b8cf4ef3.png)

![image](https://user-images.githubusercontent.com/105565683/175697754-01877088-82e1-44de-b553-80cbb67b6a7a.png)

12. Repita el problema 11 si R2 es de 10 kΩ.  En la figura 8-72 se muestra un circuito comparador. El voltaje de entrada, VENTRADA, se compara con el voltaje de referencia, VREFERENCIA, y se genera una salida negativa si VREFERENCIA > VENTRADA; de lo contrario es positiva. El comparador no carga a una u otra entrada. Si R2 es de 10 kΩ, ¿cuál es el intervalo del voltaje de referencia?

![image](https://user-images.githubusercontent.com/105565683/175697786-678b473e-2656-4f4b-b91e-3cca89326b00.png)

![image](https://user-images.githubusercontent.com/105565683/175697819-093ca443-64b9-4d23-b5c3-a8c3378c5f5d.png)

14. Los interruptores mostrados en la figura 8-74 se cierran en secuencia, SW1 primero. Determine la corriente a través de R4 después del cierre de cada interruptor.

![image](https://user-images.githubusercontent.com/105565683/175697840-cfc7b384-7e7a-425b-ac92-7521bedace22.png)

![image](https://user-images.githubusercontent.com/105565683/175697866-0f6fbacb-bf38-4140-9015-6eb171ceb0c5.png)

![image](https://user-images.githubusercontent.com/105565683/175697926-d357cd9d-2d9c-4be8-a3bb-ca7489c58717.png)

![image](https://user-images.githubusercontent.com/105565683/175697989-e3e73bc4-bcaf-4f25-8d3c-d25d3ef1bf7b.png)

![image](https://user-images.githubusercontent.com/105565683/175698044-38568024-2af2-42a3-915e-067d06183a55.png)

![image](https://user-images.githubusercontent.com/105565683/175698082-60632ce4-512d-4900-aba3-dc40ab4056af.png)

16. Para cada uno de los circuitos de la figura 8-76, determine el equivalente de Thevenin como se ve desde las terminales A y B.

![image](https://user-images.githubusercontent.com/105565683/175698105-e8126344-e6c0-4347-96b2-915b472d30fe.png)

![image](https://user-images.githubusercontent.com/105565683/175698152-65a2b152-071d-4885-8d0f-ee263c0f3445.png)

18. Con el teorema de Thevenin, determine el voltaje entre los extremos de R4 en la figura 8-78.

![image](https://user-images.githubusercontent.com/105565683/175698179-3f71f15d-6023-4ee6-8c44-576e2bd70ff1.png)

![image](https://user-images.githubusercontent.com/105565683/175698190-aea03244-b8fb-4e28-a70f-470bd2ff4217.png)

![image](https://user-images.githubusercontent.com/105565683/175698221-25567819-1ff4-4aaf-8fd2-31726530cde0.png)

![image](https://user-images.githubusercontent.com/105565683/175698245-df36eb3d-fa43-4720-91dc-2749f5429a5e.png)

20. Determine la corriente que se dirige al punto A cuando R8 es de 1.0 kΩ, 5 kΩ, y 10 kΩ en la figura 8-80.

![image](https://user-images.githubusercontent.com/105565683/175698264-81df26ed-3723-4136-af68-d964b4c71f87.png)

![image](https://user-images.githubusercontent.com/105565683/175698280-b8d8462f-d0b4-48bb-b5b8-6ba563f93f73.png)

![image](https://user-images.githubusercontent.com/105565683/175698323-39122eb1-0a5f-4cb6-87f4-30a6f574619f.png)

![image](https://user-images.githubusercontent.com/105565683/175698360-f632662a-6e72-4476-9d1e-cd9cacf6b30f.png)

22. Determine el equivalente de Thevenin del circuito mostrado en la figura 8-82 visto desde las terminales A y B

![image](https://user-images.githubusercontent.com/105565683/175698381-81907854-ef87-4d4f-86ec-209b1a52ce5c.png)

![image](https://user-images.githubusercontent.com/105565683/175698391-3289e68f-6f62-4452-86f7-fd4921faa31e.png)

![image](https://user-images.githubusercontent.com/105565683/175698435-df8c4248-b8fa-4834-9209-4278a43467d6.png)

24. Con el teorema de Norton, determine la corriente que circula a través del resistor de carga RL en la figura 8-77.

![image](https://user-images.githubusercontent.com/105565683/175698450-69b47f06-cd4c-4c43-b2bf-422b793ecb3c.png)

![image](https://user-images.githubusercontent.com/105565683/175698460-a9b9b61f-ace5-41eb-a2b3-717990bb26ad.png)

![image](https://user-images.githubusercontent.com/105565683/175698557-e77a994f-a03d-455a-9306-2e3d40b689ec.png)

26. Con el teorema de Norton, determine la corriente que circula a través de R1 en la figura 8-80 cuando R8 = 8 kΩ.

![image](https://user-images.githubusercontent.com/105565683/175698576-d6d306d4-6966-43ca-b47f-b074dd625b00.png)

![image](https://user-images.githubusercontent.com/105565683/175698588-86b882f9-aee3-45a2-bfa4-30a7d8d554db.png)

![image](https://user-images.githubusercontent.com/105565683/175698650-8e148b0a-52f4-4cd1-8f71-36fe8ab72592.png)

![image](https://user-images.githubusercontent.com/105565683/175698683-4b460859-9a25-4ca4-9252-a18419749737.png)

![image](https://user-images.githubusercontent.com/105565683/175698729-661bd095-02ac-418f-9780-2e496585c29e.png)

28. En la figura 8-83, reduzca el circuito entre las terminales A y B a su equivalente Norton.

![image](https://user-images.githubusercontent.com/105565683/175698748-53c11c04-b1b9-4cf9-bae9-e23586ccbba5.png)

![image](https://user-images.githubusercontent.com/105565683/175698763-1482b6e3-d4c6-48dc-957d-59147c07a0cb.png)

![image](https://user-images.githubusercontent.com/105565683/175698789-c6aea340-c406-4ead-bd5c-79806e065fe0.png)

30. En cada circuito mostrado en la figura 8-85, se tiene que transferir potencia máxima a la carga RL. Determine el valor apropiado de RL en cada caso.

![image](https://user-images.githubusercontent.com/105565683/175698992-c7a8fb36-3be7-4614-95b8-fe3ff3485245.png)

![image](https://user-images.githubusercontent.com/105565683/175699012-cdc00adc-ee3a-4d48-8e64-862fd7943d4b.png)

32. ¿Cuánta potencia se suministra a la carga cuando RL es un 10% más alta que su valor para transferencia de potencia máxima en el circuito de la figura 8-86?

![image](https://user-images.githubusercontent.com/105565683/175699034-e073fb39-2204-40a0-861f-85c8272ae92c.png)

![image](https://user-images.githubusercontent.com/105565683/175699043-af2d1fc5-79d4-46c5-92b1-25314ac9713b.png)

![image](https://user-images.githubusercontent.com/105565683/175699085-e46e4c1f-d6d6-4844-8e28-433f0d55e9c4.png)

![image](https://user-images.githubusercontent.com/105565683/175699251-70f758bc-943b-4226-85ed-12bff480d45e.png)

34. En la figura 8-88, convierta cada red delta en una red Y.

![image](https://user-images.githubusercontent.com/105565683/175699289-82cf021b-b0e6-4587-9583-11cc5f006734.png)

![image](https://user-images.githubusercontent.com/105565683/175699145-00b10262-625e-4e20-8f38-877beea05f3a.png)

36. Determine todas las corrientes que circulan en el circuito de la figura 8-90.

![image](https://user-images.githubusercontent.com/105565683/175699306-d19318e0-52fc-4a8d-a82d-4fe5d2e19c37.png)

![image](https://user-images.githubusercontent.com/105565683/175699316-f9a50035-fa1a-481c-aa32-b83390596c99.png)

![image](https://user-images.githubusercontent.com/105565683/175699363-b1904ed4-3fa7-42b8-8281-8c55b1fa432f.png)

## VIDEO



## CONCLUSIONES

-	Un circuito en serie-paralelo son aquellos que están conformados tanto por partes y componentes en serie y en paralelo dentro del circuito.
-	Para el cálculo de la resistencia total del circuito es necesario saber distinguir que partes del circuito en serie y en paralelo basándose en la dirección de la corriente del circuito.
-	Para el calculo de divisores de voltaje es necesario tener en cuenta que solo se puede realizar en un circuito en serie, y para el divisor de corriente es necesario hacer en un circuito en paralelo.
-	Una fuente de voltaje es aquella que suministra voltaje y una fuente de corriente es aquella que suministra corriente, para convertir de otra hay que seguir las leyes de ohm y hacer transformación de serie a paralelo dependiendo del caso.
-	El teorema de superposición consiste en eliminar una fuente del circuito para facilitar el cálculo de sus componentes.
-	El teorema de Thevenin consiste en la utilización de una fuente de voltaje equivalente y una resistencia equivalente.
-	El teorema de Norton es aquel en que se basa en simplificar un circuito lineal de dos terminales en un circuito equivalente con sólo una fuente de corriente en paralelo con un resistor.
-	El teorema de Transferencia de potencia máxima es aquel en que para una fuente de voltaje dada, la potencia máxima se transfiere desde una fuente hasta una carga cuando la resistencia de la carga es igual a la resistencia interna de la fuente.
-	El circuito Delta es aquel que se representa como un triangulo inverso, y el circuito Y es aquel que se representa como una Y, y para su conversión es necesario calcular las resistencias equivalentes.

## BIBLIOGRAFÍA 

acmax. (21 de Septiembre de 2020). acmax. Obtenido de acmax: https://acmax.mx/que-es-una-fuente-de-corriente

electronicaonline. (23 de Julio de 2021). electronicaonline. Obtenido de electronicaonline: https://electronicaonline.net/circuito-electrico/circuito-mixto/

Floyd, T. L. (2007). Principios de circuitos eléctricos. Monterrey: Pearson Education.

osakaelectronicsltda. (6 de Septiembre de 2021). osakaelectronicsltda. Obtenido de osakaelectronicsltda: https://osakaelectronicsltda.com/blog/recomendaciones/que-es-una-fuente-de-voltaje
