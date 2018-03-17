 PDF To Markdown Converter
Debug View
Result View
Actualmente la relacion entre el proyecto con el campo, se realiza mediante el siguiente proceso instrumental:

# REDACCION, EJECUCION, MODIFICACION Y COMPROBACION DE UNA

# OBRA LINEAL PARA LIBRETAS ELECTRONICAS PSION WORKABOUT.

Autor- Javier Turégano Mansilla. Ingeniero Técnico en Topografía

Este programa fue desarrollado y presentado como Proyecto Fin de Carrera de Topografía en la
Universidad de Extremadura, con la finalidad de aumentar las posibilidades en la utilización conjunta de
la libreta electrónica y la estación total, en la topografía de obras.

### RESUMEN

Se desarrolló un programa de redacción, ejecución, modificación y comprobación de obra lineal
para una libreta electrónica PSION WORKABOUT. Además de cumplir los estándares actuales, el
programa realiza el cajeo y posterior cálculo del movimiento de tierras, actualmente inexistente en el
software para libretas electrónicas. Con esto se da solución al desarrollo completo de la obra. Además se
introducen mejoras en taquimetría, toma de perfiles y replanteo. Finalmente aporta la novedad de poder
visualizar los perfiles de obra calculados en tiempo real.

### ANTECEDENTES

La topografía clásica ha sido objeto de un desarrollo radical desde sus inicios, principalmente
causado por los nuevos conocimientos tecnológicos, como la electrónica y la informática. Estos nuevos
conocimientos han permitido mejorar rendimientos y simplificar el método topográfico. Especialmente,
nos ha permitido obtener resultados mas fiables.

Con la aparición del taquímetro, el topógrafo estaba obligado a tomar un mayor número de
lecturas tales como lecturas angulares, hilos taquimétricos... Para organizarlas se utilizaban las llamadas
Libretas Taquimétricas, que facilitaban en gran medida la ordenación de los datos. Posteriormente, se
realizaba el proceso de cálculo, rellenando cada casilla de la libreta mediante operaciones sencillas
sucesivas hasta obtener unas coordenadas, superficie o volumen final. La posibilidad de errores
accidentales era muy alta, pues se realizaba una gran cantidad de procesos en los que cualquier pequeño
error se arrastraría hasta la solución final.

Con las pequeñas calculadoras de bolsillo se simplificaron las Libretas Taquimétricas, pues
permitian realizar cálculos reiterativos relativamente complejos, pudiendo calcular el dato final casi sin
operaciones parciales. Aunque se redujo la probabilidad de error en el cálculo aún se podía hacer una
mala lectura del aparato o una errónea anotación o simplemente pulsar una tecla errónea de nuestra
calculadora.

Fue con el desarrollo informático cuando apareció el tandem Computadora-Libreta Electrónica,
un método que continúa en nuestros días y nos permite un alto rendimiento y lo que es más importante
elimina gran cantidad de errores accidentales. Su fuerza reside en:

- Rapidez y comodidad de recogida de lecturas en campo.
    Pues se elimina la escritura manual sobre papel, pasando a soportes magnéticos menos
    perecederos y reducidos.
- Eliminación del error de lectura de los ángulos y distancias del aparato.
    Con la aparición de taquímetros electrónicos, que realizan las lecturas de los nonios
    mediante LEDs. Así, la lectura se realiza automáticamente a través del puerto de
    comunicaciones externo y es recogida en la memoria de la libreta electrónica.
- Posibilidad de edición de los datos tomados: borrar, modificar, copiar ...


```
Las libretas se desarrollaron, presentando una pantalla de cristal líquido que nos permite
la navegación entre menús accediendo a diversas opciones de edición.
```
- Transferencia al ordenador automática
    Los datos de la memoria pueden ser transferidos mediante un programa de
    comunicaciones a nuestra estación de cálculo mediante las comunicaciones a través del
    puerto.
- Velocidad de cálculo elevada
    Los ordenadores realizan un elevadísimo numero de cálculos mayor que las
    calculadoras de bolsillo.
- Conexión con programas de diseño, hojas de cálculo, procesadores de texto.
    Mediante ficheros de intercambio que normalmente atienden al formato ASC-II

Mediante el Ordenador-Libreta electrónica podemos realizar satisfactoriamente el ciclo
LEVANTAMIENTO-CALCULO-REPLANTEO requerido en la proyección y ejecución de cualquier
trabajo de topografía clásica. Realmente se da solución al problema que en los inicios se planteaba
pudiendo afirmar que se dispone de una herramienta rápida y eficaz, aunque se sigue planteando un
problema, la imposibilidad de realizar el proceso de cálculo en campo, necesitando un ordenador que
se encuentra en la oficina.

La evolución de las Libretas electrónicas ha sido paralela a la evolución del ordenador personal,
apareciendo en el mercado Libretas Electrónicas con mayor velocidad de cálculo y comunicación.
Además su capacidad de almacenamiento se ha multiplicado, se ha reducido su tamaño y su peso y las
pantallas han mejorado su resolución. Ya no se puede hablar de simples libretas electrónicas, sino de
auténticos ordenadores de mano, con procesador y completo sistema operativo.

A causa de este rápido desarrollo de hardware de mano producido en los últimos tres años existe
una laguna en el diseño y desarrollo de software apropiado para estas maquinas. Al contrario que en las
décadas precedentes donde era impensable el desarrollo de sofisticados programas de cálculo. Ahora ya
es posible realizar el proceso de toma del terreno, diseño de una obra, cálculo de encaje y replanteo sin
necesidad de acudir al gabinete. También se pueden realizar modificaciones de proyectos in situ, e incluso
gracias a la multitarea realizar, por ejemplo, un cálculo de movimientos de tierras mientras se está
realizando un taquimétrico.

### EVOLUCION DEL PROCESO INSTRUMENTAL

- Actualmente la relación entre el proyecto y campo, aún se realiza mediante el siguiente proceso
instrumental:

```
Replanteo
```
Levantamiento

Se puede observar que la libreta electrónica sirve principalmente como intermediaria entre la
estación total y el PC, donde se encuentra definida la geometría de la obra. Para introducir el terreno es
necesario capturar los puntos de la estación total mediante la libreta electrónica y posteriormente
volcarlos en el ordenador. Una vez encajada la obra, será necesario calcular y transferir una serie de
puntos de definición de la obra a la libreta. Finalmente mediante la información almacenada en la libreta
y la estación total podremos replantear los puntos de obra.

```
PC
Est. Total
Libreta
```

En este proceso se hace imprescindible el uso del PC, como elemento de cálculo y
almacenamiento del proyecto de obra. Esto nos obliga a trasladarnos hasta la oficina, que en el caso más
favorable se encuentra a pie de obra.

- Con la aparición de nuevas libretas electrónicas con mayor capacidad de almacenamiento,
mayor velocidad de cálculo y mayor resolución de pantalla, podemos reestructurar nuestro antiguo
proceso instrumental a un nuevo esquema:

```
Replanteo
```
```
Levantamiento
```
Con este nuevo proceso podemos establecer una relación mas próxima entre proyecto y campo.
Esta nueva disposición nos obliga a realizar un nuevo software, donde la estación total pasa a ser
considerada como un periférico más, que debe ser integrado en el programa.

Ahora podemos realizar un método topográfico completamente desarrollado en campo sin
necesidad de trasladarnos a la oficina. Con esto disponemos de una mayor interactividad entre topógrafo
y estación total.

- El constante desarrollo tecnológico de las estaciones nos permite actualmente una total
integración del cálculo y almacenamiento en la misma estación total. Aunque esto se presenta como la
solución final, actualmente presentan los siguientes problemas:
    - Software básico
    - No permite programación.
    - Resolución de pantalla insuficiente.

### CARACTERISTICAS DEL SOFTWARE A DESARROLLAR

```
El software a desarrollar nos debe permitir la gestión completa del proyecto,
permitiéndonos realizar las siguientes actividades:
```
- Redacción. Refiriéndonos a la definición geométrica de la obra encajada en el terreno.
    Podrá realizarse capturando el proyecto definido en otro programa o
    directamente en campo, mediante sus correspondientes editores.
- Ejecución. Al tener definido el proyecto completo de nuestra obra podemos calcular en
    campo cualquier dato que sea necesario, como coordenadas, distancias,
    ángulos, superficies y volúmenes sin necesidad de tener que calcularlos
    previamente en la oficina.
- Modificación. Podremos realizar in situ la modificación de cualquier elemento geométrico del
    proyecto. Inmediatamente se recalculará la obra pudiendo disponer de los
    nuevos datos de replanteo al instante.

```
Est. Total
Libreta
```

- Comprobación. Es fundamental conocer el estado geométrico real de la obra mediante
    periódicas comprobaciones. La correcta posición de un punto o la pendiente de
    un talud, por ejemplo, se puede conocer al instante.

### LIBRETA ELECTRONICA

La libreta elegida para desarrollar el programa es la novedosa PSION
WORKABOUT. Es la sucesora de la conocida PSION ORGANISER II, que se
creó hace más de diez años y actualmente aún continúa usándose, aunque ya se
ha dejado de producir. Gracias a esto la WORKABOUT se presenta como una
de las futuras libretas con mayor demanda en el campo de la topografía.

Las principales características de la WORKABOUT son, procesador
NEC 80x86, sistema operativo multitarea, pantalla con resolución de 240x
pixeles y memoria de hasta 16Mb.

Durante la ejecución del proyecto la libreta mostró indicios de un
posible error en la coma flotante, no obstante este problema no llegó a interferir
en el cálculo final.

### LENGUAJE DE PROGRAMACION

La PSION WORKABOUT puede ser programada con los lenguajes C, OPL y OVAL. Estos dos
últimos son propios de la marca. Inicialmente se seleccionó el lenguaje OVAL para desarrollar la
aplicación. Este es un lenguaje orientado a objeto, realmente nuevo (versión 1.0 OCT 1997), compatible
con el VisualBasic de MicroSoft. Se caracteriza por ser un lenguaje de alto nivel, permitiéndonos gran
libertad de posibilidades en el desarrollo de aplicaciones. Pero se optó finalmente por utilizar OPL pues
éste permite una mayor velocidad y sencillez de programación. Además la PSION permite desarrollar y
compilar programas en la misma maquina mediante el lenguaje OPL, facilitándonos la creación de
programas en el mismo campo.

OPL es un lenguaje de quinta generación, creado para maquinas WORKABOUT. Comparándolo
con su antecesor, OPL para ORGANISER II, son muy similares aunque difieren en el aumento de las
posibilidades gráficas.

A la hora de trabajar con OPL se agradece la facilidad de crear rápidamente un interface del
usuario agradable e intuitivo. Es especialmente fácil la gestión gráfica aunque queda reducida únicamente
a rectas siendo imposible crear arcos, circunferencias o cualquier elemento curvo. El problema que se
deriva del trabajo de programación en OPL es su costoso depurado mediante el software de desarrollo o
ODE. El ODE no proporciona los valores actuales de las variables, ni permite la introducción de Break
Points ni el seguimiento del flujo, dificultando radicalmente el depurado del programa.

### PROGRAMA

El programa realiza todas las operaciones estándar, como las comunicaciones con la estación
total y el PC, gestión de ficheros, lectura y escritura de ficheros ASC-II, manejo de coordenadas UTM,
estacionamiento...

Las principales novedades se centran en el cálculo del cajeo y todas las posibilidades que se
derivan de éste, como replanteo de los puntos de la sección transversal, cálculo de la superficie de los
perfiles, cálculo de cubicaciones, presupuestos generados de los movimientos de tierras y dibujo de las
secciones transversales de obra.

El programa además, incorpora importantes mejoras en el levantamiento taquimétrico, toma de perfiles,
replanteo y comprobación de taludes.


### TAQUIMETRICO:

```
Opción de Etiquetado. Actualmente para conocer la naturaleza del punto levantado,
introducíamos en la libreta un código. Este proceso se hace lento, pues debemos teclear un
código para cada punto. Si el número de caracteres es reducido el código puede ser poco
descriptivo y si contiene gran cantidad de caracteres el proceso de introducción se alarga.
Además si el levantamiento esta constituido por puntos de la más diversa naturaleza
necesitaremos una gran cantidad de códigos.
```
```
Este problema puede reducirse en gran medida sustituyendo los códigos por etiquetas.
Inicialmente generaremos una biblioteca de etiquetas, que son literales de un máximo de diez
caracteres, que indican la naturaleza del punto (Vaguada, Collado, Linde, Camino, Vértice....).
Naturalmente podremos crear, borrar y visualizar las etiquetas en cualquier momento.
A la hora de tomar cada punto
del taquimétrico, solo será necesario
pulsar la tecla de la letra inicial de la
etiqueta que queramos asociar al punto.
Con esto se visualizará en pantalla el
literal completo. Si la etiqueta que se
visualiza no es la requerida se procederá a
pulsar nuevamente la tecla de la letra
inicial, así sucesivamente hasta completar
el proceso. Una vez seleccionada la
etiqueta, pasará a formar parte del fichero
taquimétrico.
```
```
Opción de Sesiones. El punto puede quedar perfectamente definido por el número de punto,
coordenadas y etiqueta, pero sería de gran ayuda disponer de una localización temporal del
punto, a la hora de la elaboración del plano.
Es decir, dividir temporalmente el trabajo en
sesiones, indicando a que sesión corresponde
cada punto. Cada sesión almacena la hora y
fecha de inicio, un literal y el número de
estaciones y puntos contenidos en ésta. Esta
opción nos permite tener una valiosa
información extra sobre el punto, que en
levantamientos extensos puede ser de gran
importancia.
```
```
Información Extra. Podemos conocer en cualquier momento, nombre de la estación, fecha
y hora de inicio del estacionamiento y número de puntos radiados desde la hora de inicio.
```
### PERFILES

```
Asistencia en el posicionamiento sobre perfiles. Durante la toma de perfiles desconocemos
la situación del perfil en campo pues éste no suele estar previamente materializado. Esto puede
dificultar nuestro trabajo, pudiendo encontrarnos fuera del perfil o solapando terreno que ya
habíamos tomado. Al seleccionar un PK, el programa inicialmente verifica si el perfil fue
levantado anteriormente. Para tomar correctamente el perfil necesitamos tomar los puntos de
inflexión del terreno de la alineación del perfil. El programa opcionalmente puede verificar si el
punto se encuentra en la alineación. Si esto no sucede se calcula la mínima distancia a la que nos
encontramos del perfil y su sentido (AVANZA/RETROCEDE) respecto al avance de la obra.
Una vez desplazado el prisma la cantidad y dirección indicada se podrá leer de nuevo el punto.
Este proceso se repetirá hasta que la posición sea correcta o el topógrafo la considere tolerable. A
continuacion si el punto cubre una zona del perfil ya definido anteriormente el programa lo
advierte invitando a alejarse del eje o acercarse a éste. La cota del eje se calcula
automáticamente, mediante interpolación, al cruzarlo.
```
```
· Punto Visado: 1008
· Etiqueta:
· Observaciones:
Opciones Info Leer Pto
```
```
Vaguada
Collado
Rio
Farola
```
```
SESION Nº 37: Margen Izq Rio.Manuel
Inicio: 16:25:05 28 / 05 / 1999
Nº Est: 5 Nº Ptos: 523
Nueva Continuar Revisión
```

Eje
Perfil

Punto Leido

Punto Teórico Mínima Distancia

### COMPROBACION DE TALUDES

```
Asistencia en la comprobación de
taludes. Durante la ejecución de un talud
ya sea en desmonte o en terraplén, es
conveniente comprobar que se está
realizando con una pendiente constante e
igual a la de proyecto. Esta opción la
realiza el programa comprobando la cota
teórica con la cota tomada en el talud.
Inicialmente se situará el prisma en un punto del talud y dentro de la alineación de un perfil. Se
indicara el PK y el lado (IZQUIERDO o DERECHO) donde se encuentra el talud.
```
```
Talud Proyecto
```
```
Talud terreno
Cota proyecto
Cota leida Correccion de cota
```
```
Distancia al eje
```
```
El programa indicará el tipo de talud (DESMONTE O TERRAPLEN), la distancia al eje
y la corrección de cota (SUBIR o BAJAR). Si el punto está fuera del perfil se indicará la
cantidad a avanzar o retroceder para situarse dentro de éste. Si la cota del punto tomado coincide
con la cota de proyecto el programa indicará la correcta posición. Si el punto se encuentra fuera
de los límites de la planta del talud, el programa indicará la cantidad mínima a alejarse o
acercarse al eje, para poder estar situados dentro de éste.
```
### REPLANTEO

```
Opción replanteo. La opción de
replanteo nos permite acceder a los datos
de replanteo de cualquier punto de la obra
de una forma rápida y cómoda, sin
necesidad de cálculos previos. Esto se
realizará, indicando el PK del perfil y el
lado (IZQUIERDA o DERECHA) donde
se encuentra localizado el punto a
replantear. Seleccionaremos el punto de
```
```
REPLANTEO PK:8860.Arran.Tal Izq
Distancia al eje : 24.38 m
Azimut : 125.346 L.H: 210.
```
```
XY: 486935.689 , 7654332.
Z: 356.
```
### PK: 2240 .TALUD IZQ. DESMONTE

```
AVANZAR 1.35 m
COTA: SUBIR 0.15 m
Distancia al eje: 15.25 m
```

```
una lista desplegable que contiene los siguientes tipos: Arranque de talud, extremo de talud,
```
## extremos de cunetas, pie de talud, berma, arcén, calzada, eje y arista

```
Seleccionado el punto, el programa calcula los datos del punto y datos de replanteo,
visualizando: Distancia al eje, coordenadas y azimut y L.H desde la estación al punto.
```
```
Una vez leído, el programa indica las correcciones angulares y lineales que deben
realizarse para posicionar correctamente el punto. Este proceso se repetirá hasta que la posición
sea correcta o así lo considere el topógrafo, momento en el que se dará la conformidad pasando a
pedir un nuevo punto.
```
### OTRAS MEJORAS

Se prestó especial atención en crear un interface de usuario agradable e intuitivo mediante menús
y ventanas desplegables, opciones, preferencias...

Para una mayor reducción de datos accidentales, se realiza un chequeo de los valores de entrada,
verificando si se encuentran dentro de un intervalo comprendido entre un valor mínimo y un máximo
posible. Así nunca se podrá introducir un azimut de 415g o una distancia de –54.230 m.

Para una comprobación visual del encaje correcto de la obra se pueden visualizar por pantalla
todos los perfiles de obra a intervalo constante.

El programa avisa, mediante mensajes, cualquier tipo de información, que aunque no es
obligatoria para un correcto desarrollo, si ayuda a mantener una mayor interactividad entre el topógrafo y
la maquina. Por ejemplo en la toma de puntos del perfil, al cruzar el eje se visualiza un rápido mensaje en
la parte inferior derecha avisándonos de este hecho.

### CONCLUSION

Con este proyecto queda demostrado las posibilidades que nos aportan las nuevas tecnologías.
Aunque el desarrollo de la topografía clásica es apreciable, vivimos unos momentos de cierto
estancamiento en comparacion con las nuevas herramientas como el GPS, el SIG, la Teledetección o la
Fotogrametria Digital. La única puerta abierta a una revolución de la topografía clásica es su absoluta
automatización, integrando totalmente el ordenador a la estación total. Con una pantalla de alta
resolución, y disponiendo de la suficiente potencia como para ejecutar programas tipo CAD, podríamos
resolver el método topográfico desde un ángulo mas gráfico que analítico. Estaríamos en la llamada
Topografía Visual Asistida. Integrando el GPS no necesitaremos confeccionar redes de apoyo para el
cálculo de las coordenadas de las bases de replanteo. Si además se permite la libre circulación de datos
mediante la conexión a Internet gracias a un GSM, se puede realizar un seguimiento remoto desde una
oficina central, disponiendo de información en tiempo real.



This is a offline tool, your data stays locally and is not send to any server!
Feedback & Bug Reports