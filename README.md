# TAREA9

OBJETIVOS

Analizar circuitos RLC en serie y paralelo, su frecuencia, resolnancia y selectividad.
Aprender sobre los filtros pasivos, su uso, y variedad.

MARCO TEÓRICO (RESUMEN)

Dado que la reactancia inductiva y la reactancia capacitiva tienen efectos opuestos en el ángulo de fase del circuito, la reactancia total es menor que cualquier reactancia individual. Como se sabe, la reactancia inductiva hace que la corriente total se retrase con respecto al voltaje aplicado. Cuando son iguales, se cancelan y la reactancia total es cero. El término |XL - XC| es el valor absoluto de la diferencia de las dos reactancias.

Es decir, el signo del resultado se considera positivo independientemente de la reactancia más alta. Cuando XL es mayor que XC, el circuito es mayormente inductivo, y cuando XC es mayor que XL, el circuito es mayormente capacitivo. Esta sección examina los efectos combinados de las reactancias en función de la frecuencia. comenzando en una frecuencia muy baja, XC es alta, XL es baja y el circuito es principalmente capacitivo.

A medida que aumenta la frecuencia, XC disminuye y XL aumenta hasta llegar a un valor donde se eliminan XC XL y ambas reactancias, volviendo a un circuito puramente resistivo. Esta condición se llama resonancia en serie. A medida que aumenta la frecuencia, XL se vuelve más grande que XC y el circuito es principalmente inductivo. En un circuito RLC en serie, el voltaje a través del capacitor y el inductor siempre están desfasados ​​180° entre sí.

Por esta razón, VC y VL se restan entre sí, por lo que el voltaje combinado de L y C siempre es más bajo que el voltaje más alto en cualquiera de los componentes. La frecuencia a la que se produce la resonancia se denomina frecuencia resonante y se denota como fr. Para un circuito RLC en serie.

Zr=R

XL y XC se cancelan en la condición de resonancia. A la frecuencia de resonancia en serie , los voltajes entre las terminales de C y L son de igual magnitud porque las reactancias son iguales. La misma corriente fluye a través de los dos componentes porque están en serie . Dado que no hay caída de voltaje de A a B pero todavía hay corriente, la reactancia total debe ser cero.

Corriente y tensiones en un circuito RLC en serie A la frecuencia de resonancia en serie, la corriente es máxima . El voltaje a través de la resistencia, VR, sigue a la corriente y es máximo en resonancia y cero cuando f = 0 y cuando f = infinito. También se tratan la conductancia, la susceptancia y la admitancia de un circuito RLC en paralelo.

En circuitos RLC en paralelo a bajas frecuencias, la reactancia inductiva es menor que la reactancia capacitiva. Por lo tanto, el circuito es inductivo. Relaciones de corriente En un circuito RLC en paralelo, las corrientes que fluyen en las ramas capacitiva e inductiva siempre están desfasadas 180° entre sí . Además, la conversión de un circuito serie-paralelo en un circuito paralelo equivalente y la sintonización en un circuito paralelo considerado no ideal.

La equivalencia de circuito significa que, a una frecuencia dada, cuando se aplica el mismo valor de voltaje a ambos circuitos, fluye la misma corriente total en ambos circuitos y los ángulos de fase son los mismos. Básicamente, un circuito equivalente solo hace que el análisis de circuitos sea más conveniente. Condiciones para la sintonización en paralelo en un circuito no ideal La sintonización de un circuito LC ideal dispuesto en paralelo se analizó en la sección 17-6. Ahora considere la resonancia en el circuito del tanque en términos de la resistencia de la bobina.

Recuerde que el factor de calidad, Q, del circuito en resonancia es simplemente el factor Q de la bobina. En el circuito equivalente en paralelo, Rp está en paralelo con una bobina y un capacitor ideales, de modo que las ramas L y C actúan como un circuito tanque ideal cuya impedancia es infinita en resonancia. Por lo tanto, la impedancia total del circuito tanque no ideal en resonancia se expresa simplemente como la resistencia paralela equivalente. En un circuito RLC en paralelo, la corriente es mínima en la frecuencia resonante porque las corrientes inductiva y capacitiva se anulan entre sí.

Este comportamiento del circuito está relacionado con una característica llamada ancho de banda. Circuitos resonantes en serie En un circuito RLC en serie, la corriente alcanza su punto máximo en la frecuencia resonante y cae en cualquier lado de esa frecuencia. El ancho de banda, a veces abreviado AB, es una característica importante de un circuito resonante. Circuitos resonantes en paralelo En un circuito resonante en paralelo, la impedancia es máxima en la frecuencia resonante.

El ancho de banda se define en términos de la curva de impedancia de la misma manera que se usó la curva de corriente en el circuito en serie. Tipo de ancho de banda El ancho de banda para circuitos resonantes en serie o en paralelo es el intervalo de frecuencia entre las frecuencias críticas para las que se encuentra la curva de respuesta .

AB=f1-f2

Entonces, el ancho de banda es en realidad la diferencia entre f2 y f1.

AB = f1 - f2

CAPÍTULO 18
FILTROS DE PASO BAJO: Un filtro de paso bajo pasa señales de baja frecuencia desde la entrada a la salida mientras rechaza las frecuencias altas. El rango de frecuencias que pasan a través de un filtro dentro de los límites especificados se denomina banda de paso del filtro. El punto considerado como el extremo superior del intervalo de banda de paso está en la frecuencia crítica, fc. La frecuencia crítica (fc) es la frecuencia a la que la tensión de salida del filtro es el 70,7% de la tensión máxima. La frecuencia crítica del filtro también se conoce como frecuencia de corte, frecuencia de ruptura o frecuencia de -3 dB porque el voltaje de salida está 3 dB por debajo de su valor máximo en esta frecuencia. El término dB (decibel) es una unidad común utilizada en la medición de filtros.

Decibeles La base de la unidad de decibelios se deriva de la respuesta logarítmica que exhibe el oído humano a la intensidad del sonido. El decibelio es una medida logarítmica de la relación de una potencia a otra y de un voltaje a otro, que se puede utilizar para expresar la relación de entrada a salida de un filtro. La siguiente fórmula expresa una relación de potencia en decibelios:

dB = 10 log ( Salmo / Pent )

A partir de las propiedades de los logaritmos, se deriva la siguiente fórmula de decibelios para una relación de voltaje.

dB = 20 log (Vout / Vent)

Filtro RC de paso bajo: tenga en cuenta que el voltaje de salida se toma a través del capacitor. Cuando la entrada es CC (0 Hz), el voltaje de salida es igual al voltaje de entrada porque XC es infinitamente grande. A medida que aumenta la frecuencia de entrada, XC disminuye y, por lo tanto, Vout disminuye gradualmente hasta que se alcanza una frecuencia donde XC R. Esta es la frecuencia crítica, fc, del filtro. Estos cálculos prueban que la salida es el 70,7% de la entrada cuando XC R. La frecuencia a la que esto ocurre es, por definición, la frecuencia crítica.

Pendiente decreciente (roll-off) de la curva de respuesta: La salida máxima es, por definición, 0 dB como referencia. Cero decibelios corresponden a Vout Vent porque 20 log (Vout/Vent) 20 log 1 0 dB. La salida decae de 0 dB a –3 dB en la frecuencia crítica y luego continúa decayendo a una tasa fija. Este patrón de caída se conoce como pendiente descendente de la respuesta de frecuencia. La línea gruesa muestra una respuesta de salida ideal considerada "plana" hasta la frecuencia crítica. La salida luego disminuye a una tasa fija.

Filtro de paso bajo RL: tenga en cuenta que el voltaje de salida se toma a través de la resistencia. Cuando la entrada es CC (0 Hz), el voltaje de salida idealmente es igual al voltaje de entrada porque XL es un cortocircuito (si se ignora RW). A medida que aumenta la frecuencia de entrada, XL también aumenta y, por lo tanto, Vout disminuye gradualmente hasta alcanzar la frecuencia crítica. Exactamente como en el filtro de paso bajo RC, Vout 0.707Vin, por lo que el voltaje de salida es -3dB por debajo del voltaje de entrada en la frecuencia crítica.

FILTROS DE PASO ALTO: Un filtro de paso alto pasa señales de alta frecuencia desde la entrada a la salida mientras rechaza las señales de baja frecuencia. La frecuencia considerada como el extremo inferior de la banda de paso se denomina frecuencia crítica. Al igual que en el filtro de paso bajo, es la frecuencia en la que la salida es el 70,7% de la frecuencia máxima.

Filtro RC de paso alto: tenga en cuenta que el voltaje de salida se toma a través de la resistencia. Cuando la frecuencia de entrada alcanza su valor crítico, XC = R y el voltaje de salida es 0.707Vent, como en el caso de los filtros de paso. A medida que la frecuencia de entrada aumenta por encima de la frecuencia crítica, XC disminuye y, por lo tanto, el voltaje de salida aumenta y se acerca a un valor igual a Vent. La expresión para la frecuencia crítica del filtro de paso alto es la misma que para el filtro de paso bajo. Por debajo de fc, que el voltaje de salida tiene una pendiente decreciente a razón de 20 dB/década.

Filtro RL de paso alto: tenga en cuenta que la salida se toma a través del inductor. Cuando la frecuencia de salida alcanza su valor crítico, XL R, y el voltaje de salida es 0.707Vent. A medida que la frecuencia aumenta por encima de fc, XL aumenta y, por lo tanto, el voltaje de salida aumenta hasta igualar a Vent. La expresión para la frecuencia crítica de un filtro de paso alto es la misma que para el filtro de paso bajo.

FILTROS DE PASO DE BANDA: Un filtro de paso de banda pasa una determinada banda de frecuencias y atenúa o rechaza todas las frecuencias por debajo y por encima de la banda de paso. El ancho de banda de un filtro pasabanda es el rango de frecuencias dentro del cual la corriente, y por tanto la tensión de salida, es igual o superior al 70,7% de su valor a la frecuencia resonante. Como se sabe, el ancho de banda a menudo se abrevia AB y se calcula como:
AB = fC2 - fC1 donde fc1 es la frecuencia de corte baja y fc2 es la frecuencia de corte alta.
Filtro de paso bajo/paso alto Se puede utilizar una combinación de un filtro de paso bajo y un filtro de paso alto para formar un filtro de paso de banda. Debe tenerse en cuenta el efecto de carga del segundo filtro sobre el primero. Si la frecuencia crítica del filtro de paso bajo, fc, es mayor que la frecuencia crítica del filtro de paso alto, fc, las respuestas se superponen. Por lo tanto, se eliminan todas las frecuencias excepto aquellas entre fc y fc.
Filtro de paso de banda resonante en serie: como aprendió en el Capítulo 17, un circuito resonante en serie tiene una impedancia mínima y una corriente máxima en la frecuencia resonante, fr. Por lo tanto, la mayor parte del voltaje de entrada cae en la resistencia a la frecuencia resonante.

AB = fo / Q

Filtro de paso de banda resonante paralelo: Recuerde que un circuito resonante paralelo tiene una impedancia máxima en la condición resonante. En condiciones de resonancia, la impedancia de un circuito tanque es mucho mayor que la resistencia. Por lo tanto, la mayor parte del voltaje de entrada está en el circuito del tanque, lo que produce un voltaje de salida máximo en la frecuencia resonante .
A frecuencias por encima o por debajo de la frecuencia resonante, la impedancia del circuito del tanque se reduce y una mayor parte del voltaje de entrada está en R. En consecuencia, el voltaje de salida entre los terminales del circuito del tanque disminuye, creando una característica de paso de banda.
FILTROS DE RECHAZO DE BANDA: Un filtro de rechazo de banda es esencialmente lo opuesto a un filtro de paso de banda basado en respuesta. Un filtro de muesca pasa todas las frecuencias excepto aquellas dentro de una determinada banda de parada. Filtro de paso bajo/paso alto Se puede formar un filtro de rechazo de banda con un filtro de paso bajo y un filtro de paso alto. Si la frecuencia crítica de paso bajo, fc, se establece por debajo de la frecuencia crítica de paso alto, fc, se forma una característica de muesca.
Filtro de parada de banda resonante en serie: un circuito resonante dispuesto en serie en una configuración de muesca. Básicamente, esta configuración funciona así: a la frecuencia resonante, la impedancia es mínima y, por lo tanto, el voltaje de salida es mínimo.

EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

2. Determine la impedancia en la figura 17-59 y exprésela en forma polar.

Z = √R^2+(XL-XC)^2 = √(4.7 kΩ)^2 + (8.0 kΩ − 3.5 kΩ)^2 = 6.51 kΩ

4. Para el circuito de la figura 17-59, determine la reactancia neta que hará que la magnitud de la impedancia sea igual a 100 Æ.

Z = √R^2+(XL-XC)^2 = √(100)^2 + (11.3 − 0.6)^2 =100.57 ohm

6. Trace el diagrama fasorial de voltaje para el circuito de la figura 17-59.

![image](https://user-images.githubusercontent.com/105291231/187326148-9cb4f788-de58-47b9-9731-c67770a35b1a.png)


8. Para el circuito de la figura 17-59, ¿es la frecuencia resonante más alta o más baja que el valor indicado por los valores de reactancia?

Es XC < XL, fr es menor que la frecuencia indicada

10. En la figura 17-61, determine XL, XC, Z e I a la frecuencia resonante.

fr=1/2π√LC=1/2π√(1 mH)(47 pF)=734kHz
XL = 2πfrL = 2π(734 kHz)(1 mH) = 4.61 kΩ
XC = XL = 4.61 kΩ
Ztot = R = 220 Ω
I=Vs/Ztot=12/220=54.5mA

12. Para el circuito RLC de la figura 17-62, determine la frecuencia resonante.

fr=1/2π√LC=1/2π√(0.008 mH)(0.015)=15.52kHz

14. En la figura 17-62, determine el ángulo de fase entre el voltaje aplicado y la corriente a las frecuencias críticas. ¿Cuál es el ángulo de fase en condición de resonancia?

θ=arctan(0.008/0.015)=28.07

16. Exprese en forma polar la impedancia del circuito de la figura 17-63.

XL=2pi*12*15=11.3kΩ
Xc=1/2pi*0.022*12=0.6kΩ
Z = √R^2+(XL-XC)^2 = √(100)^2 + (11.3 − 0.6)^2 =100.57 ohm

18. ¿A qué frecuencia el circuito de la figura 17-63 cambia su característica reactiva (de inductiva a capacitiva o viceversa)?

fr=1/2π√LC=1/2π√15*0.033=0.28kHz

20. Determine la impedancia total del circuito de la figura 17-63 a 50 kHz.

XL=2pi*50*15=4712.39 ohms
Xc=1/2pi*0.022*50=0.14kΩ
Z = √R^2+(XL-XC)^2 = √(100)^2 + (4712.39 − 0.14)^2 =4713.31 ohm

22. ¿Cuál es la impedancia de un circuito resonante ideal dispuesto en paralelo (sin resistencia en las ramas)?

Es infinita. La impedancia es máxima a frecuencia resonante y disminuye a frecuencias más bajas y más altas

24. ¿Cuánta corriente se extrae de la fuente de la figura 17-64 en condición de resonancia? ¿Cuáles son las corrientes inductiva y capacitiva en la frecuencia resonante?

Zr = 53.1 MΩ and fr = 104 kHz
Itot =6.3 V/53.1Mohms=119 nA
IC = IL =6.3 V/√20^2+32.6^2= 193 μA

26. Encuentre la impedancia total para cada circuito de la figura 17-65.

a) √(100)^2 + (150 − 100)^2=111.8
b)√(12)^2 + (10-8)^2=12.16kohms

28. Determine el voltaje entre las terminales de cada elemento mostrado en la figura 17-66, y expréselo en forma polar.

a)L_{t} = (100 * 50)/150 + (60 * 40)/100 = 33.3 + 24 = 57.3mH
b)L_{t} = (12 * 6)/18 = 4mH

30. ¿Cuál es la corriente a través de R2 en la figura 17-67?

RTH=R||R₂+ R₂||R₁

=4.7||4.7+3.3|| 8 = 4.57k ohms

*32. Determine la resistencia y la reactancia totales en la figura 17-68.

XL(tot)=3.33kohms


34. Determine si existe un valor de C que hará Vab  0 V en la figura 17-69. Si no lo hay, explique la razón.

No habra ya que como lo muestra en la imagen del circuito esta abierto 

* 36. ¿Cuántas frecuencias resonantes hay en el circuito de la figura 17-70 ¿Por qué?

Dos ya estan en equilibrio con fuerzas actuantes y podria seguir vibrando durante mucho tiempo en condiciones perfectas

40. Si la frecuencia crítica baja es de 2400 Hz y la frecuencia crítica alta es de 2800 Hz, ¿cuál es el ancho de banda? ¿Cuál es la frecuencia resonante?

fr=2400+2800/2=2600 Hz


2. Un filtro pasabajas tiene frecuencia crítica de 3 kHz. Determine a cuáles de las siguientes frecuencias se les permite pasar y cuáles son rechazadas:
(a) 100 Hz puede (b) 1 kHz puede (c) 2 kHz puede (d) 3 kHz puede (e) 5 kHz no puede


4. ¿Cuál es fc para cada filtro mostrado en la figura 18-38? Determine el voltaje de salida a fc en cada caso cuando Vent  5 V.

a) 159.15
b)412.96
c)10504.22
d)19894.36

8. En cada uno de los casos siguientes, exprese la relación de voltaje en dB:
(a) Vent  1 V, Vsal  1 V =0dB (b) Vent  5 V, Vsal  3 V=-4.436dB
(c) Vent  10 V, Vsal  7.07 V =-3.01dB (d) Vent  25 V, Vsal  5 V=-13.97dB



10. Para cada filtro RC pasabajas, determine el voltaje de salida en dB con respecto a una entrada de 0 dB en las siguientes frecuencias (fc  1 kHz):
(a) 10 kHz=-20dB (b) 100 kHz=-40dB (c) 1 MHz=-80dB



12. La frecuencia crítica de un filtro pasaaltas es de 50 Hz. Determine a cuáles de las siguientes frecuencias se les permite pasar y cuáles son rechazadas:

(a) 1 Hz (b) 20 Hz (c) 50 Hz (d) 60 Hz (e) 30 kHz

Solo puede pasar c y d

14. ¿Cuál es fc para cada filtro de la figura 18-41? Determine el voltaje de salida a fc en cada caso (Vent 10 V).

f_{c} = 1/(2pi * L/R)
f_{c} = 1/(2pi*RC)
a)15.9kHz
b)7.2kHz
c)10.5kHz
d)0.019kHz

*16. Determine fc para cada una de las posiciones del interruptor en la figura 18-42.



18. Suponiendo que la resistencia de devanado de las bobinas mostradas en la figura 18-43 es de 10 Æ, determine el ancho de banda para cada filtro.

a) f_{0} = 1/(2pi * sqrt(LC)) = 1/(2pi * sqrt(0.01 * 12)) = 45.9kHz
X_{z} = 2pi * 45.9 * 12 = 3.4k*Omega
Q = 3460/75 = 46.13 ]
AB=0.96kHz
 b) f_{0} = 1/(2pi * sqrt(LC)) = 1/(2pi * sqrt(0.022 * 2)) = 75.87kHz
X_{L} = 2pi * 75.87 * 2 = 953Omega
Q = 953/22 = 43.11
AB = (75.83kHz)/43.11 = 1.75kHz

20. Para cada filtro mostrado en la figura 18-44, determine la frecuencia central de la pasabanda. Ignore RW.

a)50.3kHz
b)20.13kHz


24. Determine la frecuencia central para cada filtro mostrado en la figura 18-46.
1/2pi*sqrtLC
a)f0=33.93kHz
b)f0=32.83kHz

26. Si la resistencia de las bobinas de la figura 18-47 es de 8 Æ, ¿cuál es el voltaje de salida en condición de resonancia cuando Vent  50 V?

a) Veal = Rw / (R+Rw) Vent=8 / (1000+8) 50=39mV
b) Veal = Rw / (R+Rw) Vent=8 / (2200+8) 50=19mV

Video

https://youtu.be/M2bfE1afqIA

Conclusiones

Se logró obtener los conocimientos de circuitos RLC y su diferente uso.
Se aprendió sobre filtros pasivos, su aplicación con conocimientos previos

BIBLIOGRAFÍA Floyd, Thomas (2007). Principios de circuitos electricos. Octava Edicion.
