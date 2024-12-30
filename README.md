Instructivo de instalación y uso de OpenFOAM 2406 Ubuntu.
1. Instalación de Ubuntu (en Windows)
Instalación de ubuntu: https://learn.microsoft.com/es-es/windows/wsl/install
2. Instalación de OpenFOAM
Instalación de openfoam:
https://develop.openfoam.com/Development/openfoam/-
/wikis/precompiled/debian
1. Primero ir a la carpeta home de Linux y crear carpeta vacía llamada
openfoam
2. Dentro de la carpeta openfoam colocar el archivo de la simulación
(ejemplo 01llenante)
3. En la terminal entrar a la carpeta openfoam/01llenante (con el
comando cd)
4. Escribir openfoam
5. Escribir comando
Comando ls para verificar las carpetas creadas. (muestra el listado de archivos
en la carpeta)
3. Correr una simulación
a. En la terminal entrar a la carpeta openfoam/01llenante (con el
comando cd)
b. Escribir openfoam en la terminal
c. Escribir comandos en la terminal (a veces puede ser necesario escribir
openfoam comando)
i. ideasUnvToFoam mesh.unv
ii. checkMesh
iii. setFields
iv. decomposePar
v. topoSet
vi. interMixingFoam
vii. reconstructPar
4. Uso de script para visualizar parámetros (Python)
a. Instalar en su computador las librerías matplotlib (su documentación se
puede encontrar en https://matplotlib.org/) y numpy (su documentación
se puede encontrar en https://numpy.org/).
b. Los pasos de instalación son los siguientes:
a. Para instalarlo debe entrar a su cmd
b. Escribir el comando pip install numpy
c. Escribir el comando pip install matplotlib
(En caso de cualquier fallo en la instalación revisar la versión del pip o la forma
que se usa en su sistema operativo)
c. Abrir el archivo .ipynb (se puede realizar en vocalizadores de código
como vscode). Una forma de visualizar los archivos jupyter notebooks es:
a. Instalar jupyter notebooks en la cmd con el comando pip install
notebook
b. Luego usar el comando python –m jupyter O python –m
notebook para buscar el archivo .ipynb y vizualizarlo.
d. Importante: el archivo .ipynb debe estar situado en la carpeta de la
modelación, es decir en:
5. Uso de GitHub
a. Para poder acceder a los archivos de código de nuestra solución se debe
ingresar al siguiente link:
https://github.com/DonMarto/IMT2116_HOLON
b. Luego dirigirse al botón Code de esa misma pagina
c. Hacer click en el botón Code y presionar Download ZIP
d. Descomprimir carpeta ZIP, ubicándola dentro de la carpeta openfoam
previamente creada (ubuntu)
