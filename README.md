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

<img src="https://lh3.googleusercontent.com/g2OjAii1vOwcuFbYvrAm2HPDKDbXLelCv8CccJkB8DSjUMNsXGQizwmw97dWQ4ADN2nUCKpGiuTmo5iTs0ofW2A8Ov-IDjgzCFNk-vb4KXPqlQHI6qsB-dD7EbLJL7VgY8F5g9Nk27wyLTtEaefmlET3qhC_LJUB3N6yoQUK0j28uC4taOTxLEiIlfm0rKN8vZ-kXTUDsSIisxfXS58bSjEwCLHkD_79hwOtgW44pKwO7QqE-h7RxJLy1L61Ka0c6uPSfFRNlKl2gNLXBCOp7r4-u30xXOLP0spTpUrAXUpc5nC-AqW2Ze7_HX-699x2DPyhdZfTWrygCGxAk6eERUqB7lJpCIBMMheDxDEt51sa4FBKu7FzBR9epKTry2hFJgxUVb_GKHNodKF4sZb15wo2Zp4RR7EsLK1XRgmrcV8H3g6H223f8bbr9oVELeERyqO8aSUOoVg3h8BoC9bZaZUBgoTwPF35ajR5-h6xX6d3aF3KB9f22ToUEmro5DuOivA1rri9-7g5Jk1wpttg0xh8rUj-Os7YP2ZYKP5PgVaH0lT5yvKw06Uj4iSFsIJkQYhp5vh83dmryU-XUICtr_-kJz3bzav2aBOvh6xEHM7NTX_0p_3adIwbcN0f_hRd_E26mekTH6Vz3tc5KIF2smPNa4mlut0u3xg8vyVcDJby3ZQDa8kugcpgSE8M=w372-h248-no?authuser=0" width="301" height="200">
        
  Las probabilidades del número de personas susceptibles disminuye (azul) , las probabilidades del número de personas infectadas se mantiene constante (naranja) , las probabilidades del número de personas recuperadas aumenta (verde).  


CDMX CUARENTENA:

<img src="https://lh3.googleusercontent.com/cfWP7LlpIfdRRnl-ZeP0XkSbaneO1f6lJAjx9HA8s95esiWY0-x8DqGzqJrSfk-qG5YBvh57aqtlKgo64b0VYHCl_HcvViMqqJtCVpU2Z0Y8XlkNSrc9_K060yv0Rscz18fYXGAbIOJ-7Pji25ADhz2mEt3ZbtkEHhxQwzw_oak8iimnnLRFeFBJlBd7UBgLKSUFyn0TfS97CD75LYRGlo1LPSW5GxC3qKN4zWTL0hvgIMuiXi1OCGtaCjPsDyCzdjU52HpKBg2MeJCld0hGq1wf6PUKkb3pOmJ4PTiGwBqYCo33TrT5X4qSK753KKGdTW_HJIRxdaulF4kGlg9o3YsfG9O9XU5gpv60yxRwx3VZlcYK2cIMvqvXOedilxJgCgzqj5aRdXipBCLTtXnKom7aN00SoBON78Dt5zmSOFkR5U_n7vDruO-yC_HDBLdh3McK4LGBrkHkbKmLj0J6auXy13Hb_TWQJt3Dj2s2xWAnehdVHAWU8bK3Vr_wLmVjPxWpRncxl1GRRmetip8TcKKnr0whNEROyG1ihj1h2SfLrDFa6MaptcLvlPSswqFSOoiGJP0vizZmhlRvMHAm3ts_kqFGmdoepZXTFVI9_7RBa2G11euc3s1A6v_IIbz_hVcOa0aFUO8Ra5fTndT2YeF4uJ8AU4cKPvHPthdFjl29sZQOes7daNqHCPrK=w372-h248-no?authuser=0" width="301" height="200">
           
  Las probabilidades del número de personas susceptibles disminuye (azul) , las probabilidades del número de personas infectadas se mantiene constante (naranja), las probabilidades del número de  personas recuperadas aumenta ( verde).

CDMX SEMÁFORO:

<img src="https://lh3.googleusercontent.com/01SgdNOPraU2MmKDORPdeKm_Qqr5E930Tt_lhk3RNvN4ThhcX6SIzUDrcKjiYr-dASDbyP-lxV8jDcxC5_BtBD9hplY--FLpN6CZCitoO_35Lhl4iLHliCJeDMGhv7L82iDyOkiB9MadKXINuDT3I1wFanlHVU0v7pF5IzhER_783gWdTxmJfV-sib3BnGnkndsZWPyVSvpJZCsxtQXJNR_1zZzl4fNAY_4pNn6LMBfzlbs-3Tpw025ic9GcnavCkTv52VxGyRL33UeVjMKUQSpR5r7V2WsRdo82c1VRENX3pOxmXuvQrSIfFftTMx-h8soMOHB06qaSoGPzdrwHgx2f0udKbSb2qAl6dWVZfosZsLwAbjIBGD9sleiBbpYzuy6aZAC7-OQuUeHvL6IthXt54Axm-XZz4KljXjeCTbCxPE94b3I5DsOe5OM_F1ERDxIPrypXOGaDWDUHvCXvn7R9P-_K7JMtOCTuy0Y0HDeeyx7noXtE4grjqz246S6uGVnOvP7tl-3TEGlzY1bEL6U9df-QMdiqYRDAX7HHiYaV-nvw8znFPHvoerOa_RI8GT4YrYq56D8AX4wAUowBvQsD1UagAaTX1v8JIxBndx7atqyoZh438jh5RGyDVTBnt3JJU_V1mo4yYLW17hjcyWXQcALLzwudOK9Kbv2q1oGLk8KwS1Mv4Joa3AqF=w372-h248-no?authuser=0" width="301" height="200">
           
  Las probabilidades del número de personas susceptibles disminuye (azul) , las probabilidades del número de personas infectadas se mantiene constante (naranja), las probabilidades del número de personas recuperadas aumenta (verde).

COLIMA FEBRERO:

<img src="https://lh3.googleusercontent.com/1dVsDUMs3vQwbrAteuXwtaVf2alWOGc91sDyWneRX3fRmRFBNuMXJM1mg4PgQoz5BV9kbUYolrmWgsXrVWJgN1rQ7-gqHZHVSdLCtD_H2hY5CIm7FfCMS31r9gdQ3-E5cE253FrRg8c0Xz3bA7K7rmRutAt1hhzAdVmzGRn-UBcBc3Lyq7mA1uoc9QGiN5du0Y5SIDqyEDU1dqd-4rgyB-S6JsDLiVxzkedMUa1yCUA2bTGDWSkDyjjZb9lSGpsfIh-X6eclh0Y4o4lxOdM_UKLaLZq8OQhieKaJOhKQySwjqGNSQPn2cLoqPX6jYMjIz2r65Jp0AoL-2beojeHKKqcr8FQ43CERW56zecg7UwCSaPGYSaoeaBDgKMDeM4Oo9j-Z9HoJzkfT5nbXVHyXUYUaXcjTHkiR2YMIPY_Vr0NFMDSZytmhaImC_LAdke1TBNXmekPoYYKQXtBGw6XKz84PEUzgZOwvIIqG1Qz7fP67dpcz3vaBqJZia3MSGW55Oh3wzVMCas0ZWl2yydQIlgfLzcN6-7eaEavO-Khdqs4jgB-BR-HnwIvODh82WT0eTv3qB0ocDicWiZ99mPlCm3jWjI4adxl6QtVKZfTmYb9cQkT08PYTcmnvNkJ2vvaLWr50LlC8w9J6GfVHlThjjoMy8LQVGD8zUFFr3lHIoHPdexH88DZFIiSWW85k=w496-h336-no?authuser=0" width="301" height="200">
          
  Las probabilidades del número de personas susceptibles disminuye (azul) , las probabilidades del número de personas infectadas se mantiene constante (naranja), las probabilidades del número de personas recuperadas aumenta (verde).
    

COLIMA CUARENTENA:

<img src="https://lh3.googleusercontent.com/XeFTVjZka2MP5UaL_gyOiwg5QVbaEM6y8ZN15Tpj_1_3WEGehsrktoFC7RL8mbSr183PJ-zj5m3TFxYWB_SzbnIBJvHSWK-hE36pvK26X-dTGKq2UDoexZP6vhfwt474QmaNh1UW4XKcsyCEAoedskEvYca7fKPgCdacWAuUQvtjTmcAeHbivKLrwgYoGz55hv6X4mBAVTWlQFtkBt4qr_87LWCOWq_MMwXI1aqZFuvlUEAhFbl0Qxf10cdQWo5Buvfvle8mkeyIm3lZ7dsHsBI_n85FIS9ZbpX3KUnAW2Hd1Gjvk7SO15e-Tw1fs2G6759eu-gllEs9dxaDZUvZ-4J96WziycI10gqDGgre0F4b9smWoHmQBUewsxPCOwrUDsKVpGxX0qSTFN39HQBgALvjorJPS0HDGnUYWmBbY4ctq58ZaCbA4o1hwRcV-idrejwEk9P3ATCB13781pDgUsDzZtBYQFhGzACl-Wct-rgcpwwEdbJKlYk9G3BnD3uQAOXU9GA8GWGM-kHS7BMQlkaBdKRs4vBXlHuBYJXHKkw5QOj9Q43SKhaHgCsw4LTGFcneW5IHqIrmaZ0FFoz7Q-ImPZiaZVP7jMWXWFNX9RlJqmg0SBoVVWir9QKcI5n-Q2LomiCT0_Tkct2cAcUhb-7oQDCiwMSvfCRDO3FxZTT7OWs5VvCsS7HgQ_y5=w348-h232-no?authuser=0" width="301" height="200">
          
  Las probabilidades del número de  personas susceptibles disminuye (azul), las probabilidades del número de personas infectadas se mantiene constante (naranja) , las probabilidades del número de personas recuperadas aumenta (verde).

COLIMA SEMÁFORO:

<img src="https://lh3.googleusercontent.com/behRyvYb5kPc2oQI_yiAihPAsSfxfzqsxqdhH-m_MXfMmdDigWqpwusuavMa29JE4aql-G32uQRd8Gvq161ZhD4cvkz3xV0RbIb3i5NZh6pJvdkgqGQYLyehtf-8EMFXKb4-DHph3o0IdGM_UPfDTdqgVoXCJHW3GP_mQvuHqjixhPPtqhtMhTS5SzUO6BPHZsTTB_LLPcEtX1IymowdtKgjpgdsUYRMVdtyUZST4kNZPSkcFSsngiSyPtSsg6LR-Pygd3a084BsnUyPtX17cA8HwqGt9V8Fh_fjpI4BeCcUdcIQzvJqLyvmgNrRAZeqo_B7IBSN9FkE4Baf2-M5i1_Knkfk7wYiaOBuY08-sKRTCOqnzziR6RYEEYrGm_ePDkxv9qXtStFUIjc6S6cz4qL-fbdG9zi3Ecw0CJRDjKwI39JEvTFv1Mp5XGSe6nVCEnNclRqULoIwYdPdoLN-5nVieO-nTof4cttJVUbyCdFnSwZ4RkBq4WLvDXsgmYU0En2If0mf-LSPX1xiJPfqROC0qEzj9Z13OkrvzbqvrHJnleYVdWcOpwY_ZOqJIhgLJnWrYJS3AZ7bWexYr0QL3QRNtYhiLPnbQWctlQpquVbeQEy8xPmVC2Wc7Ltoz1yr5w4yjTY6g3ehtLvZqRpzbzr0mze7trNl12FAcgxU9Byh9McAPM8xRAwkiZdU=w372-h248-no?authuser=0" width="301" height="200">
     
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
