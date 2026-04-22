# INGENIERÍA EN CIENCIAS DE LA COMPUTACIÓN

# REDES DE COMPUTADORAS

## DEBER 4

**Objetivos:**

Al completar el desarrollo de esta tarea, el estudiante deberá ser capaz de:

```
a) Utilizar Google Colab y Python para realizar consultas a un API REST.
b) Realizar diferentes consultas HTTP como GET, POST, PUT y DELETE.
c) Utilizar Wireshark para identificar información de las diferentes capas del modelo
de referencia OSI cuando se realizan las consultas al API REST.
```
**Indicación General:**

Desarrollar el código necesario para el experimento en un Jupyter Notebook y ejecutarlo
en Google Colab. El estudiante debe investigar sobre el uso de la librería requests para
crear las solicitudes HTTP. Además, es necesario comprender el formato JSON que se
utiliza en las solicitudes.

**Entregable:** el notebook a desarrollar se debe subir a la carpeta “Deber 4 ” que se
encuentra en D2L. La carpeta estará activa hasta las 13 h 00 del jueves 23 de abril de
2026.

**Instrumento de Evaluación:**

En lo que respecta a la evaluación de la tarea, se ha definido una rúbrica. Una vez que
se haya evaluado la guía, el estudiante podrá observar el contenido de la rúbrica en D2L.
La rúbrica contendrá información importante de retroalimentación sobre los posibles
errores que se hayan detectado.

- **Enunciado:** JSON Placeholder (https://jsonplaceholder.typicode.com/) es un
    servicio gratuito que provee una API falsa (fake API) para realizar pruebas o
    prototipos con datos de tipo JSON. Fue creado para permitir a desarrolladores probar
    fácilmente solicitudes HTTP (GET, POST, PUT, DELETE) en proyectos sin


```
necesidad de configurar un servidor real. El API no guarda datos realmente (tras un
POST exitoso, la nueva información no se almacena de forma permanente), pero
simula respuestas válidas para las operaciones. Acceder a la sección “Guide” para
aprender sobre el uso del API y el formato JSON que se utiliza para las diferentes
solicitudes.
Una vez que se ha comprendido el funcionamiento del API, realizar los siguientes
procedimientos:
a. Recuperar todos los usuarios que existen y mostrar en pantalla el ID del usuario
y el nombre.
b. Recuperar y mostrar en pantalla los posts de un usuario en particular. Para esto,
se debe especificar el ID de usuario.
c. Crear un nuevo post en el servidor.
d. Actualizar un determinado post de un usuario determinado.
e. Eliminar un determinado post.
```
Por cada proceso, utilizar Wireshark para identificar la siguiente información:

- Capa 2: MAC origen y destino.
- Capa 3: IP origen y destino.
- Capa 4: Puerto TCP origen y destino.
- Capa 7: header HTTP (es necesario observar el tráfico cifrado).


