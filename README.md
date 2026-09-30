# Qwen Studio · Un solo Play

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xordanblu/qwen-studio-colab/blob/main/Qwen-Studio.ipynb)

Una app para crear y editar imágenes con **Qwen-Image-2.1 original**, dentro de tu propio Google Colab.

1. Abre **[Qwen Studio en Colab](https://colab.research.google.com/github/xordanblu/qwen-studio-colab/blob/main/Qwen-Studio.ipynb)** con tu cuenta de Google.
2. Pulsa **▶️ Abrir Qwen Studio** y acepta la ejecución del notebook si Colab lo solicita.
3. Espera la instalación, descarga y carga del modelo. La app aparece en la salida del notebook, lista para escribir tu prompt, elegir calidad y generar.

**Selecciona GPU T4, L4 o A100 en Colab.** El notebook propone **T4 con RAM estándar** y adapta la carga a la memoria disponible. Necesita al menos 14 GiB de VRAM, 10 GiB de RAM del sistema y 55 GiB libres para la instalación inicial. La asignación de GPU depende de tu cuenta y de la disponibilidad de Google. La primera preparación descarga aproximadamente 33 GB. No necesitas instalar nada en tu computadora.

Usa los pesos oficiales completos, **sin cuantización de 4 u 8 bits**. En T4 calcula en FP16 y lee capas desde el disco; con BF16 nativo mantiene BF16. Una T4 tarda más que una A100. La disponibilidad de una sesión gratuita o de unidades de cómputo corresponde a tu cuenta de Colab.

La ejecución usa tu propio entorno y tus recursos de Colab. Este repositorio distribuye el programa; no conecta con un entorno de otra persona. Si quieres conservar una copia editable, utiliza **Archivo → Guardar una copia en Drive**.

Incluye creación, edición con referencias, calidad rápida/alta/máxima, siete formatos, 1K/2K, PNG transparente, semillas, ajustes avanzados, progreso, cancelación, historial y descarga de PNG, recetas JSON y galería ZIP. El prompt empieza vacío, sin ejemplos precargados.

Al terminar, descarga tus resultados y elige **Entorno de ejecución → Desconectarse y eliminar entorno de ejecución** para liberar la GPU. Los archivos del entorno son temporales.

El notebook contiene el motor, la interfaz y el instalador completos. Fija las versiones de las dependencias y del modelo; no necesita claves de servicios de generación ni repositorios privados. El modelo se descarga desde los [pesos oficiales de Qwen](https://huggingface.co/Qwen/Qwen-Image-2.1).
