<p align="center">
  <img src="https://seeklogo.com/images/U/universidad-peruana-de-ciencias-aplicadas-upc-logo-B98C3A365C-seeklogo.com.png" alt="Logo"  width="150" height="150">
</p>

Curso:
CC216 – Fundamentos de Data Science – CC52

Trabajo Final:
Tendencias de los videos de YouTube en México (MX)

Profesora:
Nérida Isabel Manrique Tunque


## Indice
1. [Objetivo del proyecto](#)
2. [Integrantes del grupo](#)
3. [Descripción del conjunto de datos](#)
4. [Conclusiones](#)

## Objetivo del proyecto
El proyecto tiene como objetivo principal analizar las tendencias de los videos de YouTube en México, con el fin de proporcionar información valiosa a una consultora internacional con sede en Lima y a su cliente, una destacada empresa de marketing digital. Se busca obtener respuestas a diversas preguntas específicas que son fundamentales para satisfacer las necesidades informativas del cliente en relación con el mercado mexicano. Este análisis profundo busca brindar un conocimiento integral de las tendencias en videos de YouTube, contribuyendo así a la toma de decisiones estratégicas de la consultora y su cliente en el ámbito de la mercadotecnia digital. Las respuestas a las siguientes preguntas son fundamentales para complementar el conocimiento que se pretende estimar.

**Por Categoría de Videos:**
* ¿Qué categorías de videos son las de mayor tendencia?
* ¿Cuáles son las categorías de videos más y menos apreciadas?
* ¿Qué categorías de videos tienen la mejor proporción de "Me gusta" / "No me gusta"?
* ¿Cuáles tienen la mejor proporción de "Vistas" / "Comentarios"?

**Por el Tiempo Transcurrido:**
* ¿Cómo ha evolucionado el volumen de videos en tendencia a lo largo del tiempo?

**Por Canales de YouTube:**
* ¿Qué canales de YouTube están en tendencia con mayor frecuencia y cuáles con menos frecuencia?

**Por la Geografía del País:**
* ¿En qué estados se presenta el mayor número de "Vistas", "Me gusta" y "No me gusta"?

**Adicionalmente:**
* ¿Es factible predecir el número de “Vistas” o “Me gusta” o “No me gusta? 
* ¿Los videos en tendencia son los que mayor cantidad de comentarios positivos reciben?

## Integrantes del grupo
**Alumnos:**
| **Apellidos y Nombres** | **Código** | 
| :-------- | :------- |
| Alvarez Orellana Iam Anthony Marcelo | u202118258 | 
| Angel Ruben Zuñiga Lovera | u202111299 |
| Angel Ruben Zuñiga Lovera | u20191B823 | 

## Descripción del conjunto de datos
**Tabla 2: Descripción de Variables del Conjunto de Datos “MXvideos_cc50_202101.csv"**
| Variable               | Descripción                                              |
|------------------------|----------------------------------------------------------|
| video_id               | Identificador único del video en YouTube                 |
| trending_date          | Fecha en la que el video estuvo en tendencia             |
| title                  | Título del video                                         |
| channel_title          | Nombre del canal que publicó el video                    |
| category_id            | Identificador de la categoría del video                  |
| publish_time           | Fecha y hora de publicación del video                    |
| tags                   | Etiquetas asociadas al video                             |
| views                  | Número de vistas del video                               |
| likes                  | Número de "Me gusta" del video                           |
| dislikes               | Número de "No me gusta" del video                        |
| comment_count          | Número de comentarios en el video                        |
| thumbnail_link         | Enlace a la miniatura del video                          |
| comments_disabled      | Indica si los comentarios están deshabilitados          |
| ratings_disabled       | Indica si las calificaciones están deshabilitadas         |
| video_error_or_removed  | Indica si hay un error o el video fue eliminado          |
| description            | Descripción del video                                    |
| state                  | Nombre del estado                                        |
| lat                    | Latitud geográfica de la ubicación del estado            |
| lon                    | Longitud geográfica de la ubicación del estado           |
| geometry               | Información de geometría                                 |

**Fuente: Elaboración propia**

## Conclusiones
En conclusión, el proyecto de Data Science para analizar las tendencias de videos en YouTube ha proporcionado valiosas respuestas gracias a la aplicación de técnicas especializadas de Análisis de Series Temporales, particularmente utilizando el modelo ARIMA. Sin embargo, es crucial destacar que en el proceso de obtener insights, la perseverancia es clave. La naturaleza iterativa del proyecto sugiere la importancia de revisar y reflexionar sobre las decisiones tomadas en cada etapa, especialmente considerando la metodología CRISP-DM. Si algún insight no es evidente de inmediato, la revisión cuidadosa de pasos anteriores puede revelar áreas de mejora en la salida del modelo, permitiendo ajustes significativos para una mejor comprensión de las tendencias de los videos en YouTube. La iteración y la reflexión continua son elementos esenciales para maximizar la eficacia y el valor del modelo creado en este proyecto.
