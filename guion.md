# Guión del laboratorio denominado "Propiedades emergentes de los ecosistemas o el todo es más que la suma de sus partes"


> + **_Versión_**: 2022-2023
> + **_Titulación_**: PACE
> + **_Autor_**: Curro Bonet-García (fjbonet@uco.es)
> + **_Duración_**:  1 hora y 15 minutos.



## Objetivos 

En este "laboratorio" tratamos de abordar los siguientes objetivos, agrupados en dos tipos. 

+ Disciplinares: Están relacionados con competencias propias de la ecología.
  + Entender (más o menos) la idea de "sistema complejo"
  + Empezar a entender el concepto de "propiedad emergente"
+ Instrumentales: Están relacionados con la adquisición de competencias en el manejo de herramientas potencialmente útiles en ecología y en otros ámbitos.
  + Conocer la teledetección como disciplina.
  + Aprender cómo gracias a la teledetección podemos medir algunas propiedades emergentes de los sistemas complejos.



## Hilo argumental: Desde Rajoy a cómo respira un bosque

+ Corría el año 2012 y el por aquel entonces presidente del gobierno, M. Rajoy, asistía a una reunión de alto nivel con varios líderes europeos. En un momento de la reunión, los micrófonos captaron cómo nuestro presi decía: "it is very difficult todo esto". Rajoy reaccionó ante un problema complejo como hacemos habitualmente: quejándonos de que la vida es compleja. 



![Rajoy](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/raw/main/imagenes/rajoy.jpg)



+ El Sr. Rajoy tenía razón. Todo es muy difícil. Muy complejo, para ser más precisos. El mundo es complejo. Todo lo que vemos es el resultado de miles, millones de interacciones de átomos, moléculas y otras entidades que ocurren en cada lapso de tiempo y en cada "trozo" del espacio. Estamos rodeados de "sistemas complejos". 

+ Hay muchos sistemas complejos a nuestro alrededor. Un puente es un buen ejemplo de un sistema complejo. Para que dure mucho tiempo y cumpla su función es necesario saber muchas cosas. Debemos de conocer las leyes físicas que gobiernan la distribución de masas, las tensiones, la resistencia de los materiales, etc. No es fácil mantener y conservar un puente.

![puente](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/raw/main/imagenes/puente_de_alcantara.jpg)

+ Los ecosistemas son también sistemas complejos. Un bosque, por ejemplo, es una agrupación de seres vivos que hacen cosas de seres vivos: comen, se reproducen, compiten, cooperan, etc. ¿sabemos construir ecosistemas?, ¿y mantenerlos?

![bosque](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/raw/main/imagenes/bosque.jpg)

+ La diferencia fundamental entre un puente y un ecosistema (desde el punto de vista de los sistemas complejos) es que las propiedades del puente resultan de la agrupación de las propiedades de los elementos que lo conforman. Es decir, un bloque de hormigón pequeño tiene propiedades parecidas a las de un puente. Esto no pasa con los bosques (ni con los ecosistemas en general). Las propiedades de los ecosistemas van más allá de las propiedades de los elementos que lo constituyen. Es decir, el bosque es más que la suma de sus partes. Estas características que surgen cuando muchos seres vivos se asocian en un ecosistema, son las denominadas "propiedades emergentes" de un sistema complejo. Data nos lo explica muy bien en [este](https://www.youtube.com/watch?v=LSXffX8weME) vídeo con otro ejemplo.

<iframe width="560" height="415" src="https://www.youtube.com/embed/LSXffX8weME" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


+ Veamos ahora este vídeo.

<iframe width="560" height="315" src="https://www.youtube.com/embed/jlO8NiPbgrk?start=48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

  + ¿Reconocéis lo que se describe en él?
  + En efecto, vemos una animación en 4D de la fotosíntesis. Estamos observando cómo trillones de fotones estimulan las moléculas de los fotosistemas y provocan la fotolisis del agua, la liberación de oxígeno y la producción de moléculas de azúcar. 

+ ¿Qué pasa si observamos millones de hojas haciendo la fotosíntesis? ¿y si además observamos cómo los animales se las comen y luego se comen entre ellos?. En definitiva, ¿qué propiedad o propiedades emergentes surgen cuando vemos la fotosíntesis de un ecosistema en su conjunto? En el vídeo mostrado a continuación se observa este proceso a escala planetaria.


<iframe width="560" height="415" src="https://www.youtube.com/embed/8uDYfpw1gg0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


+ En este rato trataremos de responder (parcialmente) alguna de estas preguntas. Estudiaremos los ecosistemas desde arriba, viéndolos en su conjunto sin preocuparnos de cómo los fotones estimulan las moléculas de clorofila. Para ello usaremos una serie de técnicas englobadas en una disciplina llamada "teledetección". 

+ Como su nombre indica, la teledetección nos permite ver cosas desde lejos. Nuestros ojos son aparatos muy eficaces de teledetección. Pero en este caso usaremos satélites. 

  + ¿Cuántos satélites diríais que hay orbitando alrededor de la Tierra?
  + Muchos más.
  + Estos, más o menos. 
  + No son todos útiles para ver la Tierra. La mayoría son satélites de comunicaciones. Pero vaya, que hay muchísimos.

+ Los satélites tienen cámaras parecidas a las de nuestros móviles. Al menos conceptualmente. Se caracterizan porque son capaces de "excitarse" (en el sentido fotónico de la palabra) cuando llegan a ellas ondas electromagnéticas con una longitud de onda concreta. A nuestros ojos les pasa algo parecido. Vemos ciertas longitudes de ondas y somos ciegos ante otras. No vemos en el infrarrojo ni en el ultravioleta, por ejemplo. 

+ Pues bien, resulta que hay satélites que son capaces de "ver" la fotosíntesis. Una planta que hace la fotosíntesis refleja poca radiación roja porque la utiliza para romper moléculas de agua y producir glucosa. Una planta muerta refleja menos radiación de infrarrojos que una viva. Así que, si tenemos en un satélite sensores que pueden ver la radiación roja e infrarroja que refleja la superficie, podemos cuantificar cuánta fotosíntesis está ocurriendo en un lugar determinado. Para cuantificar esto construimos índices de vegetación. El más utilizado se denomina NDVI (Normalized Difference Vegetation Index)

+ Todo este rollo sirve para que entendáis cómo las imágenes de satélite nos ayudan a visualizar una propiedad emergente de los ecosistemas: la producción primaria. Se define como la cantidad de biomasa que pueden generar los organismos autótrofos de un ecosistema en un momento dado. Cuando tomamos imágenes de satélite estamos viendo en realidad el resultado de la interacción de trillones de fotones con los cloroplastos de millones de plantas. 

+ Vamos a analizar con cierto detalle cómo cambia la producción primaria en distintos ecosistemas de la Tierra. Para ello usaremos imágenes de un satélite llamado Landsat. Este satélite (bueno, en realidad son varios) fue lanzado en 1984 y sigue en órbita en la actualidad. Pasa por cada punto de la Tierra cada 16 días. Y toma una foto. Así que tenemos muchísimas imágenes de satélite de todo el planeta. Es posible "resumir" toda la información de esta larguísima serie temporal. Para ello podemos obtener imágenes que agregan la producción primaria de cada año, por ejemplo. Si representamos la producción primara de varios años en una gráfica, observamos cuestiones interesantes que nos ayudan a entender cómo funciona un ecosistema determinado. Veremos varios ejemplos usando una herramienta muy potente llamada "[Landsat timeseries explorer](https://jstnbraaten.users.earthengine.app/view/landsat-timeseries-explorer)"

  + Diferencia entre un bosque y un cultivo. Veremos desde arriba el patrón de producción primaria de dos zonas muy cercanas a esta clase. De hecho son dos zonas que visitaréis a continuación. La primera es un bosque y la segunda un cultivo. En la siguiente sesión conoceréis a alguno de los elementos que conforman el ecosistema. Desde nuestra visión holística, esos elementos son las piezas cuyas interacciones generan las propiedades emergentes que observamos desde el satélite.

![parcelas](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/raw/main/imagenes/rabanales.png)
											*Ubicación de las dos parcelas. La del oeste es el bosque*

![bosque](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/raw/main/imagenes/bosque_rabanales.png)
														*Patrón de producción primaria del bosque*



![pasto](https://github.com/aprendiendo-cosas/TP_emergentes_teledeteccion_PACE_UCO/raw/main/imagenes/pasto_cultivos_rabanales.png)
													*Patrón de producción primaria del pastizal-cultivo*







