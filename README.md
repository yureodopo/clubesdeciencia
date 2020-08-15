# Comparación de medidas preventivas para *SARS-COV-2*
# Subtítulos
- [Introducción](#Introducción)
- [Marco Teórico](#marco_Teórico)
- [Subtítulo2](#Subtítulo2)
- [Datos](#Datos)
- [Conclusiones](#Conclusiones)
- [Video](#Video)
- [Equipo](#Equipo)

# Introducción
<span style="color:red"></span>
El *Covid-19* es una enfermedad infecciosa causada por el *SARS-Cov-2*, esta enfermedad se ha extendido alrededor del mundo y ya ha cobrado la vida de miles de personas, sin duda supuso un gran reto en China y posteriormente alrededor del mundo desde que se tuvo noticia de los primeros casos confirmados en Wuhan capital de Hubei en China. El modelaje matemático puede ser de gran ayuda ya que de esta manera podemos tener un mejor manejo de una pandemia, así como poder determinar la eficacia de ciertas medidas impuestas. Lo que aquí se muestra es el modelaje mediante cadenas de Markov de las diferentes etapas en la que se ha llevado a cabo la pandemia en México, se utilizó el modelo SIR el cual los estados coinciden con la transición por la que una persona puede pasar en el desarrollo de la pandemia.

# Marco teorico
## Semáforo
El Semáforo de riesgo epidemiológico para transitar hacia una nueva normalidad, es un sistema de monitoreo para la regulación del uso del espacio público de acuerdo con el riesgo de contagio de COVID-19.

Este semáforo será estatal y está compuesto por cuatro colores:

<span style="color:red">Rojo</span>
Se permitirán únicamente las actividades económicas esenciales, asimismo se permitirá también que las personas puedan salir a caminar alrededor de sus domicilios durante el día.

<span style="color:orange">Naranja</span>
Además de las actividades económicas esenciales, se permitirá que las empresas de las actividades económicas no esenciales trabajen con el 30% del personal para su funcionamiento, siempre tomando en cuenta las medidas de cuidado máximo para las personas con mayor riesgo de presentar un cuadro grave de COVID-19, se abrirán los espacios públicos abiertos con un aforo (cantidad de personas) reducido.

<span style="color:yellow">Amarillo</span>
Todas las actividades laborales están permitidas, cuidando a las personas con mayor riesgo de presentar un cuadro grave de COVID-19. El espacio público abierto se abre de forma regular, y los espacios públicos cerrados se pueden abrir con aforo reducido. Como en otros colores del semáforo, estas actividades deben realizarse con medidas básicas de prevención y máximo cuidado a las personas con mayor riesgo de presentar un cuadro grave de COVID-19.

<span style="color:green">Verde</span>
Se permiten todas las actividades, incluidas las escolares.

## Jornada Nacional de Sana Distancia
Debido a la propagación del nuevo coronavirus en México, se han implementado medidas preventivas para evitar el aumento de contagios en el país, una de ellas es la cuarentena a través del programa denominado como Jornada Nacional de Sana Distancia implementada por el Gobierno Federal.

De acuerdo a la Ley General de Salud, se entiende por cuarentena “la limitación a la libertad de tránsito de personas sanas que hubieren estado expuestas a una enfermedad transmisible, por el tiempo estrictamente necesario para controlar el riesgo de contagio”.

La Secretaría de Salud recomienda suspender temporalmente a partir del lunes 23 de marzo todas las actividades no esenciales de los sectores público, social y privado.

Cabe recordar que a partir del próximo lunes y hasta el 20 de abril, todos los planteles de educación básica, media superior y superior a nivel nacional suspenderán clases para prevenir

## Medidas de protección básicas contra el nuevo coronavirus
-Lávese las manos frecuentemente
    Lávese las manos con frecuencia con un desinfectante de manos a base de alcohol o con agua y jabón. Lavarse las manos con un desinfectante a base de alcohol o con agua y jabón mata el virus si este está en sus manos.

-Adopte medidas de higiene respiratoria
    Al toser o estornudar, cúbrase la boca y la nariz con el codo flexionado o con un pañuelo; tire el pañuelo inmediatamente y lávese las manos con un desinfectante de manos a base de alcohol, o con agua y jabón. Al cubrir la boca y la nariz durante la tos o el estornudo se evita la propagación de gérmenes y virus. Si usted estornuda o tose cubriéndose con las manos puede contaminar los objetos o las personas a los que toque.

-Mantenga el distanciamiento social
    Mantenga al menos 1 metro (3 pies) de distancia entre usted y las demás personas, particularmente aquellas que tosan, estornuden y tengan fiebre. Cuando alguien con una enfermedad respiratoria, como la infección por el 2019-nCoV, tose o estornuda, proyecta pequeñas gotículas que contienen el virus. Si está demasiado cerca, puede inhalar el virus.

-Evite tocarse los ojos, la nariz y la boca
    Las manos tocan muchas superficies que pueden estar contaminadas con el virus. Si se toca los ojos, la nariz o la boca con las manos contaminadas, puedes transferir el virus de la superficie a si mismo.

-Si tiene fiebre, tos y dificultad para respirar, solicite atención médica a tiempo
    Siempre que tenga fiebre, tos y dificultad para respirar, es importante que busque atención médica de inmediato, ya que dichos síntomas pueden deberse a una infección respiratoria o a otra afección grave. Los síntomas respiratorios con fiebre pueden tener diversas causas, y dependiendo de sus antecedentes de viajes y circunstancias personales, el 2019-nCoV podría ser una de ellas.

-Manténgase informado y siga las recomendaciones de los profesionales sanitarios
    Manténgase informado sobre las últimas novedades en relación con la COVID-19. Siga los consejos de su dispensador de atención de salud, de las autoridades sanitarias pertinentes a nivel nacional y local o de su empleador sobre la forma de protegerse a sí mismo y a los demás ante la COVID-19. Las autoridades nacionales y locales dispondrán de la información más actualizada acerca de si la COVID-19 se está propagando en su zona. Son los interlocutores más indicados para dar consejos sobre las medidas que la población de su zona debe adoptar para protegerse. 

### Comparación de medidas preventivas para *SARS-Cov-2*

*Objetivo*

Determinar la incidencia de los casos de *SARS-Cov-2* en dos estados (Colima y Ciudad de México[CDMX]) para comparar la eficacia de medidas preventivas tomadas por el gobierno en respectivos estados.

*Hipótesis*

Las medidas preventivas que se tomarán en cada uno de los estados no serán suficientes para disminuir el número de casos infectados por *SARS-Cov-2* en la CDMX y Colima.

*Justificación*

Crear un mejor modelo epidemiológico que nos permita evaluar las medidas y verificar su utilidad para disminuir la incidencia de casos infectados, así como el número de muertes, estableciendo medidas específicas de precaución en cada estado referente a sus necesidades.

*Metodología* 

**Diseño:** es un estudio transversal retrospectivo para determinar la comparación de medidas preventivas en dos estados para *SARS-Cov-2* la información será recopilada de la página de estadística de la secretaría de salubridad mediante la identificación de variables por medio de cadenas Markov para determinar nuestros modelos relacionadas con el tema de investigación.

**Sitio:** Colima y Ciudad de México.

**Periodo:** comprendido del 23 de marzo,17 de junio y 29 de junio.

# subtítulo2

# Datos
Los datos recabados estan en el siguiente link https://docs.google.com/spreadsheets/d/16THYBJuzGIXUjoXdccNhuNpeCLrTRWs0Ocy9T_Mu9iA/edit#gid=0



# Conclusiones


# Video

[![ScreenShot](https://postmodernjukebox.com/wp-content/uploads/2017/12/Screen-Shot-2017-12-13-at-1.18.05-PM-e1513224576689.png)](https://www.youtube.com/watch?v=FyFwko9O2UE&list=RDMMlrscdXiKnWc&index=4)

<img src="https://www.clubesdeciencia.mx/static/theme/mx/logo10241024.png" width="600" height="600">

# Equipo B-8
## - Félix Emiliano Hernández Pérez
Preparatoria (felixe.hernandezp@gmail.com)

Hola a todos me llamo Félix Hernández, estoy por comenzar la carrera de Ingeniería Química Metalúrgica en la UNAM, estoy muy interesado en la parte química y biologia aunque también me gusta probar cosas nuevas como la programación y tecnología, y la situación actual puede ser de gran ayuda para todos para mejorar diferentes aspectos por lo que me gustaría formar parte de como ayudar a las personas, es mi primer Challenge! Gusto en conocerlos!

## - Abigail Sánchez González 
Preparatoria (gail.gonzaxd@gmail.com)

¡Hola a todos!
Mi nombre es Abigail Sánchez y  recientemente concluí la preparatoria. Estoy interesada en temas relacionados con las Ciencias Espaciales y la Inteligencia Artificial , pero  soy bastante curiosa y me gusta aprender cosas nuevas todo el tiempo. Participar en el  challenge me pareció una excelente idea por el hecho de aplicar la  programación a problemas actuales.:sonriendo:
Además me  gusta mucho conocer a personas apasionadas de la ciencia y será un placer trabajar con ustedes. :corazón:

## - Jimena Martínez Ramírez 
Preparatoria (jimjim.14@hotmail.com)

Hola soy Jimena estudiante de preparatoria me gusta programar. Tengo conocimientos básicos en Python. me gusta la quìmica y biologìa.

## - Kouthumi Mondragón Figueroa
Preparatoria 3er año (goexta@gmail.com)

Hola soy Kouthumi Mondragón Figueroa, soy estudiante de preparatoria 5to semestre estoy en el componente de salud. En programación solo tengo lo básico del curso de python aunque me costo mucho terminarlos pero si es necesario seguire aprendiendo mas cosas para poder programar sin dificultad, me gusta mucho biología y en este curso espero poder obtener conocimientos que me ayuden para poder decidir mi carrera, tambien espero conocer a nuevas personas.
