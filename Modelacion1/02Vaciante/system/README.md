Funciones implementadas en controlDict

fieldAverage1:

Para cada punto en el dominio se calcula el promedio de un campo respecto al tiempo transcurrido

fieldAverageCelda1, fieldAverageCelda2, fieldAverageCelda3:

Obtiene el promedio del campo del contaminante en 3 zonas para cada tiempo y guarda los resultados en
postProcessing/fieldAverageCelda1.dat, postProcessing/fieldAverageCelda2.dat y postProcessing/fieldAverageCelda3.dat

Para que openFoam reconozca estas 3 zonas antes de correr interMixingFoam se debe correr topoSet -dict system/topoSetDict
en la consola. Se pueden añadir o modificar las zonas en topoSetDict.

fieldAverageCelda1U, fieldAverageCelda2U, fieldAverageCelda3U:

Obtiene el promedio del campo de velocidades en 3 zonas para cada tiempo y guarda los resultados en
postProcessing/fieldAverageCelda1U.dat, postProcessing/fieldAverageCelda2U.dat y postProcessing/fieldAverageCelda3U.dat

Para que openFoam reconozca estas 3 zonas antes de correr interMixingFoam se debe correr topoSet -dict system/topoSetDict
en la consola. Se pueden añadir o modificar las zonas en topoSetDict.

fieldMinMax1:

Guarda los valores mínimos y máximos del campo de contaminante y donde se dan por cada iteración en
postProcessing/fieldMinMax1.dat

test_fun:

Es una función de tipo coded que no tiene una función muy específica en este momento.