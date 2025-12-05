# Generación de Texturas de Minecraft con Modelos Generativos (CVAE, CGAN, DDPM)

Este repositorio contiene el código, modelos y experimentos empleados para el estudio de técnicas de generación de imágenes aplicadas a texturas de objetos de Minecraft, concretamente utilizando el pack **Faithful 32x32**, versión **1.21.1**.

El objetivo es comparar distintos enfoques generativos (CVAE, CGAN y DDPM) para evaluar su rendimiento en entornos con datos limitados y resolución reducida.

---

##  Descarga y preparación de datos

Los datos utilizados en este estudio pertenecen al proyecto **Faithful**, disponibles públicamente en:

**https://faithfulpack.net/downloads**

Para reproducir los experimentos:

1. Descargar la versión:
   - **Faithful 32x32**
   - **Minecraft 1.21.1**

2. Dentro del archivo `.zip`, navegar hasta: `/assets/minecraft/textures/`

3. Copiar la carpeta `item` de esa carpeta en: `datos/`

El proyecto asume esta ruta para cargar automáticamente todas las texturas.


---
##  Nota sobre el cuaderno LoRA / Stable Diffusion

Durante el desarrollo del proyecto se intentó ejecutar un cuaderno experimental para entrenar LoRA sobre Stable Diffusion en la plataforma **Kaggle**.  
Sin embargo, el proceso fue interrumpido y la cuenta fue suspendida debido a los sistemas automáticos de detección de contenido sensible.

Por este motivo he decidido no incluir dicho cuaderno en este repositorio, y para evitar posibles sanciones o restricciones de cuenta de usuarios.


---

## Uso adecuado del pack Faithful

Este proyecto utiliza texturas del pack Faithful exclusivamente con fines académicos y no comerciales. Este repositorio no distribuye ningún archivo del pack Faithful. Los usuarios deben descargar los recursos directamente desde su web oficial: https://faithfulpack.net/

Las texturas generadas como resultado de los modelos entrenados pueden considerarse obras derivadas, de modo que su uso también queda sujeto a la licencia Faithful incluida en la carpeta `extras/`.

---

## Licencia del repositorio

El código fuente de este repositorio está disponible bajo una licencia de uso académico y no comercial (MIT License).




