# Docencia con IAG
En esta sección encontrara material específico para el uso de la Inteligencia Artificial Generativa en actividades de Educación superior.


## 1. Consultar a la IAG como te puede ayudar
Como primera actividad se propone introducir el siguiente Prompt al modelo de lenguaje grande ChatGPT:

```
Mi nombre es [Nombre], soy Ingeniero/a [Profesión] con estudios en [Posgrados].
Soy docente de las [Asignaturas] en el programa de [Programa].
Que tareas puedes realizar para ayudarme en mi labor docente?
```

## 2. Generación de contenido de una asignatura
La IAGs  nos puede ayudar a construir el plan de contenidos para una asignatura. Ensaye con el siguiente Prompt para alguna de sus asignaturas:

```
Necesito diseñar los contenidos y evaluaciones de una asignatura universitaria.
La asignatura es [Nombre de la Asignatura], tiene una duración de [Numero Semanas]
semanas y el tema principal es [Tema Principal]. Quiero que incluyas los objetivos
del curso, la estructura semanal con los temas, contenidos y evaluaciones correspondientes,
además de los recursos y la evaluación final.
```

Ahora le puede indicar que faltó indicar los conocimientos previos o prerrequisitos que requiere la asignatura (esta información no la incluyó la IA porque no estaba en el contexto). 

## 3. Generación de tablas de saberes
En el formato de microcurriculo se debe diligenciar la tabla de saberes. Por medio de la IAG podemos generar un Prompt para saber como debemos consultarla con el fin crear una tabla de contenidos, así:

```
Actúa como un experto en diseño de Prompts. Necesito el diseño de un Prompt para
consultar la tabla de saberes de una asignatura universitaria. Me puedes indicar que
información necesitas y cuales son las variables, por ejemplo: Nombre de la asignatura,
contenidos, etc. La tabla de saberes se debe entregar en formato tabla.
```

La IAG te entregara el Prompt que puedes usar para generar la tabla de saberes, también puede que te muestre un ejemplo de aplicación. Ahora, rellena la información de la plantilla del Prompt generada a partir de los datos de una asignatura que estés dictando.

## 4. Generación de resultados de aprendizaje
La idea es generar los resultados de aprendizaje sobre el mismo contexto donde se construyeron los contenidos y las tablas de saberes del curso. Un Prompt sencillo para generar los resultados de aprendizaje usando una IAG puede ser el siguiente:

```
Actúa como un experto en el diseño de resultados de aprendizaje de asignaturas universitarias.
La asignatura es [Nombre de la asignatura], el tema principal es [Tema Principal].
Quiero que incluyas los resultados de aprendizaje y la rubrica definida en una tabla.
La rubrica debe estar definida sobre las siguientes categorías: Excelente (Nota 4.0-5.0),
Bueno (Nota 3.5-3.9), Aceptable (Nota 3.0-3.4) y Requiere mejoras (Nota<=2.9).
```

Para generar los resultados de aprendizaje sobre otra asignatura diferente, se debe incluir una oración donde se describan los contenidos y los objetivos de la asignatura. Ensayar generando los RA de otra asignatura para la cual la IAG no haya construido un contexto previo.

## 5. Generacion de lecciones de un tema y diapositiva
Podemos generar el contenido para una diapositiva y tambien el prompt para generar la imagen que acompañe la explicacion. 

```
Actua como un experto en diseño de presentaciones. Escribe que texto debe llevar la diapositiva de
[Tema de la diapositiva] juntos con el prompt que se necesita para generar la imagen explicativa de la diapositiva.
```
Tambien le podemos pedir a las IAG que nos generen todos los contenidos y todos los prompts de las imagenes para cada diapositiva, y que el resultado sea entregado en una tabla. Puedes intentar construir este prompt y probarlo en ChatGPT. 

En office 365 podemos hacer uso de extensiones con IAG las cuales pueden ayudar a construir una presentacion inicial para un tema de la asignatura

<img src="https://raw.githubusercontent.com/cgl-itm/HerramientasIA_Docentes/main/assets/Office365_PowerPoint.png" alt="drawing" style="width:400px;"/> <br>


## 6. Consulta información de un PDF
Aplicaciones como [ChatPDF](https://www.chatpdf.com/) permiten subir un archivo PDF y por medio de la IAG podemos realizar preguntas sobre el documento. Hoy en dia ChatGPT 4o y Claude 3.5 Sonnet permiten hacer algo similar.

## 7. Generación de aplicaciones
Un uso muy particular para Claude es la gneneracion de codigo en Python para hacer GUIs, o para generar codigo HTML, CSS y JS para paginas web. 

### Ejemplos en linea de generación de Apps
* [8 Apps con Claude 3.5 Sonnet](https://alejavirivera.com/8-apps-con-claude-3-5-sonnet/): Ejemplos de generacón de paginas web a partir de la IAG Claude 3.5 Sonnet (al parece el ejemplo del panel interactivo no funciona).

# Recursos en linea
* [ChatGPT - Teaching with AI](https://openai.com/index/teaching-with-ai/)
* [ClassPoint - 11 of the Best AI Tools for Teachers](https://www.youtube.com/watch?v=KG4_CYbVpTo)
* [Copilot Resources for Education](https://adoption.microsoft.com/es-es/copilot-resources-for-education/)
* [Ejemplo de Prompts para Docentes 2024](https://www.youtube.com/watch?v=Eu6D2TVRf98)

# Cursos en Linea
* [Google - AI for Educators](https://grow.google/ai-for-educators/)
* [Microsoft - Enhance teaching and learning with Microsoft Copilot](https://learn.microsoft.com/en-us/training/modules/enhance-teaching-learning-bing-chat/)
