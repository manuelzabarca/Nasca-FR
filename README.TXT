Nasca-FR es un software para análisis, procesamiento e interpretación de datos de terremotos naturales mediante el método de Función del Receptor (Receiver Funtion).
Función del Receptor fue desarrollada en los años 80 como metodologia de investigación que permite determinar las profundidades y velocidades de
interfaces sismicas a gran profundidad. La discontinuidad de Mohorivicic ha sido estudiada con Función del Receptor (Langston, C. A., Structure under Mount Rainier, Washington, inferred
from teleseismic body waves, J. Geophys. Res., 84, 4749–4762, 1979); otras discontinuidades han sido detectadas a los 410 y 660 km de profundidad (Dueker, K. G., and A. F. Sheehan,
 Mantle discontinuity structure beneath the Colorado Rocky Mountains and High Plains, J. Geophys. Res.,103, 7153 – 7169, 1998); y en algunas zonas del globo terraqueo 
se han detectado indicios de otra discontinuidad a los 720 km (Receiver function analysis of the North American crust and upper mantle, D. S. Ramesh, R. Kind, X.
 Yuan, Geophysical Journal International, Volume 150, Issue 1, July 2002, Pages 91–108).
El método de Función del Receptor fue adaptado por el autor para estudios de interfaces sísmicas mucho más someras,en el orden de pocos km. (Iván, Zevallos.,
 Marcelo, Assumpção., Antonio, L., Padilha. (2009). Inversion of teleseismic receiver function and magnetotelluric sounding to determine basement depth in 
the Paraná Basin, SE Brazil. Journal of Applied Geophysics, 68(2):231-242. doi: 10.1016/J.JAPPGEO.2008.11.002). Una de las aplicaciones practicas sería
en la exploracion de hidrocarburos en cuencas sedimentarias, en las cuales tendria una ventaja sobre los metodos tradicionales de exploracion
(refraccion y reflexion sismicas) pues se vale de la energia sismica de terremotos naturales; esto significa que cuenta con mucha energia, capaz de
atravesar estructuras geologicas, de la base al techo, aunque estas estructura presenten problemas de gradiente inverso de velocidades o dispersion 
por difracciones multiples (pantallas sismicas que muchas veces inutilizan los datos de reflexion sismica).

El uso del software es intuitivo; aunque requiere de una preparacion previa de los sismogramas (para esta etapa se recomienda seguir los tutoriales online de
Charles Ammon). Despues de efectuar los procesos descritos por Ammon, se completa la preparación de sismogramas con estos pasos:
1.- rotar a GCP (obtner radial, transversal y vertical);
2.- poner inicio de sismograma en cero (B=0)
3.- poner tiempo de origen en variable T0.
4.- convertir a sac alpha

El programa Nasca-FR es capaz de leer sismogrmas en el formato SAC alpha; la opcion de menú para esta accion es Abre -- Lee SAC. Esto mostrará los sismogramas
radial, tagencial y vertical en la ventana grafica.
Luego debemos marcar el tiempo de arribo de la onda P con la opcion de menú Abre -- Marca P. Con esta se exhibira en ventana grafica el sismograma vertical,
 ya listo para efectuar zoom sobre la zona de primer impulso de onda P; es obligatorio hacer el zoom (del vertice inferior izquierdo al vertice superior derecho)
 con el botón izquierdo del raton pulsado; luego marcamos el inicio de P pulsando boton izquierdo del ratón.
El siguiente paso es para escoger la frecuencia principal del sismograma, opción del menú Funcion del Receptor -- Marca frecencia;  aqui tambien es
obligatorio efectuar zoom antes de marcar la frecuencia (mismo procedimiento descrito antes).  
Obtenemos la Funcion de Receptor bajo la estacion sísmica con la opción Funcion del Receptor -- Determina FR.
Estamos listos para inferir un modelo sismico de la tierra bajo la estacion sismica. Escogemos la opcion Inversion -- Gradiente, para efectuar un proceso 
de modelamiento inverso sobre la funcion del receptor (FR). En la ventana grafica apareceran los pseudo-sismogramas de FR y de la curva de ajuste; si el error
de ajuste es considerado suficientemente bueno, segun nuestro criterio, tenemos el modelo de velocidades sismicas mostrado en la ventana de texto (bajo el grafico)
y tambien en la memoria del computador, de donde podemos mandar a generar un archivo grafico en el formato postscript con  Inversion -- Perfil sismico.
Las figuras que aparecen en la ventana grafica pueden ser trasladas a un archivo de imagen vectorial en cualquier momento con la opcion Imprenta -- Grafico postscript.

Este software es de uso libre, del tipo freeware, sin embargo requiere de una clave para su instalacion en un pc con sistema windows. La clave es gratis,
se la proporciono a quien la solicite por el correo manuel.z.abarca@outlook.es; lo unico que requiero es una disertación breve sobre el uso y aplicacion para que lo
solicita. 

Un breve tutorial de uso se encuentra en https://www.youtube.com/watch?v=DYXn3SfYbhI 



