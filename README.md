# Descripción

El archivo `clean_data.py` implementa el algoritmo 'fingerprint' para collisión
de textos, el cual es utilizado para unificar cadenas de texto que representan
la misma entidad.

Complete el código siguiendo las instrucciones que aparecen en `clean_data.py`.

Referencia:
https://openrefine.org/docs/technical-reference/clustering-in-depth

# Configuración en MacOS y Linux

## Instalación del ambiante de desarrollo

Ejecute los siguientes comandos en el terminal:

```bash
python3 -m venv .venv
source .venv/bin/activate
source setup.sh
```

## Calificación del laboratorio

Ejecute los siguientes comandos en el terminal:

```bash
./tests/run.sh
```

# Configuración en Windows

## Instalación del ambiante de desarrollo

Ejecute los siguientes comandos en el terminal:

```bash
python3 -m venv .venv
.venv\Scripts\activate
setup
```

## Calificación del laboratorio

Ejecute los siguientes comandos en el terminal:

```bash
tests\run
```