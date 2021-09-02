UV MANIPULATION


ENG

Starting from a TOP GLSL and then from a UV map, it is possible to create a loop by modifying, or inserting, simple mathematical functions, in this case creating a "uniform float time" vector that moves diagonally. From this, we proceed to manipulate the UV using two IMAGEFILTERS, namely TWIRL and FEEDBACKEDGE. By inserting a geometry, an image or a noise in the patch and linking it to the rest via a TOP REMAP, it is possible to obtain various effects. You can be creative by thinking with TOP COMPOSITE, but also by changing the parameters of TOP NOISE and the two IMAGEFILTERs. To obtain a smooth animation, attention must be paid to the pixel format, 32-bit float (RGBA) is recommended, but you can manage the output with a TOP ANTI ALIAS or a TOP BLUR. 

ITA

Partendo da un TOP GLSL e quindi da una mappa UV, è possibile creare un loop modificandone, o inserendone, semplici funzioni matematiche, in questo caso creando un vettore “uniform float Time” che si muove diagonalmente. Partendo da ciò si procede manipolando gli UV tramite l’utilizzo di due IMAGEFILTER, ovvero TWIRL e FEEDBACKEDGE. Inserendo una geometria, un’immagine, o un noise alla patch e collegarla al resto passando per un TOP REMAP è possibile ottenere svariati effetti. Si può essere creativi, ragionando con TOP COMPOSITE, ma anche modificando i parametri dei TOP NOISE e dei due IMAGEFILTER. Per ottenere un’animazione fluida bisogna prestare attenzione al formato dei pixel, consigliato 32-bit float (RGBA), ma è possibile gestirne l’output con un TOP ANTI ALIAS o un TOP BLUR. 


Freely inspired by

https://www.youtube.com/watch?v=EOP6f39e0dw
