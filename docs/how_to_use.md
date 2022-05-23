## Como usar este modulo

Con este módulo podemos obtener las colas de trabajo y los datos de los
formularios creados en R.O.C, los cuales posteriormente son llenados por los
usuarios.
Ir al menú “Mods” y abrir el módulo “Rocketbot Forms”

![](imgs/1.png)

1. Login NOC <br>
Para realizar el login hacia el Orquestador es necesario lo siguiente: <br>
● URL del servidor : Indicar la URL del servidor R.O.C <br>
● Seleccionar una opcion: Indicar la opcion que se utilizara para la conexion las cuales pueden ser mediante las credenciales del usuario, API KEY o mediante el archivo noc.ini.

![](imgs/2.png)

2. Obtener cola de trabajo de Forms <br>
Este comando obtiene las colas de trabajo que se encuentran en R.O.C <br>
● Form Token: Token del formulario que se genera al momento de crear el Form. <br>
![](imgs/3.png) <br>
● Asignar a variable: Nombre de variable donde se almacenarán el o los ids
de las colas de trabajo encontradas. <br>

![](imgs/4.png)

3. Obtener datos de Forms <br>
Con este comando podemos obtener los datos del formulario, los ids creados para los elementos en el Form de R.O.C deben coincidir con el nombre de las variables en Rocketbot, con esto automáticamente se llenarán. <br>
● ID cola de trabajo: ID de la cola de trabajo que queremos leer. <br>
● Form Token: Token asociado al formulario.

![](imgs/5.png)

4. Descargar desde archivo<br>
Descarga un archivo subido a un formulario <br>
● ID cola de trabajo: Cola de trabajo del formulario <br>
● Nombre: Nombre del archivo que se va a descargar <br>
● Guardar archivo en: Ruta donde se almacenara el archivo

![](imgs/8.png)

5. Actualizar estado de cola Form<br>
Con este comando podemos actualizar el estado de la cola de trabajo en el R.O.C, indicando como realizada o no. <br>
● Estado: Estado de la cola (Done, Undone). <br>
● ID cola de trabajo: ID de la cola de trabajo a actualizar.

![](imgs/6.png)

6. Devolver mensaje a Xperience <br>
Devuelve un mensaje a Xperience especificando el Token y el mensaje a devolver

![](imgs/7.png)

## How to use this module

With this module we can obtain the work queues and the data of the
forms created in R.O.C, which are subsequently filled out by the
users.
Go to the “Mods” menu and open the “Rocketbot Forms” module

![](imgs/1.png)

1. Login NOC
To login to the Orchestrator, the following is necessary: ​​<br>
● Server URL : Indicate the URL of the R.O.C server <br>
● Select an option: Indicate the option that will be used for the connection, which can be through the user's credentials, API KEY or through the noc.ini file.

![](imgs/2.png)

2. Get work queue from Forms
This command gets the job queues found in R.O.C <br>
● Form Token: Token of the form that is generated when the Form is created. <br>
![](imgs/3.png) <br>
● Assign to variable: Variable name where the id(s) will be stored.
of the work queues found. <br>

![](imgs/4.png)

3. Get data from Forms <br>
With this command we can obtain the form data, the ids created for the elements in the R.O.C Form must match the name of the variables in Rocketbot, with this they will automatically be filled. <br>
● Work Queue ID: ID of the work queue we want to read. <br>
● Form Token: Token associated with the form.

![](imgs/5.png)

4. Download from file<br>
Download a file uploaded to a form <br>
● Work queue ID: Work queue of the form <br>
● Name: Name of the file to be downloaded <br>
● Save file in: Path where the file will be stored

![](imgs/8.png)

5. Update Queue Status Form<br>
With this command we can update the status of the work queue in the R.O.C, indicating as done or not. <br>
● State: State of the queue (Done, Undone). <br>
● Work queue ID: ID of the work queue to update.

![](imgs/6.png)

6. Return message to Xperience <br>
Returns a message to Xperience specifying the Token and the message to return

![](imgs/7.png)