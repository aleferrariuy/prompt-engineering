We often read that one structure or another must be used when writing a prompt.

GPTs basically process: natural language and structured language (Markdown, XML, JSON).

The same language should not always be used when addressing the AI ​​agent via a prompt.

Which one to use will depend on the use case:

| Format      | Recommended Use                       |
| ----------- | ------------------------------------- |
| Plain Text  | Casual Conversation, Quick Questions  |
| Markdown    | Organized Presentations               |
| JSON        | Programmatic Processing, APIs         |
| XML         | Integration with Structured Systems   |

## Plain Text format (natural language)

#### Ideal for:
- Common questions or natural dialogue
- Requesting explanations, examples, ideas, or essays

## Markdown format

#### Ideal for:

- Organizing complex requests
- Requesting lists, tables, sections, or specific output formats
- Step-by-step instructions or code blocks

~~~
**Rol:** Eres un asistente experto en [dominio].

**Contexto:**  
- [Punto clave 1]  
- [Punto clave 2]  

**Tarea:**  
- [Verbo + acción principal]  
- Enfócate en [detalle específico].

**Restricciones:**  
- Longitud: máximo [X palabras/párrafos]  
- Tono: [formal/coloquial/técnico…]  
- Formato: [lista, tabla, JSON…]  
- Evitar: [puntos prohibidos]

**Formato de salida:**  
1. [Encabezado o sección 1]  
2. [Encabezado o sección 2]  
3. Conclusión breve.

**Ejemplo:**  
- **Entrada:** “[Texto de muestra]”  
- **Salida esperada:** “[Resultado de muestra]”
~~~

For everyday use cases for an average person, outside of a demanding context, natural language options for simple queries, and Markdown if a query needs to be made more complex, are more than sufficient.

When the volume or complexity of data increases, when the required level of analysis is greater, when automation or linking to external agents or applications is included, then it is an opportune time to use XML (using tags) or JSON (not using tags) to provide order and portability to the information.

## XML format
~~~
<prompt>
  <rol>
  </rol>
  <contexto>
    <ítem1>...</ítem1>
    <ítem2>...</ítem2>
  </contexto>
  <tarea>
    <ítem1>...</ítem1>
    <ítem2>...</ítem2>
  </tarea>
  <restricciones>
    <ítem1>...</ítem1>
    <ítem2>...</ítem2>
  </restricciones>
  <formato de salida>
    <ítem1>...</ítem1>
    <ítem2>...</ítem2>
  </formato de salida>
  <ejemplo>
  </ejemplo>
</prompt>
~~~

## JSON format
~~~
{
  rol:
  contexto: ["...","..."],
  tarea: [
    "...",
    "..."
  ],
  restricciones: [
    "...",
    "..."
  ],
  formato de salida: [
    "...",
    "..."
  ],
  ejemplo: ["..."],
}
~~~
