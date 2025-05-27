## Plain Text format


## Markdown format
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
