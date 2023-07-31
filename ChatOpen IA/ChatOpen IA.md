<h1>Nest.js</h1>
lenguaje 
typescript viene por defecto pero también permite vanilla javascript 
**Prerequisitos** 
- nestjs
**instalacion** 
- npm i -g @nestjs/cli
- nest new project-name 

<h2>Node HTTP framework</h2>
- express 
- fastify

**controladores**
vigilantes de los que sale y entra dentro de backend
los controladores son los encargados de escuchar lo que busca y genera una respuesta 

**PostMan**
Es una herramienta muy popular para probar y desarrollar APIs (Interfaces de Programación de Aplicaciones). Es un cliente HTTP que facilita la creación, envío y gestión de solicitudes HTTP a través de diferentes métodos, como GET, POST, PUT, DELETE

**Código de status HTTP**
Código de status HTTP es una parte fundamental del protocolo HTTP (Hypertext Transfer Protocol). Es un número de tres dígitos que se envía en la respuesta del servidor a una solicitud realizada por un cliente (por ejemplo, un navegador web o una herramienta como Postman) para indicar el resultado del procesamiento de la solicitud.

**Metodos HTTP**
son un conjunto de comandos utilizados para indicar la acción que se debe realizar en un recurso específico en un servidor. Cada solicitud HTTP contiene un método, que determina la operación que se desea realizar en el recurso.

**Implementar operaciones CRUD**(crear, leer, actualizar, eliminar)
<h2>Coneccion con la API de Chat OpenIA</h2>

entramos a la pagina oficial **CHAT OPEN IA** y iniciamos sesión y seleccionamos unaa casilla API y generamos un código que el sistema no da cuando ya se genera acceso a una API 

**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**

Nosotros ya obtuvimos un código ya realizado el cual solo debíamos colocar el código para tener una api personal 

Una ves ya colocamos la Key que nos da **chat Openai** para que genere ya respuestas debemos modificar en **POST MAN** 
![[Pasted image 20230731000114.png]]