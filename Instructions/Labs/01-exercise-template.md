---
lab:
  title: Título del ejercicio
  module: Learn module title
---
<!--
Edit the metadata above to manage the list of exercises in the home page of the GitHub site that gets generated.
You can delete the module and edit index.md in the root of the repo to customize the display so that only the exercises are listed
To enable GitHub page publishing, edit the Page settings for the repo and publish from the main branch
-->

# Título del ejercicio <!-- match title in metadata above (and Learn Exercise unit and ILT slide)-->

En este ejercicio: <!-- provide a description of what they'll do and why it;s important -->

Este ejercicio debería tardar aproximadamente **XX** minutos en completarse. <!-- update with estimated duration -->

## Antes de comenzar

<!--
Add steps to get the learner to the starting point" for the exercise.
This might be cloning the repo and running a script or performing some manual steps.
Only include this section if its necessary to do some pre-exercise setup AND the same setup steps are required for self-paced (on Learn) and managed (in hosted ILT lab profiles) scenarios. Otherwise delete this section.
If self-paced /ILT-specific setup steps are required, include them in the Learn "Exercise" unit from where they open this exercise and in the Skillable lab profile instructions before this markdown file is imported.
 -->

Antes de poder iniciar este ejercicio, deberás...

1. Paso 1
1. Paso 2
1. etc.

## Tarea <!-- Change to an appropriate task title with an imperative verb phrase (e.g. "Do something") -->

Primero, necesitas...

1. Paso 1
1. Este paso incluye un ejemplo de `inline code formatting`, que se usa cuando el alumno necesita escribir algo (cualquier cosa, no solo código) porque crea un vínculo [T] en el entorno hospedado Skillable.
1. Si necesitas que el alumno abra un sitio web, incluye un vínculo (para que pueda abrirlo haciendo clic en la página HTML de GitHub) Y la dirección URL con formato de código (para que pueda escribirla en un explorador de VM hospedado). Por ejemplo, "Abre el sitio web de [Bing](https://www.bing.com) en `https://www.bing.com`".
1. Si necesitas que el alumno descargue un archivo (o varios archivos en formato ZIP), almacena el archivo en la carpeta Allfiles de este repo y usa la dirección URL **sin procesar**, de la siguiente manera: "Descarga [nombre de archivo](https://raw.githubusercontent.com/MicrosoftLearning/INF99X-SampleCourse/master/Allfiles/Labs/01/Starter/azuredeploy.json) desde `https://raw.githubusercontent.com/MicrosoftLearning/INF99X-SampleCourse/master/Allfiles/Labs/01/Starter/azuredeploy.json`.
1. Como alternativa, para una audiencia de desarrolladores, puedes hacer que clonen este repo si parece más adecuado.
1. Si necesitas incluir un bloque de código de varias líneas, aplica sangría para que coincida con la sangría de lista con viñetas:

    ```python
    # This is an example of an
    # indented code block.
    ```

1. Si necesitas incluir una captura de pantalla, cambia su tamaño a un tamaño adecuado (de modo que cualquier texto con formato "normal" en una captura de pantalla parcial es aproximadamente del mismo tamaño que este texto; por lo general, intenta realizar capturas de pantalla de las ventanas de aplicación completa 800x600px (aprox)). Almacena las imágenes en una subcarpeta **Media** y usa Markdown para agregarlas a la página (recuerda que los nombres de archivo y carpeta distinguen mayúsculas de minúsculas). Si la imagen está en una lista, aplica sangría de la siguiente manera:

    ![Una captura de pantalla de una aplicación.](./Media/edge-copilot.png) 

1. Si necesitas explicar por qué algo se hace como se hace, o proporcionar contexto adicional o vínculos a información, usa una nota como esta:

    > **Nota**: esta es una nota.

1. Sé flexible al proporcionar instrucciones que pueden variar entre entornos de laboratorio autodirigido y hospedado. Por ejemplo:
    - "Inicia sesión con tus credenciales de Azure" (suponiendo que haya instrucciones específicas de Learn para usar una suscripción personal o crear una prueba en la página del ejercicio de Learn e instrucciones específicas de ILT para usar credenciales de cloudslice proporcionadas en el perfil de laboratorio de Skillable)
    - "Selecciona un grupo de recursos existente o cree uno nuevo" (suponiendo que se use cloudslice de Skillable CS-R, has incluido una nota en el perfil de laboratorio que indica al alumno qué grupo de recursos debe usar).
    <!-- The key point is that this markdown file should be environment-agnostic - you need to provide explicit details of things that can vary OUTSIDE of this file (in the Learn exercise page or the Skillable lab profile instructions) -->
1. etc.

## Tarea siguiente

Ahora vamos, ...

1. Paso 1
1. Paso 2
1. etc.

## Tarea con subtareas

A veces, es posible que quieras dividir una tarea en fragmentos más pequeños.

### Subtarea 1

1. Paso 1
1. Paso 2
1. Etc.

### Subtarea 2

1. Paso 1
1. Paso 2
1. etc.

## Limpiar

<!-- Good practice - especially as self-paced learners will be using their own subscriptions -->
<!-- Delete this section if it is not needed -->

Ahora que has terminado el ejercicio, debes eliminar los recursos en la nube que has creado para evitar el uso innecesario de recursos.

1. Paso 1
2. Etc.
