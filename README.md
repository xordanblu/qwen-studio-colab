# Qwen Studio · Un solo Play

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xordanblu/qwen-studio-colab/blob/main/Qwen-Studio.ipynb)

Una app para crear y editar imágenes con **Qwen-Image-2.1 original**, dentro de tu propio Google Colab.

1. Abre **[Qwen Studio en Colab](https://colab.research.google.com/github/xordanblu/qwen-studio-colab/blob/main/Qwen-Studio.ipynb)** con tu cuenta de Google.
2. Pulsa **▶️ Abrir Qwen Studio** y acepta la ejecución del notebook si Colab lo solicita.
3. Espera la instalación, descarga y carga del modelo. La app aparece en la salida del notebook, lista para escribir tu prompt, elegir calidad y generar.

**Necesitas acceso a A100 + Alta capacidad de RAM y unidades de cómputo en tu Colab.** El notebook incluye esa configuración; la asignación depende de tu cuenta y la disponibilidad de Google. La primera preparación descarga aproximadamente 33 GB. No necesitas instalar nada en tu computadora.

La ejecución usa tu propio entorno y tus recursos de Colab. Este repositorio distribuye el programa; no conecta con un entorno de otra persona. Si quieres conservar una copia editable, utiliza **Archivo → Guardar una copia en Drive**.

Incluye creación, edición con referencias, calidad rápida/alta/máxima, siete formatos, 1K/2K, PNG transparente, semillas, ajustes avanzados, progreso, cancelación, historial y descarga de PNG, recetas JSON y galería ZIP. El prompt empieza vacío, sin ejemplos precargados.

Al terminar, descarga tus resultados y elige **Entorno de ejecución → Desconectarse y eliminar entorno de ejecución** para liberar la GPU. Los archivos del entorno son temporales.

El notebook contiene el motor, la interfaz y el instalador completos. Fija las versiones de las dependencias y del modelo; no necesita claves de servicios de generación ni repositorios privados. El modelo se descarga desde los [pesos oficiales de Qwen](https://huggingface.co/Qwen/Qwen-Image-2.1).
