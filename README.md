#c16-98-m-data-bi

## Integrantes:
#### Franco Asplanatti, Paola Garrone

## Análisis exploratorio sobre los casos notificados de VIH en Argentina
#### Cliente: 
**<p>Organismo de salud público o privado asociado a la prevención, tratamiento del virus y a la enfermedad adquirida.</p>**

#### Objetivo: 
**<p>El objetido se centra en el desarrollo de campañas  de prevención de la enfermedad dirigidas a grupos específicos en función del comportamiento de contagios, y de esta forma, disminuir el avance de la enfermedad y las muertes precoses. </p>**

#### Desarrollo: 
**1. Extracción, transformación y carga (ETL):**
A partir de la página de INDEC se obtuvieron diversos datasets con datos provenientes del Ministerio de Salud de la Nación, correspondiente a periodos entre 2010 y 2022.  Asimismo, a través de la pagina de Kaggle, se obtuvieron datos a nivel mundial.

**2. Análisis de datos:**
Luego realizamos un breve proceso de transformación, ya que los datos de fuente estaban relativamente limpios.  En una primera etapa se realizó el análisis a través herramientas de Python y luego se conectaron con la plataforma Looker Data Studio para su análisis y armado de un dashboard interactivo con controles de filtrado para facilitar su consulta por las areas de Comunicaciones y Programas de Prevención.

**3. Datasets:**
Se compartieron en una carpeta de google drive:  <br>

**[Datasets Argentina](https://drive.google.com/drive/folders/16p59UyppGT7Etl6hBHmkbCQyykpKoUrT?usp=drive_linkhttp:// "Datasets Argentina")**<br>

**[Datasets Mundo](https://drive.google.com/drive/folders/1bm7fR9UFq6fjf0pjcjvxrIxXaBvhvhj8?usp=drive_link "Datasets Mundo")**

**4. Informe final realizado en Looker Data Studio:**
[https://lookerstudio.google.com/s/vajpMybvfQk](https://lookerstudio.google.com/s/vajpMybvfQk)

**5. Hallazgos:**
Realizando un análisis general mundial, podemos observar una diferencia ampliamente significativa en el número de muertes asociadas con el VIH en África frente al de otras regiones.
Debemos tener en cuenta que muchas de las defunciones podrían no estar contadas debido a un deficiente sistema de salud o por no haber detectado la enfermedad adecuadamente. Además, se encontraron muchos países sin datos oficiales publicados.
En el caso particular de latinoamérica, se puede observar que Brasil lidera la región, mientras que Argentina, se encuentra décimo entre los países más afectados por defunciones causadas por SIDA en América, cuya tasa es diez veces menor que la de Brasil.
En particular, Argentina, con un patrón de transmisión ligado durante años a las personas usuarias de drogas por vía parenteral o a las relaciones sexuales de hombres homosexuales,  estos datos nos permiten observar cambios fundamentales en los últimos años. Por lo cual, es necesario rearmar los criterios de comunicación en prevención de esta enfermedad. 
Con una tasa de casi el 69%, los hombres son el grupo sobre el que se reforzarán las acciones de prevención haciendo hincapié en pautas de practicas sexuales seguras y métodos de profilaxis farmacológica. 
Es alarmante observar que más de la mitad de los casos que han sido notificados en este periodo corresponden a contagios transmitidos por relaciones sexuales con hombres. Incluso supera el doble de el siguiente caso más frecuente, las relaciones sexuales con mujeres. Por lo tanto, es más que evidente que el foco de contagio principal se debe a relaciones sexuales en general. 
En el período estudiado se observa un descenso sostenido, con un mínimo pronunciado en el año 2020, coincidiendo con el inicio del aislamiento por la pandemia de COVID-19. 
Sería interesante contar con datos adicionales para discernir si se debe a una disminución de casos reales, o fue producto de casos no identificados por la restricción de acceso al sistema de salud. 
A partir de estos datos, en cuanto a su distribución a nivel país, Buenos Aires, incluida la Capital Federa, Córdoba, Santa Fé, Salta y Mendoza, son las provincias con mayor cantidad de notificaciones de casos y donde se deberían reforzar las acciones de prevención.

### Problemas hallados durante el estudio y abordaje de soluciones:
##### Acceso a datos públicos
Trabajar en la mejora y  disponibilidad de datos abiertos de origen cierto garantiza un acceso equitativo a la información sobre infecciones por VIH, lo que es fundamental para todos los actores involucrados en la prevención y tratamiento.

##### Fuentes de Datos Inconsistentes
Identificar las posibles fuentes de inconsistencia en los datos es esencial para garantizar la precisión y fiabilidad de la información, fundamentalmente para trabajar en modelos predictivos para planificar las políticas sanitarias futuras.

##### Impacto en las Decisiones
Las incongruencias en los datos pueden llevar a decisiones erróneas o ineficientes en las estrategias de prevención y tratamiento del VIH, subrayando la importancia de abordar este problema.

### Conclusiones
- En base a los resultados obtenidos, si bien los índices de enfermedad presentan un descenso sostenido, se evidencia un grupo de pacientes con alto grado de exposición, por lo que se recomienda focalizar las acciones de prevención en el grupo de varones cis y mujeres trans, entre 25 y 35 años, para mejorar las tasas de buena salud.

- Se busca especialmente abordar la reticencia de los varones homosexuales y los varones que mantienen relaciones sexuales con 
- varones a acceder a la asistencia sanitaria debido al temor o estigmas culturales asociados. Combatir estas barreras es crucial para mejorar la prevención y el tratamiento del VIH como de otras enfermedades.

- Con un patrón de transmisión ligado durante años a las personas usuarias de drogas por vía parenteral o a las relaciones sexuales de hombres homosexuales, estos datos nos permiten observar cambios fundamentales en los últimos años. Por lo cual es necesario rearmar los criterios de comunicación y prevención de esta enfermedad.

- Es necesario priorizar políticas de prevención que aborden las barreras socio-culturales y promuevan un acceso equitativo a los métodos de profilaxis previa y posterior a la exposición.

- En última instancia, se debería segmentar la comunicación tanto por género como por grupo etario, generando materiales en lenguajes y contextos para cada segmento y población de riesgo más frecuente.



