# Prueba Bcas
Imaginemos que estamos desarrollando una red social de personas que adoran a los animales.
Esta red social tiene algunas peculiaridades:
- Los usuarios deben tener nombre, descripción y foto de perfil [Generador](https://xsgames.co/randomusers/).
- Los usuarios se relacionan con otros por una relación de “amistad”, dando lugar al
listado de amigos.
- Los usuarios tienen un listado de mascotas.
- Los usuario escriben posts sobre sus mascotas en una aplicación externa. Esta aplicación nos proporciona una [API](https://jsonplaceholder.typicode.com/) para poder obtener los posts de los usuarios y mostrarlos.

## Requisitos
1. Diseñar y desarrollar una API en [Nest](https://docs.nestjs.com/) con base de datos Postgres en [Railway](https://railway.app/dashboard) que implemente el CRUD (operaciones Create,
Read, Update y Delete) para la entidad usuario (Los amigos y mascotas se pueden introducir directamente en la base de datos).
2. En el READ de usuario deben venir, tanto las mascotas como los amigos de este usuario para poder pintarlo en el front.
2. Crear un endpoint en nuestra API que nos traiga los posts del usuario seleccionado (por id) de la [API](https://jsonplaceholder.typicode.com/) externa para poder pintarlos en el front.
3. Crear un front con [Next](https://nextjs.org/) con el diseño de [Figma](https://www.figma.com/file/AJba5WKv7dV1EcXx6gxptR/Prueba-t%C3%A9cnica-Red-Social?node-id=0%3A1) para ver a los usuarios, sus amigos, sus posts y sus mascotas.
4. El listado de usuarios (página principal) debe cumplir los siguientes requisitos:
   -  Se puede ordenar por nombre.
   -  Tiene paginación, 10 usuarios por página, y debe mantenerse la página si se recarga la web.
   -  Se puede filtrar por nombre.
   -  Muestra un loading mientras carga los datos.
   -  Muestra un mensaje en el caso de que no haya usuarios.
   -  Se puede borrar un usuario y toda su información desde el listado.

## Requisitos técnicos
- La programación asíncrona debe realizarse mediante promesas o async/await.
- Entrada y salida del API en formato JSON.
- Documentación de la API.
- Control de errores.
- Buen estilo y organización de código.
- Despliegue en [Railway](https://railway.app/dashboard) del back y base de datos.
- Despliegue en [Vercel](https://vercel.com/solutions/nextjs) del front.

## Observaciones
En caso de duda o falta de especificaciones, es tarea del desarrollador tomar las decisiones pertinentes para la realización de la prueba. Estas decisiones deben ser justificadas en un fichero incluido junto a la prueba, o bien comentadas claramente en el código.