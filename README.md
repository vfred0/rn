# UBA - Maestria en Explotación de Datos y Descubrimiento de Conocimiento - Redes Neuronales

Material de la materia redes neuronales.

### Requsitos

* [git](https://git-scm.com/downloads)
* [anaconda](https://www.anaconda.com/products/individual) / [minconda](https://docs.conda.io/en/latest/miniconda.html)


### Instalar entorno y correr jupyter lab

[Ejemplo de setup de proyecto en windows](https://www.youtube.com/watch?v=O8YXuHNdIIk)

Para correr las practias es necesario configurar un entorno de conda con las librerias necesarias.

**Paso 1**: Descargar el repositorio.

```bash
$ git clone https://github.com/adrianmarino/rn.git
$ cd rn
```

**Paso 2**: Crear environment de dependencias para el proyecto (Parado en el directorio del proyecto).

```bash
$ conda env create -f environment.yml
```

Para los que usen mamba:

```bash
$ mamba env create -f environment.yml
```

**Paso 3**: Activamos el entorno.

```bash
$ conda activate rn
```

**Paso 4**: Sobre el directorio del proyecto levantamos jupyter.

```bash
$ jupyter notebook
Or copy and paste this URL:
    http://localhost:8888/?token=...
```

**Paso 5**: Ir a http://localhost:8888.... como se indica en la consola.

