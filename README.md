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

Este es el resultado del primer punto.

![Ejercicio 1_1](https://user-images.githubusercontent.com/54320247/64304165-c28f1100-cf50-11e9-95b5-1050643af6f9.jpg)

Y este el resultado del segundo punto.

![Ejercicio 1_2](https://user-images.githubusercontent.com/54320247/64304173-c4f16b00-cf50-11e9-9db4-fd49a737541c.jpg)

# 3_2_Ejercicio_2

Lea esta historia y calcule/imprima los valores necesarios:

– El lunes, el granjero Pedro recoge 100 huevos.

– El martes, recoge 121 huevos.

– El miércoles, recoge 117 huevos.

– ¿Cuál es el valor diario de huevos recogidos (dailyAverage )? 

– ¿Cuántos huevos cabría esperar como media en un mes de 30 días (monthlyAverage)?

– Si se obtienen unos beneficios de 0,18 dólares por huevo, ¿qué beneficio total obtendrá Pedro (monthlyProfit) para todos los huevos?

Se utiliza el programa -Chickens02-.
Para resolver el primer punto del problema, se debe obtener un media de los 3 días; esto es, la suma y posterior división entre los 3 días.
Con el dato obtenido se calcula la media de 30 días al multiplicarlo. Y con este último dato se obtienen las ganancias totales.

