# 3_2_Ejercicio_1

Este ejercicio consiste en resolver el problema.
Lea esta historia y calcule e imprima el número de -totalEggs- recogidos entre el lunes y el miércoles:
– Las gallinas del granjero Paco Torres siempre ponen -eggsPerChicken- huevos a las 12 en punto del mediodía, que él recoge a lo largo del día.
– El lunes, Paco tiene chickenCount pollos.
– El martes por la mañana, se hace con 1 gallina más.
– El miércoles por la mañana, un zorro se come la mitad de las gallinas.
– ¿Cuántos huevos consigue recoger Paco, si empieza con...?
• eggsPerChicken = 5, chickenCount = 3 
• eggsPerChicken = 4, chickenCount = 8 

Para resolver el problema se emplea el programa -Chickens01-, el primer paso es calcular el número de huevos que se obtienen el primer día, dado que el día lunes comienza con 3 gallinas y cada una coloca 5 huevos sólo a las 12 de la mañana, se debe multiplicar el número de gallinas por la cantidad de huevos.
En el segundo día hay una gallina más, por lo que se aumenta en uno la cantidad de gallinas, posteriormente se vuelve a multiplicar el número actual de gallinas por la cantidad de huevos y se obtiene el número total de huevos para el segundo día. Cabe señalar que no se debe perder la cantidad de huevos calculados anteriormente.
Posteriormente se divide el número de gallinas entre dos, ya que el zorro se come la mitad de las gallinas. Y por último se calcula la cantidad de huevos obtenidos el tercer día para finalizar con la suma obtenida de los tres días.

