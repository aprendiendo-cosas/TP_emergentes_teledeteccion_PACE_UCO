# Guión del laboratorio denominado "Estudiando los ecosistemas desde el cielo mediante satélites"


> + **_Versión_**: 2023-2024
> + **_Titulación_**: PACE
> + **_Autor_**: Curro Bonet-García (fjbonet@uco.es)
> + **_Duración_**:  35 minutos.



## Objetivos 

En este "laboratorio" tratamos de abordar los siguientes objetivos, agrupados en dos tipos. 

+ Disciplinares: Están relacionados con competencias propias de la ecología.
  + Entender (más o menos) la idea de "sistema complejo"
  + Empezar a entender el concepto de "propiedad emergente"
+ Instrumentales: Están relacionados con la adquisición de competencias en el manejo de herramientas potencialmente útiles en ecología y en otros ámbitos.
  + Conocer la teledetección como disciplina.
  + Aprender cómo gracias a la teledetección podemos medir algunas propiedades emergentes de los sistemas complejos.



## Hilo argumental

+ En la naturaleza hay "cosas" muy complejas que resulta difícil de describir. Una de ellas son los ecosistemas. Sabemos que están compuestos de elementos (especies, ambiente abiótico, relaciones, etc.) que "hacen cosas", pero nos cuesta verlos como un sistema integrado.
+ En estos sistemas suele ocurrir que su comportamiento va algo más allá que lo que resultaría de sumar el comportamiento de los organismos que lo componen. Estas nuevas propiedades se denominan "propiedades emergentes".
+ El cuerpo humano (y el del resto de animales) es también un sistema complejo. Piensa, por ejemplo, en el funcionamiento de cada una de las neuronas de tu cerebro. Cada una de estas células se limita a transmitir un impulso electroquímico a una neurona cercana. La actividad conjunta de los miles de millones de neuronas del cerebro genera una propiedad emergente llamada "conciencia"
+ Algo parecido pasa en un ecosistema. Si ponemos el foco, por ejemplo, en la fotosíntesis, veremos cómo la actividad sincronizada de los trillones de cloroplastos que hay en un bosque, genera un patrón de producción primaria específica. En el siguiente vídeo puedes ver el funcionamiento de los cloroplastos. 

<iframe width="560" height="415" src="https://www.youtube.com/embed/jlO8NiPbgrk?start=48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

  + En el video vemos una animación en 4D de la fotosíntesis. Estamos observando cómo trillones de fotones estimulan las moléculas de los fotosistemas y provocan la fotolisis del agua, la liberación de oxígeno y la producción de moléculas de azúcar. 

+ ¿Qué pasa si observamos millones de hojas haciendo la fotosíntesis? ¿y si además observamos cómo los animales se las comen y luego se comen entre ellos?. En definitiva, ¿qué propiedad o propiedades emergentes surgen cuando vemos la fotosíntesis de un ecosistema en su conjunto? En el vídeo mostrado a continuación se observa este proceso a escala planetaria.


<iframe width="560" height="415" src="https://www.youtube.com/embed/8uDYfpw1gg0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


+ En este rato trataremos de responder (parcialmente) alguna de estas preguntas. Estudiaremos los ecosistemas desde arriba, viéndolos en su conjunto sin preocuparnos de cómo los fotones estimulan las moléculas de clorofila. Para ello usaremos una serie de técnicas englobadas en una disciplina llamada "teledetección". 

+ Como su nombre indica, la teledetección nos permite ver cosas desde lejos. Nuestros ojos son aparatos muy eficaces de teledetección. Pero en este caso usaremos satélites. 

  + ¿Cuántos satélites diríais que hay orbitando alrededor de la Tierra?
  + Muchos más.
  + [Estos](https://www.youtube.com/watch?v=FDiIayhicFo), más o menos. 
  + No son todos útiles para ver la Tierra. La mayoría son satélites de comunicaciones. Pero vaya, que hay muchísimos.

+ Para entender esto tienes que evocar el conocimiento que ya tienes sobre el espectro electromagnético. La siguiente figura resume un poco las ideas principales.

![espectro](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/raw/2023_2024/imagenes/espectro.png)




+ Los satélites tienen cámaras parecidas a las de nuestros móviles. Al menos conceptualmente. Se caracterizan porque son capaces de "excitarse" (en el sentido fotónico de la palabra) cuando llegan a ellas ondas electromagnéticas con una longitud de onda concreta. A nuestros ojos les pasa algo parecido. Vemos ciertas longitudes de ondas y somos ciegos ante otras. No vemos en el infrarrojo ni en el ultravioleta, por ejemplo. La siguiente imagen resume esta idea.



![solete](https://raw.githubusercontent.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/2023_2024/imagenes/sol.png)




+ Pues bien, resulta que hay satélites que son capaces de "ver" la fotosíntesis. Una planta que hace la fotosíntesis refleja poca radiación roja porque la utiliza para romper moléculas de agua y producir glucosa. Una planta muerta refleja menos radiación de infrarrojos que una viva. Así que, si tenemos en un satélite sensores que pueden ver la radiación roja e infrarroja que refleja la superficie, podemos cuantificar cuánta fotosíntesis está ocurriendo en un lugar determinado. Para cuantificar esto construimos índices de vegetación. El más utilizado se denomina NDVI (Normalized Difference Vegetation Index).

![NDVI](https://raw.githubusercontent.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/2023_2024/imagenes/ndvi.png)


+ Todo este rollo sirve para que entendáis cómo las imágenes de satélite nos ayudan a visualizar una propiedad emergente de los ecosistemas: la producción primaria. Se define como la cantidad de biomasa que pueden generar los organismos autótrofos de un ecosistema en un momento dado. Cuando tomamos imágenes de satélite estamos viendo en realidad el resultado de la interacción de trillones de fotones con los cloroplastos de millones de plantas. 

+ Vamos a analizar con cierto detalle cómo cambia la producción primaria en distintos ecosistemas de la Tierra. Para ello usaremos imágenes de un satélite llamado Landsat. Este satélite (bueno, en realidad son varios) fue lanzado en 1984 y sigue en órbita en la actualidad. Pasa por cada punto de la Tierra cada 16 días. Y toma una foto. Así que tenemos muchísimas imágenes de satélite de todo el planeta. Es posible "resumir" toda la información de esta larguísima serie temporal. Para ello podemos obtener imágenes que agregan la producción primaria de cada año, por ejemplo. Si representamos la producción primara de varios años en una gráfica, observamos cuestiones interesantes que nos ayudan a entender cómo funciona un ecosistema determinado. Veremos varios ejemplos usando una herramienta muy potente llamada "[Landsat timeseries explorer](https://jstnbraaten.users.earthengine.app/view/landsat-timeseries-explorer)"

  1. Diferencia entre un bosque y un cultivo. Veremos desde arriba el patrón de producción primaria de dos zonas muy cercanas a esta clase. De hecho son dos zonas que visitaréis a continuación. La primera es un bosque y la segunda un cultivo. En la siguiente sesión conoceréis a alguno de los elementos que conforman el ecosistema. Desde nuestra visión holística, esos elementos son las piezas cuyas interacciones generan las propiedades emergentes que observamos desde el satélite.

![parcelas](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/raw/2023_2024/imagenes/rabanales.png)
											*Ubicación de las dos parcelas. La del oeste es el bosque*

![bosque](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/raw/2023_2024/imagenes/bosque_rabanales.png)
														*Patrón de producción primaria del bosque*



![pasto](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/raw/2023_2024/imagenes/pasto_cultivos_rabanales.png)
													*Patrón de producción primaria del pastizal-cultivo*


  2. Evolución de la producción primaria en el bosque de Posadas. Busca "posadas, córdoba" en la web anterior. Identifica el bosque hay al norte del pueblo (Parque Periurbano La Sierrezuela) y haz click en cualquier punto del bosque. Verás cómo se genera una gráfica como las anteriores.
     + ¿Cómo ha evolucionado la producción primaria en esta zona?
     + ¿A qué crees que se debe este cambio?
  3. Evolución de la producción primaria después de una perturbación. Busca "Sierra Bermeja, España" en la web anterior. Haz click en una zona sin bosque. Se generará una gráfica como las anteriores.
     + ¿Qué crees que ha pasado en esta zona?
     + ¿Recuerdas el nombre del proceso ecológico que ocurre después de una perturbación?





En [este](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/raw/2023_2024/presentacion/prop_emergentes.pptx) enlace está disponible la presentación que usamos como guía de la presentación. 

## Conexión a los ordenadores de la UCO

Por motivos de seguridad es necesario usar una contraseña para acceder a los ordenadores. Usad las siguientes:



```
USUARIO    CONTRASEÑA
-------    ----------

DPACE001 - Toi:nul536
DPACE002 - Nog$sof593
DPACE003 - Cof:dok954
DPACE004 - Hab>lef749
DPACE005 - Cek!dok963
DPACE006 - Tia-meb293
DPACE007 - Pik&com246
DPACE008 - Bes:goa657
DPACE009 - Hod%mut625
DPACE010 - Foc&lia983
DPACE011 - Nam>doe682
DPACE012 - Vos-pei765
DPACE013 - Gud!kal258
DPACE014 - Doc%dua845
DPACE015 - Kat:but298
DPACE016 - Mio+fes546
DPACE017 - Goh.rir637
DPACE018 - Giv&rul968
DPACE019 - Gei>jel532
DPACE020 - Pus+dil562
DPACE021 - Kue&cal695
DPACE022 - Puh&fip957
DPACE023 - Tod+nii298
DPACE024 - Hae%sid423
DPACE025 - Ruo.hap539
DPACE026 - Jed!nem459
DPACE027 - Sis_mub952
DPACE028 - Fik*cud463
DPACE029 - Nod*nii326
DPACE030 - Lim.gol293
```



