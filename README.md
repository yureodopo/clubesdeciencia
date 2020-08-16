# Comparación de medidas preventivas para *SARS-COV-2*

<img src="https://www.gob.mx/cms/uploads/document/main_image/80552/Covid-19-1.jpg" width="400" height="300">

# Subtítulos
- [Introducción](#Introducción)
- [Marco Teórico](#Marco Teórico)
- [Datos](#Datos)
- [Conclusiones](#Conclusiones)
- [Video](#Video)
- [Equipo](#Equipo)

# Introducción
<span style="color:red"></span>
El *Covid-19* es una enfermedad infecciosa causada por el *SARS-Cov-2*, esta enfermedad se ha extendido alrededor del mundo y ya ha cobrado la vida de miles de personas, sin duda supuso un gran reto en China y posteriormente alrededor del mundo desde que se tuvo noticia de los primeros casos confirmados en Wuhan capital de Hubei en China. El modelaje matemático puede ser de gran ayuda ya que de esta manera podemos tener un mejor manejo de una pandemia, así como poder determinar la eficacia de ciertas medidas impuestas. Lo que aquí se muestra es el modelaje mediante cadenas de Markov de las diferentes etapas en la que se ha llevado a cabo la pandemia en México, se utilizó el modelo SIR el cual los estados coinciden con la transición por la que una persona puede pasar en el desarrollo de la pandemia.

# Marco Teórico
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

Cabe recordar que a partir del próximo lunes y hasta el 20 de abril, todos los planteles de educación básica, media superior y superior a nivel nacional suspenderán clases para prevenir.

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

**Diseño:** Es un estudio transversal retrospectivo para determinar la comparación de medidas preventivas en dos estados para *SARS-Cov-2* la información será recopilada de la página de estadística de la secretaría de salubridad mediante la identificación de variables por medio de cadenas Markov para determinar nuestros modelos relacionadas con el tema de investigación.

**Sitio:** Colima y Ciudad de México.

**Periodo:** Comprendido del 23 de marzo,17 de junio y 29 de junio.


# Datos
Los datos recabados estan en el siguiente URL: 

(https://docs.google.com/spreadsheets/d/16THYBJuzGIXUjoXdccNhuNpeCLrTRWs0Ocy9T_Mu9iA/edit#gid=0)

Las graficas obtenidas con los datos estan en el siguiente URL: 

(https://drive.google.com/drive/folders/1bbnZskNwCXv5INAJgtaA9EibB3Y8m9rG)

# Imágenes

CDMX FEBRERO:

<img src="https://lh3.googleusercontent.com/-0rKIjdd6EYlRHp7gOuVyYJ0d1XgrWtoRWlWIxnuBEnbyyqdOKIiBxNoX3o9_JeY-Oy1TUZwVp0YTm08RgZwMWG9q0zMn5sdEM9RxSuuCZ_lA9nhgd73CAi4rC0zz8T8BfVobHHzCc9jqSBQtc-cYlbXeBIdvtDOeJ_0SK2bW3FdcSmABvbfr-zRVPTpXt-GmlC1kCgoRk-edIRhGS8RSBM3naz0o62E7h8bKEJRvOdsYr7XHlh03AY7-KjsjQVXQMYAKWEc4N-gtMa0rcprLzDCJzY5kqGWaK4W-QYo2gQ3l2AnXT6NbzHJRgvOZSk1aTVqx72bYjhlHSrBugA3k-wMQIhFXNwcCabCgTh19py3w2HobwLuIO3N_TvyeTOIOuvbyTMXwVa3xzkidlK2TA7GOkdujTAqJ6OfPc-XlYrhCPjWHKYULhxiQw93aAVfW4kKGxc9_TDOpCtLPIXAA2n5p00riW5gU27oEF7XCy6Cm63yztLd-o_aSlvtXN_b5MtlXB3NHGTVQhU-p9OFJTg-pKrDKn869kHWnaGGbHkrurwYEGMDToNHzGGzG2M4qFVvjWLUa9_Of3dD9tDf_PhOs88HQWRbpHp1WnKgXqtl7vPrxGdqYZEAr2aLoofdvG2ko2QDkCxe7PaACT7sCfWR0A5UoraWV7t2NYcYga2WulhqjGisWG2JpjSh=w372-h248-no?authuser=0" width="301" height="200">
        
  Las probabilidades del número de personas susceptibles disminuye (azul) , las probabilidades del número de personas infectadas se mantiene constante (naranja) , las probabilidades del número de personas recuperadas aumenta (verde).  


CDMX CUARENTENA:

<img src="https://lh3.googleusercontent.com/d_o8W0iLYtNYPJayMRXo9VMczJX_XGTClXhgSDWx79_oypmBQSrr-ZYD8YkkfB3MA_WucS4j6AOFwgNTD8LGJmHV6CNYnZKykwQMnKp8x-0tYDxKXyuO12qrC57tkLi7cSwg7jVgYu-ug4in9_6YQCiFIqnrNa4iUiolsjhLAAbk3_5pdLe9_Xw3pZc7-sQULqjZUI1hYO_PVT-uOpg2XGGwtRQwyM2MArrITDDNubufRfa-6p-ezxUIRJWzIOkPQ3j1vVS3o2Tgb7IXOshY6bYYmBvfhrb2-GtRylhiZWZXGPE7JQAsj9crp2CUiSIl0_oqK_isTMC-FRm-H6lKknkxRJAJ_70JuNaWwOEx2gM7fbAtv9nHAWByJL1gvzkdcoYEIAR9uNwa1RZqaOyFTTBSWcP6JrEslJcHV9ADCr93ObkqnSLKNR75XhexIYKyY-WMoFyx_4yOMYJA6onzn4XLmjifxMMswtbyzxzq-FmYV_StbZsYZ_JF35t1CSFDbf6oEBOsG9dtNyka2rv_mC35iyT-q8w-AR1W9R7FP6hJKY6HFH3jyzkk52Ci0EHVFcfgzD7TQWPxFDyLm9p_9Dh4l3ZmGFQxnn6acqyYZekusMrnnudXuJk7VVW-QhSSiUcjyWRHQakxcazcgOSuGhygcS5oQ7pdpgx5OqfSN5owXDQEt4IXT6UZF2bd=w372-h248-no?authuser=0" width="301" height="200">
           
  Las probabilidades del número de personas susceptibles disminuye (azul) , las probabilidades del número de personas infectadas se mantiene constante (naranja), las probabilidades del número de  personas recuperadas aumenta ( verde).

CDMX SEMÁFORO:

<img src="https://lh3.googleusercontent.com/ag569UVGy7FYnSFFEhi0vm7iNLZRcT-ijgq568szfZ-JVCAhd8quK6ROwFTB116X8K-dIKxuetCDT1UvQqlaxLhiMFAz58Zkt5bVxNoqFqGw0uS744w2qm5zfHUx6DuMLa1ub0qOrPYxRYlGxUnyIZbQ-EuXzTXASYcrxGTIX4jN5FWUSMPJO9mFw985Qnhr2MxZ8X5n7pyA5LyV-1Lz7At2rB4jQYiRywPp4Gs6YkObyFLdjqEZQnEblwPdsc5G4jHCjGLqyh-p3pBJldQQu62ZfqGuW6D795c9GBXCBfg0bVy_QXhiwBaRGEpppUXL7D5xxLLrfRFFzLNFcASPwL4Yl-4qHdieMppFKVzOYbcXZTvBEZoaJUMqxe5QhKFgfbtFPqzmdzgU0m7jBbHP9RxT1BvrmFd8_ck3_IxhMBVO263tTAtcp1SFl5-xR4nm0uLahXENGdGkTJbgYhTNifcVWTUuOL-Qd6II7bBYaalfu3Lo7_MZyTo2CI5go2B1YC8zDv85fHqCJnua6SC3ky1bJ1kLqDa2QtTofIdJshlJdRHyrUsWmSY3zYcTwkqxj5b0QGDsQacrrfjjqfultibwgoxsH66KUQ_kFskl5ueVAxRvndYZHt3cjAPKebIrfk9YJU_QvCui5_ORvj0xZlW0ABV_qo-Kp2Qv1a6T-mXJNYvcs2Y4KxJ1NcB3=w372-h248-no?authuser=0" width="301" height="200">
           
  Las probabilidades del número de personas susceptibles disminuye (azul) , las probabilidades del número de personas infectadas se mantiene constante (naranja), las probabilidades del número de personas recuperadas aumenta (verde).

COLIMA FEBRERO:

<img src="https://lh3.googleusercontent.com/eHrkj1rfInhhkXfFTsRu-fSB1zQVOK04P-uCfF6Gw9Vi61vewBqYn_7yN-pNAez9qMcC9OcbG0mIq-RpIg-RXYxFbHZ_LXx3qFHpsjbZ9T-am-jpUoB77AG6DqFxS26j9pymtbU2JaoNvzgKQrX-i2YBY5deRgCmXDyEaRnifDQnwn9kodHaGm7AuWftBAaIZ9JW7tdmb5ZqLDoBFXnTZ-vY5SGlPKc_zA5-jaQ9JlUd5LasqQB0IM1OtaoI866f7QdPPnycZpGSKTwwMXLeIzK-Lz6hdou7e4nGbHeWsa8kzk1DS4NzD0fJP5osQlu-GjVEZI2HKhAife0cVsGtr-JpqDsYLyR8lWlVASSLN2gp1yAMU5PHXYR9pNyWFvVFhah-0Wqk8JK3Dp-raGFoBOmcMTIyeiPhOBU7P-LLP25CVX-Zxc51RZuTRCjtVFaFjkNfOXaOkkfTeV0WqThLGlIghmamKPhgqM_aOl-sL9tNE8yaNcuop-G6M2YTuOrU-MhrI3nBaxpC2vVS2OQWUZbhEi7e1qGJaoXpDkl7T50afIogoDnC7ZlnDghFnNtFgstOnljU_y9DGm0PCgn_gsKUfKXeD8aDJz8NNu8fWAK5Vk35GcYlB-zuG5j4_1jznjcQh97LQTWMCAprzUFJ3sF9gSLi8QmCGoAVVREEnkJR-qsK281NU3w1uduC=w496-h336-no?authuser=0" width="301" height="200">
          
  Las probabilidades del número de personas susceptibles disminuye (azul) , las probabilidades del número de personas infectadas se mantiene constante (naranja), las probabilidades del número de personas recuperadas aumenta (verde).
    

COLIMA CUARENTENA:

<img src="https://lh3.googleusercontent.com/dI7veJIsZXmsIOBpsP6QqWpxVM7IjM4ZVyPekP5m8hcsy1wzmxbrx-teFqIDYw7MN5rGLn9afjAEWTjzPSM0MCt3ZTNElHmIOD9RF_kkQAZ2eYtzu_y3dJNW17yh5eOLpjVPXxK6IwIAM2Ly_4OkQBbgmz1NmGS8a4BTd-F6vKxpY2P-as27Bb-QLavB4MnIjKGX8M5VGPIGIc7ZpA6XDKBvF2Zbqs6gS0r_Un1bAlLYL79A0EmKSRDIzRgUZm-H1nRkcnbQ0Dtx2CWsyoDXci3nRqdwzQZtFa8idrpspBvM5NKDBPMAogRGsy8EIps5BhQ5XgriGToMlw7UVAI50Yh4kAVolfzfNxr8qKthVITgLxuqsL_f6RqVsjVbqYBvrc9Usqs4rdjhQVn_-KgYfOrMJWNeMPXsh4Mon19_s05rNiOkr_L611bIs7gWS3bp5eG1ELIK3R-a1v4O9Aye2-aVjPa8cRDl7wQCd3OqZxAA8stuIu3rDdlVlzWYl5tRs0wuW_0FhPv6itL3wnJ4ot2jgWTZZIjoLfRX1YBZuPv9tFsWov7Z2Q_YmJVeHSUOkbBZeTOizevfEyfn2LylET9kXXy060DiBqp_OZOk0HpWNIxtJG2KHGXJdigjsCVnjssX6jsiuu6rtjLq4EAv5Nqfv8IYjf1tgT47NbiGfpAvUC5XwJA8D6Tvd_XX=w373-h248-no?authuser=0" width="301" height="200">
          
  Las probabilidades del número de  personas susceptibles disminuye (azul), las probabilidades del número de personas infectadas se mantiene constante (naranja) , las probabilidades del número de personas recuperadas aumenta (verde).

COLIMA SEMÁFORO:

<img src="https://lh3.googleusercontent.com/Dxxbsxuk9u18tW-FB88ayhV9FYwt80fGegB6ML_z_coCsEFFbCcLYSDqpvuOJYpr1hfiTjMqbUnAjNqLDKZqKg8G3zeLXx3xIDk3X3hKe75C7KKRYTsyzm054GvFDvjU5Ai7hM7z_BGZz4Cjvq_3pGbiT4lwhPJMsETD6XZYf9NlPSCy9DXH0sqS18AEaD9AkXZHAApXCz9JreZKqkc4FVVOgO0cG_2-L-ZDQqyip6PU13x9dRqPV8lKZrwtKSXTH9YvAqj1uau6Au_Oc9NDuso4bZfkDmepBkRv6fmOgP0YcaixAW8Fvs_2PmEyO9gGx_T3qtHitY-D5esjHFY5NMosdx6pJDRoj1ep341UsAL1i-VZ3aOwPCcbF46nqRazn0XrrBx_en9aNAc2uLN1HxV4Cs4K0Xo_p8hDCjiFBskLfnQ13T2FFgz0XSG3XPSrfwwWUFsMW9tbPZtcmJezSCDBNvylDpQftNV31_hNrTzCydVhZN-vbrwY0dytgS5w8iYorRwLn1xOI8l0HjnnbH-LiTFxL-Yku_zBR1Nln34KQaUkEbmLZj60NTHx9TebJjGFj-Iwke12X6xQg19yzqD4KC-8H1uIU2noyi5GFJerERrMPKYHB12b9gjLAIUsoY7FDKrChD9rM2qHKiCBBxU7OkEVHSlT4kPEyN5Y9wAi30yiTK70ZaBCqtwY=w372-h248-no?authuser=0" width="301" height="200">
     
   Las probabilidades de que haya personas  susceptibles disminuye (azul), las probabilidades del número de personas infectadas se mantiene constante (naranja),las  probabilidades del número personas recuperadas aumenta (verde).      

# Conclusiones

En la CDMX del periodo de 27 de febrero a 22 de marzo(inicio de la pandemia-inicio de la cuarentena) era muy poco probable que te infectaras pero había una gran probabilidad de que si te infectabas te recuperaras del 0.0029, sin embargo como no hubo medidas preventivas se presentó una gran cantidad de casos en el siguiente periodo 23 de marzo al 31 de mayo, donde se dio un aumento de probabilidad del 0.0009 de que te infectaras, pero con mayor probabilidad de que pudieras recuperarte del 0.9142, lo que provocó que en el siguiente periodo 1 de junio 28 de junio había una probabilidad del 0.7047 de no infectarse y 0.8622 de recuperarse.

A diferencia de COLIMA que no es una gran urbe y se tomaron medidas más eficientes tomando las estadísticas en la CDMX, aunque debido a su poca población también era más difícil su propagación durante el 1er periodo hubo una probabilidad de permanecer sano del 0.1199. El segundo periodo reflejo los efectos de contener el virus y reducirlos a casos regionales con una probabilidad de infección de 0.0001 con la ventaja de recuperación del 0.9097. Por último, en un cambio de estadísticas solo subió un 0.0004 la probabilidad de infectarse a diferencia de CDMX que subió casi 30% aunque con un descenso de 0.8524.

En la hipótesis planteamos que los estados no proporcionaron medidas concretas para la disminución de transmisión del virus, hecho que queda confirmado en la CDMX pero que da un gran contraste con el estado de COLIMA, parte de esta abismal diferencia es parte del hecho de que CDMX tuvo el primer caso de toda la república mexicana y que COLIMA se mantuvo intacta hasta el 20 de marzo del 2020 tiempo en el que la secretaria de salud ya había dictado medidas preventivas, debido a esto tomaron medidas correctas a tiempo con un confirmación a la par que la CDMX.

# Video

[<img src="https://lh3.googleusercontent.com/upf8TMSwp4yUvvXjaQo48LiBBNmNqs3k5vN4aqx5r2G7nJG61bwJv60j20Hic749-avjNqvMIdCK9UHJA3X1vLAIHSAfZpu5VHTl8y-Qjg1wcipRuZLdSd0FNknYl_YI9e6VgRyAJUL5shr7OtLqBLfgO8Ma-qj3txu5N8GTjd62hBbl3ObkaDrgpy4e4vPT9gDLQx4n0kgx-ZK_zVInFvfcOZckNLJZtaPLFGRF9c12-IGNzhH7pGoy8YSCwnj3xpnDKB4SPrzFSRDaoIOMNzypSFaFgqpkBa-slk9pPNB58zkeGvfgQZAanEroSDdMfz7uo5Aqk9VPmv1Xfl9lImEA8tTdPmQe_F2hUqcJD3lWfzwnMKZzM0vQm44FGvkNMUp8h16dRGllXBmALb7XnS9b2lhzVUNMrZ8K8wgrRJThjqN1NJJMXDjNAA5qim3ffZoXzf5L9HzhtgOnlA2WMekMsAwUsbqk012T40xiv7d5RACVpFvfsrrrZIsqCK2vbdCKD15ra4jnK90z9x9TmKx9V-2emQ9H-uJejE4z9CPMCzUmqemy6uuzP__uGMTEfKax5_Pf0GBGSyn33huWunmjVjvknz1E_AFt4_WCNyhjwP-xfNB68Hp28_xLnYPUGyXuRLdo01KfUt-Kb-5YpSJoB4xblcp4x6my9nSbufY2xXMm5B-dUZT-s-oW=w332-h155-no?authuser=0" width="401" height="200">](https://www.youtube.com/watch?v=e-wa92AoaiA&feature=youtu.be)

# Equipo B-8
## - Félix Emiliano Hernández Pérez
Preparatoria (felixe.hernandezp@gmail.com)

Hola a todos me llamo Félix Hernández, estoy por comenzar la carrera de Ingeniería Química Metalúrgica en la UNAM, estoy muy interesado en la parte química y biologia aunque también me gusta probar cosas nuevas como la programación y tecnología, y la situación actual puede ser de gran ayuda para todos para mejorar diferentes aspectos por lo que me gustaría formar parte de como ayudar a las personas, es mi primer Challenge! Gusto en conocerlos!

<img src="https://www.clubesdeciencia.mx/static/theme/mx/logo10241024.png" width="200" height="150">

## - Abigail Sánchez González 
Preparatoria (gail.gonzaxd@gmail.com)

¡Hola a todos!
Mi nombre es Abigail Sánchez y  recientemente concluí la preparatoria. Estoy interesada en temas relacionados con las Ciencias Espaciales y la Inteligencia Artificial , pero  soy bastante curiosa y me gusta aprender cosas nuevas todo el tiempo. Participar en el  challenge me pareció una excelente idea por el hecho de aplicar la  programación a problemas actuales.:sonriendo:
Además me  gusta mucho conocer a personas apasionadas de la ciencia y será un placer trabajar con ustedes. :corazón:

<img src="https://www.clubesdeciencia.mx/static/theme/mx/logo10241024.png" width="200" height="150">

## - Jimena Martínez Ramírez 
Preparatoria (jimjim.14@hotmail.com)

Hola soy Jimena estudiante de preparatoria me gusta programar. Tengo conocimientos básicos en Python. me gusta la quìmica y biologìa.

<img src="https://www.clubesdeciencia.mx/static/theme/mx/logo10241024.png" width="200" height="150">

## - Kouthumi Mondragón Figueroa
Preparatoria 3er año (goexta@gmail.com)

Hola soy Kouthumi Mondragón Figueroa, soy estudiante de preparatoria 5to semestre estoy en el componente de salud. En programación solo tengo lo básico del curso de python aunque me costo mucho terminarlos pero si es necesario seguire aprendiendo mas cosas para poder programar sin dificultad, me gusta mucho biología y en este curso espero poder obtener conocimientos que me ayuden para poder decidir mi carrera, tambien espero conocer a nuevas personas.

<img src="https://www.clubesdeciencia.mx/static/theme/mx/logo10241024.png" width="200" height="150">
