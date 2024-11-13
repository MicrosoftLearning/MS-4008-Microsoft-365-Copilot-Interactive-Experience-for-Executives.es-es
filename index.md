---
title: Instrucciones hospedadas en línea
permalink: index.html
layout: home
---

# MS-4008: Experiencia interactiva de Microsoft 365 Copilot para ejecutivos 

## Directorio de contenido

Las demostraciones de este curso se basan en las demostraciones de la guía de demostración del kit [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

Es importante que te familiarices con las demostraciones antes de presentar este entrenamiento. Para varios laboratorios, usarás documentos de ejemplo y reuniones y correos electrónicos de Teams creados previamente.

- Descarga previamente todos los documentos de ejemplo [aquí](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/tree/master/ResourceFiles).
- Configura las reuniones de Teams y los hilos de correo siguiendo las instrucciones que se indican [aquí](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Familiarízate con la experiencia interactiva:
    - Opción 1: [aka.ms/CopilotEE](https://aka.ms/CopilotEE)
    - Opción 2: [aka.ms/TeamsEE](https://aka.ms/TeamsEE)

    > **NOTA:** si los particpantes no tienen una licencia de Microsoft 365 Copilot, pueden usar la versión comercial gratuita de la experiencia que se encuentra en [aka.ms/CopilotWebEE](https://aka.ms/CopilotWebEE).

## Descripción del curso

Descubre cómo Microsoft 365 Copilot eleva la productividad y la innovación en el área de trabajo. Esta experiencia, adaptada al líder empresarial moderno, proporciona información sobre la creación de indicaciones contextuales para Copilot e incluye ejercicios de casos de uso interesantes que muestran una integración perfecta en los flujos de trabajo diarios.

Los objetivos principales de esta entrega son:

- Presentar Microsoft 365 Copilot a los participantes para enseñarles a crear una solicitud eficaz
- Demostrar Microsoft 365 Copilot en aplicaciones de Office (hasta 3 demostraciones)
- Guiar a los participantes a través de una experiencia interactiva
- Invitar a los participantes a descargar y probar Microsoft Copilot for Mobile

## Tiempos del curso (estimación) 

| # | Tema                                 | Tiempo total      |
|---|---------------------------------------|-----------------|
| 1 | Introducción a Microsoft 365 Copilot | 10 minutos    |
| 2 | Guía del directivo para crear solicitudes eficaces | 30 minutos             |
| 3 | Experiencia interactiva con Microsoft 365 Copilot  | 20 minutos      |
|   |                                       | **Tiempo total 60 minutos** |


A continuación, se enumeran los hipervínculos a cada una de las demostraciones.

## Demostraciones

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demostración |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
