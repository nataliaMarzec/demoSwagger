¿Qué es OpenAPI?
La especificación OpenAPI (anteriormente especificación Swagger) es un formato de descripción API para las API REST. Un archivo OpenAPI le permite describir su API completa, que incluye:
    • Endpoints disponibles  ( /users) y operaciones en cada endpoint ( GET /users, POST /users)
    • Parámetros de operación Entrada y salida para cada operación.
    • Métodos de autenticación
    • Información de contacto, licencia, condiciones de uso y otra información.
Las especificaciones de API se pueden escribir en YAML o JSON. El formato es fácil de aprender y legible tanto para humanos como para máquinas. 
¿Qué es swagger?
Swagger es un conjunto de herramientas de código abierto creadas alrededor de la especificación OpenAPI que puede ayudarlo a diseñar, construir, documentar y consumir API REST. Las principales herramientas de Swagger incluyen:
    • Swagger Editor : editor basado en navegador donde puede escribir especificaciones OpenAPI.
    • Swagger UI : genera documentación interactiva de API que permite a sus usuarios probar las llamadas de API directamente en el navegador.
    • Swagger Codegen : genera stubs de servidor y bibliotecas de cliente a partir de una especificación OpenAPI.
Swagger puede usar con la mayoría de los lenguajes de programación: desde JavaScript a Haskell a C ++ a Python a Rust, la lista sigue y sigue. La cantidad de idiomas admitidos es realmente asombrosa.
¿Cómo podría usar Swagger?
Swagger se utiliza principalmente para documentar API. Existen varios enfoques y las dos formas más comunes son:
    • Enfoque de arriba hacia abajo (diseño-primera) : en este enfoque Swagger Editor se utiliza para crear Swagger definición y Swagger Codegen continuación, se utiliza para generar código para un cliente y un servidor. Básicamente, esto significa que Swagger se usará para diseñar la API antes de que se haya escrito ningún código.
    • Enfoque ascendente : en este enfoque, el usuario ya tiene una API RESTful existente y Swagger se usará solo para documentar la API existente.

