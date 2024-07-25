<img src="https://raw.githubusercontent.com/cgl-itm/HerramientasIA_Docentes/main/assets/IA_generativa.jpg" alt="drawing" style="width:400px;"/> <br>

# HerramientasIA_Docentes

# IAs Generativas mas conocidas
Una comparativa de las IAs Generativas se puede encontrar en [artificialanalysis](https://artificialanalysis.ai/models/claude-35-sonnet).
* [OpenAI - ChatGPT](https://chatgpt.com/): La ultima version es ChatGPT 4o (ommni), consultar la [pagina oficial](https://openai.com/index/hello-gpt-4o/) del modelo. Tambien ejemplos de [vision](https://blog.roboflow.com/gpt-4o-vision-use-cases/) con ChatGPT 4o.
* [Google - Gemini](https://gemini.google.com/app): Un modelo muy avanzado cuyas caracteristicas estann descritas [aqui](https://blog.google/technology/ai/google-gemini-next-generation-model-february-2024/).
* [Antorpic - Claude](https://claude.ai/): El modelo Claude 3.5 Sonnet ha mostrado mejor desempeño que ChatGPT 4o en varias tareas. Una vista al modelo se encuentra en este [enlace](https://beginswithai.com/claude-3-5-sonnet/).
* [Meta - Llama](https://www.meta.ai/): La ultima version LLama 3.1 es el modelo mas grande hasta el momento y es completamente abierto. Para mas informacion consultar el [blog oficial](https://ai.meta.com/blog/meta-llama-3-1/).


# Prompt Engineering
Define la forma correcta de realizar consultas a las IA Generativas con el fin de obtener resultados de buena calidad. Se recomienda como primer documento de lectura la [Guia de OpenAI](https://platform.openai.com/docs/guides/prompt-engineering).

## Técnicas de Prompting
* Aportar contexto: El contexto es muy importante, ya que permite obtener respuestas más especificas. <br>

| Tipo de Prompt   | Ejemplo de Prompt                                                                                                                                           |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Zero Shot        | Describe las preferencias de vestimenta de una persona.                                                                                                     |
| One Shot         | Describe las preferencias de vestimenta de una persona que prefiere ropa casual. Aquí tienes un ejemplo: "Juan prefiere usar jeans y camisetas cómodas".   |
| Multiple Shot    | Describe las preferencias de vestimenta de una persona. Aquí tienes algunos ejemplos: "Juan prefiere usar jeans y camisetas cómodas. Ana prefiere vestidos elegantes y zapatos de tacón. Carlos prefiere ropa deportiva como sudaderas y pantalones de chándal."                                                 |

En el prompt "Zero Shot", simplemente se pide una descripción sin proporcionar ningún ejemplo previo. En el "One Shot", se da un ejemplo para guiar la respuesta. En el "Multiple Shot", se proporcionan varios ejemplos para ofrecer una guía más completa y específica.

* Establecer un rol: se le puede pedir a la IA que actúe con diferentes niveles de experiencia, desde basico hasta nivel experto en cualquier area. Probar el siguiente prompt con chatGPT:

````
Actúa como un experto en diseño de prompts para chatgpt. Me puedes dar un ejemplo de un prompt detallado donde el rol sea de un profesor de matemáticas, que tenga contexto, objetivo y formato de salida. 
````  

## Enlaces
* [Ejemplos de Prompts para ChatGPT](https://ua-data7.github.io/introllms/chatgpt_prompts/)
* [Xataka - 8 prompts para terminar tareas y ahorrar horas](https://www.xataka.com/robotica-e-ia/ocho-prompts-chatgpt-para-terminar-tareas-segundos-ahorrar-horas-trabajo)
* [TextCortex - Prompt Engineering guide](https://textcortex.com/es/post/prompt-engineering-guide)

# Text-to-Image
* [Midjourney](https://www.midjourney.com/home): La más conocida, requiere de Discord para hacer las consultas, y es de pago.
* [Leonard.ai](https://leonardo.ai/): Genera imagenes a partir de una palabras clave, posteriormente se genera magicamente un prompt detallado. [Guia de Prompts](https://leonadoai.com/ai-prompts/).
* [Ideogram](https://ideogram.ai/login): IA para generar imagenes, [Guia Inicial](https://docs.ideogram.ai/using-ideogram/getting-started/the-basics-step-by-step).
* [Designer](https://designer.microsoft.com/): Para usarlo de forma gratuita, abrir la pagina en un ventana incognita (con privacidad Ctrl+Mayus+N).

# Text-to-Video
* [OpenAI - Sora](https://soorai.com/)
* [Pika](https://pikartai.com/labs/)
* [Krea](https://www.krea.ai/home)
* [LumaLabs](https://lumalabs.ai/dream-machine): 30 videos gratis.
* [HeyGen](https://www.heygen.com/)
* [Synthesia](https://www.synthesia.io/)
* [Pictory](https://pictory.ai/)

# Text-to-WebPage
* [Durable](http://Durable.co)
* [WebSim](https://websim.ai/)


