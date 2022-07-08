---
title: ¿Por qué es tan cara la electricidad?
layout: post
post-image: "/assets/images/im_4.jfif"
description: El sector eléctrico es un conjunto de entidades bien diferenciadas y relativamente complejas. Aquí vamos a resumir solamente ciertos aspectos para comprender tratar de responder a esta pregunta.
tags:
- energía
- información
- tecnología
---
En este post se hablará principalmente del sistema español, sin embargo esto es fácilmente extrapolable a la mayoría de países europeos en los que su estructura eléctrica, tanto esquemática como financiera, es similar.
# Breve introducción.
El sistema eléctrico se compone de cuatro entidades fundamentales:
- Generación
- Transporte
- Distribución
- Comercialización

![sist_elect](/assets/images/sist_ele.jpg)

Tanto el transporte como la distribución de la energía son actividades reguladas por el gobierno debido a su carácter de monopolio natural. Por el contrario, la generación y la comercialización son actividades de libre mercado.

# Precio de la electricidad.
Ya tenemos los participantes, ahora, ¿Cómo se determina el precio final que pagamos en la factura?

En primer lugar, el gobierno fija una serie de precios o de tarifas que tendrán que pagar todos los usuarios de la red. 

Estos precios están destinados entre otras cosas, a mantener la infraestructura, pagar a los operarodes del mercado y del sistema, cargos que provienen de diversas fuentes, etc.

Esto podemos verlo en las secciones marcadas con "Importe por peajes de transporte y distribución y cargos" o algo similar.

Este tema es amplio y se le podría dedicar un post aparte, sin embargo, lo que aquí nos interesa es cómo se fija el precio del kWh.

## Fijación de precios.
Conceptualmente la tarea es sencilla, generas electricidad y hay que pagar el coste de esa generación como cualquier otro bien o servicio. Pero ¿Cuánto vale generar esa electricidad?, ¿Cuánto vale transportarla?, los organismos encargados de la gestión de la misma, distribuirla, compensación de pérdidas, etc. Es aquí donde vienen los problemas, porque establecer de manera precisa cuánto vale un kWh no es trivial y además es muy abstracto ya que no podemos hablar de algo tangible que se pueda intercambiar fácilmente sino de una red interconectada en la que se vierte la energía demandada en ese instante.

En España, al igual que en la mayor parte de Europa, la fijación del precio de la energía atiende a las reglas del llamado **'Mercado Marginalista'**. 

En este mercado se realizan las ofertas de venta de energía por parte de los generadores y las ofertas de compra por parte de los consumidores (representados mayormente por las comercializadoras) para cada hora del día siguiente.

Si ponemos estas ofertas en una gráfica vemos algo como lo siguiente:

![curvas_oferta_demanda](/assets/images/curva_o_d.jpg)

Estas son las curvas agregadas de oferta (verde) y demanda (azul) y el punto donde se cruzan es el punto o precio de casación.

Ese será el precio que se establecerá para una hora en concreto del día siguiente. 

Los generadores cuyas ofertas estén por debajo del precio de casación deben producir y a todos ellos se les pagará el precio de casación. De forma similar ocurre con los consumidores, en principio, los que hayan ofertado igual o más caro al punto de casación recibirán energía.

Es evidente que cuanto más alto se crucen ambas curvas, más alto será el precio de la electricidad en esa hora. Pero ahora toca hacerse otra pregunta: ¿Por qué ha subido tanto el precio de la luz?

## ¿Por qué ha subido tanto el precio?
No importa cuándo leas esto ya que es un tema recurrente y no me refiero a que suba exageradamente el precio, sino a cuestionarse estas cosas.

Para empezar, debería de llamaros la atención que haya generadores que oferten a 0 €/MWh y que haya consumidores realizando ofertas de compra a precios excesivos. Pues ésta es una de las principales características del mercado marginalista y es que las centrales generadoras no entran al 'pool' (mercado) con su coste de producción, que a priori suena a lo más lógico, sino que entran con su coste de oportunidad.

Pongamos un ejemplo claro. 
- Una central solar fotovoltaica tiene unos costes fijos muy altos, pero este tipo de centrales entran al pool a 0 €. Esto no quiere decir que no les cueste nada generar electricidad, sino que su generación depende del recurso solar y si para esa hora en concreto hay sol, tienen que entrar en el mix[^nota] de generación porque, generalmente, les es más rentable producir a cualquier precio y aprovechar el recurso solar, que no producir y "no saber" cuándo podrán entrar otra vez.

- De igual forma con los consumidores. Las comercializadoras tienen que cubrir la demanda de los usuarios al 100% por lo que entran al pool con el precio máximo que se permita, pero esto no quiere decir que vayan a pagar a ese precio, sino que tienen que asegurarse que cuando se realice la casación, estén dentro.

Entoces, en la curva de la oferta van entrando las diferentes tecnologías de generación, cada una con su coste de oportunidad, hasta que se produce la casación. Pero ¿Qué ocurre si una de esas tecnologías empieza a ofertar a un precio muy alto porque de otra forma no le sale rentable producir?
Pues que la casación se realizaría a un precio más elevado, **et voilà** aquí tenemos uno de los motivos por los que el precio de la electricidad puede subir y, de hecho, lo hace.

Por lo general, las tecnologías solares o eólicas y las nucleares forman la base de esa curva de oferta mientras que las que, recientemente, están fijando los precios son la hidráulica, cogeneración o carbón.

## Entonces....
El sistema marginalista, si bien es cierto que necesita una modificación para evitar que subidas repentinas del precio de una tecnología afecte al resto de ellas, es robusto y ofrece resultados similares a su contraparte el "pay as bid" pero eso es para otro post.

A fecha de escribir este post, el sujeto que ha provocado un cambio significativo en el precio de la electricidad es el gas. El precio del gas se ha visto envuelto en una subida constante y se ha mantenido a precios altos desde principios de 2021. 

A esto hay que sumarle la también subida del precio de los derechos de emisión de CO<sub>2</sub> (Pagar más cuanto más CO<sub>2</sub> se emita a la atmósfera) y los movimientos antinucleares en buena parte de Europa, donde se incluye España.

 Esto hace que, si se elimina una de las fuentes de generación más robustas que se complementa genial con la generación de energías renovables, se tenga que suplir su ausencia con centrales de gas.

 Estas centrales como las de cogeneración son necesarias y versátiles pero la idea de la transición energética es emmitir menos CO<sub>2</sub> a la atmósfera y debemos avanzar en la dirección correcta.

 # Resultado
Aquí tenéis una gráfica de los precios mensuales medios de España sacados de [OMIE](https://www.omie.es/es/market-results/annual/daily-market/daily-prices?scope=annual&year=2022):

![omie](/assets/images/resumen_omie.png)

Además, si graficamos el precio diario de la electricidad junto con la cotización del gas de dos mercados europeos muy potentes como son TTF Dutch y Mibgas, podemos ver lo siguiente:

![pico](/assets/images/pico_elect.png)

Parece haber una correlación entre estos dos elementos y es que en muchas horas era el gas (a un precio alto) el que fijaba el precio horario de la electricidad.

Todo lo anterior ha dado como resultado un aumento sin precedentes del precio de la energía. Aquí os dejo unas gráficas de un usuario común en España con una potencia contratada en ambos periodos de 4.4 kW, acogido al PVPC.

<img src="/assets/images/evo_consumos.png" alt="evo_c" width="570px"/>
<img src="/assets/images/evo_precios.png" alt="evo_p" width="570px"/>

Se ve muy claramente cómo la tendencia de consumo es muy parecida en los tres años, sin embargo, la curva de precios está desplazada en el 'eje y' viendo cómo afecta de manera directa al consumidor y la diferencia de precios.

A continuación adjunto dos gráficas de la relación €/kWh para este mismo usuario:

<img align="center" src="/assets/images/relacion_energia.png" alt="rel_e" width="570px"/>
<img align="center" src="/assets/images/relacion_total.png" alt="rel_t" width="570px"/>

La primera hace referencia a la relación, tomando el precio de la energía únicamente y de un tiempo de 12 meses, mientras que la segunda tiene en cuenta el precio total de la factura.

La segunda gráfica es muy esclarecedora y a pesar de los cambios introducidos en el sistema de tarificación español, es muy marcado el peso que está teniendo el aumento de la energía en este último año.

# Conclusión
Como conclusión de este post se puede sacar que las materias primas con las que se genera electricidad juegan un papel primordial en el precio final de la misma y que, por lo tanto, una buena gestión y previsión de las mismas es crucial.

Me gustaría aclarar que este post es meramente informativo y que cualquiera de los temas mencionados podrían ser abordado en decenas de páginas de manera mucho más precisa. 

<br>

[^nota]: **Nota**: El Mix de generación se refiere al conjunto de tecnologías que van a generar en esa hora.

