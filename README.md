# Procesamiento de señales de ADV
> Hergenreder, L. e Irigoyen, M. (2019). Generación de una herramienta de procesamiento de registros de ADV en lenguaje Python. _Informe LHA-378-2019_ Laboratorio de Hidráulica, Instituto Nacional del Agua, Argentina.

> Ejecutar la herramienta: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lhergenreder/ADV/master)

El presente es un código interactivo que permite realizar una serie de procesamientos básicos en registros de velocidad obtenidos por velocimetría acústica-Doppler. El programa permite:
1. Identificar y reemplazar valores anómalos (spikes) empleando el critero _Phase Space Threshold_ (Goring y Nikora, 2002).
1. Evaluar la calidad del registro a través de los siguientes indicadores:
   1. Señal ruido (SNR)
   1. Correlación
   1. Cantidad de valores anómalos (spikes)
1. Extraer del ruido Doppler a través del _Análisis espectral_ (Voulgaris y Trowbridge, 1998).
1. Determinar los siguientes parámetros:
   1. Velocidades medias
   1. Varianzas
   1. Energía cinética turbulenta
   1. Intensidad de la turbulencia
1. Determinar el tiempo óptimo de medición empleando la metodología _Moving block bootstrap_ (García et al., 2006)

Los siguientes equipos son admitidos al momento:
1. Sontek MicroADV de 16 MHz
1. Nortek Vectrino II

## Cómo utilizar la herramienta
El programa fue desarrollado en la plataforma [Jupyter Notebook](https://jupyter.org/), en lenguaje Python 3.0. El mismo puede ejecutarse a través de [mybinder](https://mybinder.org/), clickeando en el bóton [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lhergenreder/ADV/master).

## Renuncia de responsabilidad
_(en desarrollo)_
