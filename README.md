# Comparación de medidas preventivas para *SARS-COV-2*
# Subtítulos
- [Introducción](#Introducción)
- [Marco Teórico](#marco_Teórico)
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
Los datos recabados estan en el siguiente URL: https://docs.google.com/spreadsheets/d/16THYBJuzGIXUjoXdccNhuNpeCLrTRWs0Ocy9T_Mu9iA/edit#gid=0

Las graficas obtenidas con los datos estan en el siguiente URL: https://drive.google.com/drive/folders/1bbnZskNwCXv5INAJgtaA9EibB3Y8m9rG
# imagenes

CDMX_FEBRERO:

<img src="https://lh3.googleusercontent.com/edbRP93JvZ6-E6WHRxmasYnXxLFkjQJCxPklXzN0xLzVBhxfEvk0cjZuaDmyuGkpNCVBZgYPRI1E0MppCvGTx8h4LDCizDoTN0YZHdYeLFX-7fZOcmqAxnApaOFPXbAHLfyflgHu-QXi2nHDwYm7qvdVX-XxwHCD7SZfRtPMBChVQLvOcGv8rf87Gk7SJgFkzkSfcjtmBSX8OHoOgGqqyHD598tJbDtGcJljg6hxDr9fXPyWiI2DaNPAubQS2NmMshDLclEAiAg6y_5EckFO_K8I--8MVAjWHPoKJOsC4RRCI11RR03AdWMWbysMckrlNnRC1bt3I6nWAMe2KpDjj6Fj_elFCLwU_f45PvVCl6c-7lj2kRTKzSyMQYCkGmDu8cA4LpWiUe5eaaXzPF9LOc6ahTPtWeEDx_7kPlEf4211j2NL3S3eA6aWtiZJhiIj_uKp9TGCItce59qXJUawxtSmacqE5L36UrvSZrJWlMxWCQp964GsorFUFayTDiDvqchzgRHfFpRoDUvY3_51Z8HKyjLuFPiR4CdyJeeGxm2n1on7-ECwqgQdvfWyX2c4YIqpKUCQi5AxwHMft3EoXQOy12PesMZe97MllJR0LnkJFe5laq7OmghIj9wL0CQdqfLOX50ynTj3XSaaJI0QTCLdr-MFxMN42yK-lS5AvGGMHvkbrSRJoSVS-U8f=w432-h288-no?authuser=0" width="300" height="200">

colima_febrero:

<img src="https://lh3.googleusercontent.com/k_qHOuvLHOs5mmwCpiKIQ8k5I-tXs_w65XSUL-IEE5x0EMSf4x_n8MWslDvZdBRkfKqPGWLcYY8YnchgcJcA_OnyRzhKjg9G0mCib8Xhy1CKzlTfBXxnQr80deWjHagHoC_I7frOSuVCBn-qv8Psyq1STdqmYT_DbmqpUrQ2SLYWm22y3E3thUBds8PjCLF333OB9JKXKK0vAk_sgqACo4OoRMdoFDO9BElCLKmhrhQoNfr7IPfPqIAcU5vLzXW5kSc0X6742N6756pAjCH46bO6vEauWJH7QUzM_MvW5Z5aS5PydaMvbfVggj35iGYgrwoRdxW9zzD6GCACce-tqr-lacO8lfTATakt7tuBl1H77DS5JZr-mDz3wiWUruVex3fQmGq75ETAT17yCnfDeqKaaiNS33RdvQ5axSaaa6wlXL_XY5uJhFk0MiRtX5fRtokCOcethUBwmxVK6Q7sdmqtPwnt9DIYA3zMm-1wrPxGcNrM7OQXwuGoBiZyLLNkHtgs1vtuhpZ6gIuTbtccXJaR2kINp8kNL2Xg_juHUTdGSoAdwfrjBUukz3kHkTUaj0so_mfzLWlX4-2lRnZAwLrWz_MF9BNW6t3MEfe3tlKhKs5HyuquWqfS-QEiQSYupW0xgLcCzF6Wpy8PGw8LLxNYrRJRJy69tVd3kIHrxkyUvCXIi-u_vXOpsYmk=w432-h288-no?authuser=0" width="300" height="200">

CDMX_cuarentena

<img src="https://lh3.googleusercontent.com/rrAEQpTP6it9JJAQ4FBDWbupuUxt_F4V4ewW2lK-R_KzjIE7kow_06b0F_irpt7Qteg3ttMRiBIU1Xxv3vJQBAz_1R0BOByant4Q-0moiALH2hfBCHImnl5i_qf2BD7YOVMQMqeU1ra23cZWPmv2gXSfKF-bDlle674-fF5qpiBnzM1QmQVFh-N4gzTJ4Kwuy2MEOMsAyxUKaGwh7HndTXj10TaK4A06BOPu9LhzccK6pULRYQKaM4V5sPstXCckW0EHLp52Bue-jx6h2-FrofR2080OJ4DOm3DxriLJ9BkWAD_29Htt2Bqagau_IXS1qClxKj1MVNDMyZ_IDUYxVMJeZQfcPhEPvr52AQaRPEPwVnPidmWZy4ThC8gSTzCJMyBuX6S-YsxaZGtVD7VTx8Kaw97WjonYjFwGdO9RVa-5RtkG_0Dgao1_pkhoCCxXd290QOLckCx2xSlzN-5cFivWdHzTvnlf5XIf-rKxyx4bOodFkqIa6BnxKtFA0MN8rnscNrSUV0LGiLsy53Nnwiotuyu_YaiRQkX56hHZVdcSeuxdaSoWdvOsvrLgoGoHQu-K0GLUloAUyZImAYbXKM4FI3RsE-5FToduNYfFTLnx7sgUSpwkPoUNLDNzT2NtNwfJtByQLCuXvSoxZLIlvYHEaCIuLBqeTP02TnBGFbeTetDMo5xxjHBQr978=w432-h288-no?authuser=0" width="300" height="200">

colima_cuarentena:

<img src="https://lh3.googleusercontent.com/R6gQ-Q_5OkdNgcm58oHwckXWAQ1OC91ITZZOZJQJubd_0mp6qeT03jSWIH-_tpsxdcs-SP1fgafX_yV9ROhBOcdWUJ-LgCPGtOMHHF7yDbkCktBWoOAXDZa40pPECDnAeRYXuq8wlWwlQzUnVBDtsfl4DGUibzjd9Zb1hs-NOUOKdF5ZC3fSuKBtr6VGVsDEKubYcx5JFF9ZvltXPf-rfXGgnqntJ1-54Td0eAynY-CN-ePZqZKqDEiRkkRcvMDkEGN_zaJitsrOjHSXvuNlMzv4Ou8nXaWpRPsiRVIvZR6jAjL6OD0R04eDJfAeeLliggf3uN1tIoN8vyY4KfKROL--L3vzEWA_cttbpbWI2k8H3ns15tZQRRvWmmO5e4y3ycoOe0UhOG08_e44wtNNvgc9fxlw_JN44OfhbOVFJFlzaKo7oHxt5RX9DYFvtdYjARJ5SBP0MZP4JG_qaq6HI2jvHM4YCq6yoBi0SUf21xY8cvU-wuq8-bamqvap4MRBsnG0lAskhbT2UhDItPH4o-XS23IoEBpv7-wos3Vsf2KSuKQpCiiXTwsEOaj-4QAAyIF2iBlgTOY72y1GdZOlifO1Afe7ezRMrm_wcjmVIffFCnb1DOg0bC78_mdOXZbqu0NAyQ41pelHdO9aVO56AdiPQ8aIat6uj1xRkk7PMJCYnsQFU7hcswaxUKcE=w432-h288-no?authuser=0" width="300" height="200">

colima_cuarentena1:

<img src="https://lh3.googleusercontent.com/w2lU-Zx51Ii5WkUF3MoGRV3TYyN8vgvyaJMHITKfA1Jn7-ETINeXUl89sMC7w5BlKVFbqsw3N3YGHbzptOoD-T_0-hoXUkKQdJHcyO2X-yn-u1eKvHVGDMeNwVtswRI4bh9YUiwjWpBn6CG4WviUm_fIRuk54Xp5cge7ShDnVunchybg45-CmJt5uT5I08ileXXc-02g4eov1-N-j4YL0P3sOyhZ6_5pfuEuuVmo_1A2B_IpL4_KBwY6BV_A_d_bI9oGsyA1Bo4zGrgDXrXp6zPYMMYSEU6Qzu2LgPJjbVSaHz5PVQ3oo90NT7-Vak2-1W3BcjxWoZber_6GkdFvQ2gdXiB5qgmKIQ_e97JVmnVfwlqPNTuByj7gW6B2NL45yc4YqBlsVdWJdEIggV3PpNketJhPPQc22vjMKAHkOWM0FofkbcZLPsJV_ue9gZo8e94U-Yu-EBWXrkIowKewHy4xDjhLTRQyFkgdsvudBdyKL4YEu9e9OapTVODPaD6i4S8ISVxRc_jW0eKFQPe1rwN7uWMC3zYlub6g85vhouKwxzwkW6tOZK9h21BXUCEXI6UGHbQUpAZ2a5RGpSwZXzXpHz7TkrHB_gKZUgOYjdQ1skX49ue5DUgIcMPiX4P8xqUmbcjv-tGfDT54LVaOjYDCKU8zUgYVQqyG8tv6fdll1xApyFD80LQxe6-7=w432-h288-no?authuser=0" width="300" height="200">

CDMX_semaforo:

<img src="https://lh3.googleusercontent.com/I32EdAWDNxLWXyRe7ZwYEqNb6cBHLUCMabinwdCQQZlfazIY6OZVV7M4okVAzaqlZ8CPDH7iXENi2LTC8UBv1YAFQena3sDMpLSF0VWYO0jjS4PbjYXBYwwLcpm7RUhIxnbRLb2DI4TjLphUEeMMaVYS5Pa91J6WLcHixTqny9u4ZCrcX77IeqRZ2EglpgZFJ-CuE6qd8B3GB4Vfx90L0jkOwnKuk9wqgg7erkymtsSniUpGNB6rGWVW948CR9ndXWxbUrmlFpcvZrc4hs-B6MlloA7cwc5IxcrRYhtWISFu6dhJ8GKzABoHrQh0B8r5UA3o_PehTvWGBvME0-T4vX7Rsq0wdN9fOsuE4LPqZZjr9NH8khJZYLupkrap2pjWeugmCT5DCw-GVrxiCbd56LFTbQxud49NOrQ4DjCY-3VJhQ4Yem5Z_jd2kWztFgs3cqd4mlzOwOg_uO77tElj7on9DGAR0ucFGa1FaNF9Lkz4ML1fOZW4o1E3LdzeSbV6_sEebCZVXb7za-1z8v0vsnqRDwt18G80kVWrSSdolhaL8Kyn5DmF4p5FrQox-CqC6UwU3kTGMGRdYiJwzlbTlOHuoO0NWUdVqs7dQaRLb0uW4RJ_J8PU1wSXkw-TavlRbOHlcJnkzJfrgcyUmbu1TWa9oiKkAboLNS_lLWXUFzXREBb6uKvrv8VF9vuo=w432-h288-no?authuser=0" width="300" height="200">

colima semaforo:

<img src="https://lh3.googleusercontent.com/GhiMOuVUJhCEoNxA729AvAZnZXKHu-nGAmonYe3OK9PhUxwVanM-CrDXx1Wf61_mtKkywA9PfNqh_N90j4yS0eQ3SaQjij4WWyywZu8oF95k7SzIJPiz-eguft6xkmQW17xZXZZMs2xL9dMJHYY5ZnFgDlwMksN2Rxu6UhV3-ACQ3PWV_IOVVz8f7UxDlHYz_btgP4NaFhowxvW97VRRyBQNHBc01kmR6zPJINYTT_kGpgodFtCz1q8v_nH0a9vZclewt9IAlgRVWvLxYNtHAF24aTiWrbVDlXgcm0qAYbdMnmcg_HZFuEwV-xNSTe6AdJ2TwyMYLooY8WsG1gE9BXGUA_znPnC8rWhafntr8IW0EE6WN66gZVwMeDf98dCgqo3yybihb6yy0ljgQe8bC2fh7Z1gP_YZYmlYtVIhQtFuON-3c9fL8V2N-MqDPNWygto79HEGX9a_cyAK0uG5OAfTyWwBRiznbj2NrmOjgT-TISrhZCAfgiAVq1z-fDIrhKJEdnajHRFzpME0VH1m0mcAIwlt7kU8Zv6KbdxgC0NUfroA_U4_zdJusIX53j4kliO-c1CDQVt2Rvbpq3ocWSD2u4-HtdAl_M0DAB_TZ48mT8AN6Jxu7XmXiZbrPsv4ChvkC_oX6dIkjE7Qln6cs5i1Jm5aR4IRuCd7XQpDuC8n27m3uP1cPDmhVr7_=w432-h288-no?authuser=0" width="300" height="200">

colima semaforo:

<img src="https://lh3.googleusercontent.com/Fz3SRFcGYNQaUZOCu7nuMuEE8-huSbGqtJpfITPl-ADlEHDcV7hXwqpf8ppRkMtyCq95CciDxaaogauOmuiHcYQhSNb0P1rh6aKgwop-OqYMwBx-ocaeIosySZIT7wrRpa34RgNPXnWjwxc3stMF59HyVMojjyRymXMTNzWGHwIH9XHp4GOIgEDlaol2y4HI4DGzd36CRsESV3pw_l1wdXrs-9cZ9jTQU9oWAZ6uh-ZHzGMYsxS9FvcdH_KEr94UtiotID-pzZ24UbjJ3fJ5DNmwbgjfFcTJt1dCJPXnLnMQBVjf9k6CCgahFOLTf0r1JWLfYYURZiEfJm1yg34oMDKb_OvtVAmmTUUhIYxJpeCJBos88Vw8pYPLR4qvgIaYbEj6KbB9RVuloYOzshTc2tDaks6yVqBNGHJLlf5Z6VHmkUxz5IbfgatdUlE5xysBnuxEi68GT-8ghakn9njjXFYpL_7Ure82CUNDtbhC12D2-hTFYs6QWWLlbwKPSN41z0-VvvDV7BBqTY7Z0LcmJN0c6iuOdr1klxeSh7SqR_yTqi7JdIjrE35yPw7nakjL_s_FRWP1zkFrBH2Wpug0ce49aGcwG5sTn3OtESdbMgtmdSWysv0qkRH8VbYt7VJgxsuH9GkvHYXPPefiyqpHuYJhF-tpTab-fOvWOzrTzuADaJRgiefFyyPBij6X=w432-h288-no?authuser=0" width="300" height="200">

# Conclusiones


# Video

[![ScreenShot](https://postmodernjukebox.com/wp-content/uploads/2017/12/Screen-Shot-2017-12-13-at-1.18.05-PM-e1513224576689.png)](https://www.youtube.com/watch?v=FyFwko9O2UE&list=RDMMlrscdXiKnWc&index=4)

<img src="https://www.clubesdeciencia.mx/static/theme/mx/logo10241024.png" width="300" height="250">

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
