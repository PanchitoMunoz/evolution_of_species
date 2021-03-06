[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12eInXV0C5Cep8h0PWgh2WxzGKr96NYfa?usp=sharing)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-no-red.svg)](https://bitbucket.org/lbesson/ansi-colors)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/PanchitoMunoz/evolution_of_species/blob/master/LICENSE.md)

# evolution_of_species

Proyecto orientado a resolver las Ecuaciones de Perthame que se encuentran en el paper [Evolution of species trait through resource competition](https://link.springer.com/article/10.1007/s00285-011-0447-z). Para más información puede revisar [la Wiki del proyecto](https://github.com/PanchitoMunoz/evolution_of_species/wiki). Aquí se puede observar un [notebook de ejemplo en google colab](https://colab.research.google.com/drive/12eInXV0C5Cep8h0PWgh2WxzGKr96NYfa?usp=sharing).

# Visualizaciones

A continuación se podrán observar algunas visualizaciones del proyecto

#### Divergencia evolutiva
![Divergencia evolutiva](https://github.com/PanchitoMunoz/evolution_of_species/blob/master/gifs/div_evol.gif)

#### Condición de supervivencia
![Condición de supervivencia](https://github.com/PanchitoMunoz/evolution_of_species/blob/master/gifs/supervivencia.gif)

#### Condición de Extinción
![Condición de Extinción](https://github.com/PanchitoMunoz/evolution_of_species/blob/master/gifs/extincion.gif)

# Instalación

## Usando entorno virtual
Es recomendable (y buena práctica) utilizar entornos virtuales para la instalación de la librería (por posibles incompatibilidades de requerimientos). Las siguientes instrucciones crean e instalan la librería en el entorno virtual `my_env`:

### Windows
```
py -m pip install --upgrade pip
py -m pip install --user virtualenv
py -m venv my_env
.\my_env\Scripts\activate
pip install git+https://github.com/PanchitoMunoz/evolution_of_species.git#egg=perthame_pde
```
### Unix/macOS
```
python3 -m pip install --upgrade pip
python3 -m pip install --user virtualenv
python3 -m venv my_env
source my_env/bin/activate
python3 -m pip install git+https://github.com/PanchitoMunoz/evolution_of_species.git#egg=perthame_pde
```

## PIP
Si usas `pip` el paquete se puede instalar con:
```
pip install git+https://github.com/PanchitoMunoz/evolution_of_species.git#egg=perthame_pde
```
Observar que esta acción hará que la librería se pueda ocupar de forma global.

# TODO

* [X] Agregar documentación de cómo instalar el programa
* [X] Agregar GIF de los resultados
* [ ] Escribir una wiki con los modelos descritos

