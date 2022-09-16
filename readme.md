# Prueba Bcas
Imaginemos que estamos desarrollando una red social de personas que adoran a los animales.
Esta red social tiene algunas peculiaridades:
- Cuando un usuario se da de alta, en el formulario de registro, introduce los
siguientes datos: username, email y password.
- Los usuarios se relacionan con otros por una relación de “amistad”, dando lugar al
listado de amigos.
- Los usuarios tienen un listado de mascotas

## Dado este ejemplo se pide realizar las siguientes tareas:
1. Diseñar y desarrollar una API rest que implemente el CRUD (operaciones Create,
Read, Update y Delete) para la entidad usuario (Los amigos y mascotas se pueden introducir directamente en la base de datos) y desplegarlo en [Railway](https://railway.app/dashboard)
2. En el READ de usuario deben venir, tanto las mascotas como los amigos de este usuario para poder pintarlo en el front
3. Crear un front con [Next](https://nextjs.org/) con el diseño de [Figma](https://www.figma.com/file/AJba5WKv7dV1EcXx6gxptR/Prueba-t%C3%A9cnica-Red-Social?node-id=0%3A1) para ver a los usuarios, sus amigos y sus mascotas. Desplegarlo en [Vercel](https://vercel.com/solutions/nextjs)


## Requisitos
- Uso de Node.js y framework Express.js
- Uso de base de datos postgres en [Railway](https://railway.app/dashboard)
- Uso de lenguaje SQL (no usar ORM)
- La programación asíncrona debe realizarse mediante promesas o async/await.
- Entrada y salida del API en formato JSON
- Documentación de la API
- Antes de cada petición se debe imprimir un log con alguna información sobre la
petición que se está realizando.
- Control de errores y excepciones.
- Buena organización y estilo de código intentando seguir un patrón de diseño en el
que la lógica y el modelo de datos sean independientes.
- Despliegue


## Observaciones
En caso de duda o falta de especificaciones, es tarea del desarrollador tomar las decisiones
pertinentes para la realización de la prueba. Estas decisiones deben ser justificadas en un
fichero incluido junto a la prueba, o bien comentadas claramente en el código.