# 📝 Plantilla de Entrega: El Pensadero (Frontend)

Responde a las siguientes preguntas como parte de tu evaluación final. Guarda una copia de este archivo con tu nombre (ej: `JUAN_PEREZ.md`) dentro de `magos_graduados/`.

1.  **¿Usaste Inteligencia Artificial para resolver los retos (del 1 al 6)?**
    *Respuesta:* Si la utilice para los retos del 1 al 6

2.  **¿Para qué específicamente te fue útil la IA? (Ej. para entender los Observables, para explicar errores de TypeScript, para que hiciera el código desde cero)**
    *Respuesta:* Principalmente me fue util para entender muchos errores puesto que aunque los podia ver y saber en que linea eran y el autocorrector me inidcaba una sugerencia luego yo mandaba mi duda a la ia de claude porque cree una skill para consultar y que me explique ese tipo de cosas mediante la cual le pedia una explciacion del error y la logica detras de la misma como las consultas que se mandan al backend asegurandome que si resolvia los retos o tenia problemas en el camnio supiera el porque de los mismos

3.  **¿Qué fue lo que más se te dificultó al conectar Angular con la API de Spring Boot?**
    *Respuesta:* Lo que mas me costo al inicio fue enviar el parametro de un tipo a la consulta pero cuando lo intente me marcaba un error de ts2390 ahi utilice si fui directamente a goggle para saber de que trataba y vi que solo me faltaba importar los HttpParams porque antes pense que no habia que tocar nada pero luego vi que solo era agregar eso

    
4.  **Explica con tus palabras la diferencia entre un componente y un servicio en Angular.**
    *Respuesta:* Un componente sirve como una interfaz visual mediante la cual el usuario puede ver y trabajar en la misma por el ejemplo el hechizobuscador ya que muestra la tabla de hechizos y guarda los que se generan, en cambio un servicio no tiene una interfaz grafica solo pura logica que se puede reutilizar como habalr con el backend como hechizoapiservice hace las peticiones a api/hechizos.
    el componente pide los datos al servicio con inject y el servicio los trae del backend

    

5.  **¿Por qué validamos en el formulario si el backend ya valida en el Manager?**
    *Respuesta:* lo validamos porque el formulario envia una respuesta para el usuario para que si tengan una respuesta como por ejemplo pedir el nombre pero el backend no puede confiar en eso porque alguien puede enviar la peticion sin pasar por el formulario por eso el manager valida otra vez se ve con la magia oscura pues el formulario la deja pero el manager la rechaza con un 400 y diciendo magia prohibida en el colegio
   
