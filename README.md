# UBA - Maestria en Explotación de Datos y Descubrimiento de Conocimiento - Redes Neuronales

Material de la materia redes neuronales.

### Videos

[Videos de unidades y clases presenciales](https://www.youtube.com/playlist?list=PLcUKhWwmWVPHC6QzK5s9XPeG30BazvOW9)


### Instalar entorno y correr jupyter lab

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

**Paso 4**: Sobre el directorio del proyecto levantamos jupyter lab.

```bash
$ jupyter lab

Jupyter Notebook 6.1.4 is running at:
http://localhost:8888/?token=45efe99607fa6......
```

**Paso 5**: Ir a http://localhost:8888.... como se indica en la consola.

