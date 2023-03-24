Bienvenido al proyecto de PP2 
=============================

### Nociones del proyecto 

 Este proyecto debe ser realizado bajo una serie de parametros como el control de versiones y las tecnologias que se utilizaran ademas de la metodologia de trabajo y los requerimientos del proyecto en si.

---

### Metodologia

 Este proyecto sera realizado en metodologia SCRUM. El equipo se dividira las tareas en funcion de sus fortalesas y luego deberan reportar sus avances y explicar su desarrollo en una reunion que se realizara periodicamente al finalizar cada Sprint; ademas de distintas reuniones de desarrollo que seran organizadas por el SCRUM Master en caso de tener algun problema o querer explicar algun tema en especifico, esto ultimo tiene la intencion de transmitir el conocimiento a todos los integrantes del equipo. 

---

### Tecnologias

 En este proyecto utilizaremos las tecnologias de Spring en java para desarrollar una base de datos y React en javascript para realizar la interfaz grafica.

---

### Control de versiones 

 Utilizaremos Git en un repositorio de GitHub para el control de versiones, dicho repositorio sera compartido y la cuenta que posee la rama Main no sera manipulada hasta la etapa de prueba donde se actualizara, cada miembro del equipo tendra su propia rama vinculadad a su cuenta donde realizara sus tareas.
 Para acceder al repositorio podran hacer click [aqui](https://github.com/OurProgramingHub/PP2.git "OurProgramingHub").

 Ademas dejaremos una serie de comandos que deberan seguir para mantener el control de versiones lo mas limpio y ordenado posible.
 
> Iniciar GIT 

* Lo primero que haremos sera crear una carpeta donde se ubicara tu repositorio local, una vez creada la arrastraremos a tu editor de codigo de confianza y abriremos una terminal desde esa carpeta o desde la direccion de esa carpeta realizaremos el comando `cmd` para abrir una consola.

* Desde la terminal o consola vamos a iniciar un repositorio local para poder trabajar en el atravez del siguiente comando.

> `git init`

* Recuerda que este comando debe ser ingresado en la terminal cada vez que abran su editor de codigo antes de cualquier cosa; luego de esto podemos empezar a trabajar con el repositorio.

> Vincularce al repositorio.

* El repositorio remoto del Hub va a ser el que posea todos los archivos del proyecto, este mismo debe ser clonado para poder usar los archivos, para ello utilizaremos el siguiente comando.

> `git clone https://github.com/OurProgramingHub/PP2.git`

* Una vez clonado dentro de nuestra carpeta se creara otra carpeta donde esta el clon del repositorio original, ahora arrastraremos la carpeta con el clon del repositorio a tu editor de codigo de confianza y abriremos una terminal desde esa carpeta o desde la direccion de esa carpeta realizaremos el comando `cmd` para abrir una consola e ingresaremos el comando `git init`.

* Ya estamos vinculados con el repositorio remoto pero no podremos efectuar cambios en el; en este momento se deberia añadir tu usuario de GitHub como colaborador del proyecto. Te llegara una notificacion a tu correo y a tu cuenta de GitHub, verifica la invitacion y acepta ser colaborador del Hub.

> Actualizar tu repositorio local

* Las actualizaciones del repositorio remoto se avisaran con anticipacion, esto tiene como finalidad mantener el proyecto lo mas controlado y libre de errores entre actualizaciones, claro esta que despues de cada actualizacion los colaboradores deberan actualizar sus repositorios locales para mantener su copia del proyecto actualizada y funcional para esto se debe usar el comando.

> `git fetch`

* Recuerda que las actualizaciones del proyecto seran previamente informadas, pero recomendamos que cada vez que inicien sus editores de codigo ingresen este comando en la terminal despues de iniciar GIT y antes de realizar cualquier cambio al codigo para evitar errores con el repositorio.

> Crea una rama de trabajo

* Una vez verificado como colaborador lo siguiente sera crear una rama de trabajo (branch) para poder subir todo tu trabajo.

* Lo primero que haremos sera verificar en que rama nos encontramos, atravez del siguiente comando.

> `git branch`

* Una vez verificamos en que rama nos encontramos lo siguiente sera crear una rama propia, con el siguiente comando.

> `git branch tu-rama`

* Recuerda que tu rama de trabajo es tu espacio de desarrollo y de nadie mas porfavor evita modificar el codigo desde una rama que no sea la tuya.

* Luego de crear tu rama deberas direcionarte a ella, utiliza el siguiente comando.

> `git checkout tu-rama`

* Una vez en tu rama ya eres libre de trabajar en el codigo.

> Subir tu trabajo al repositorio

* Una vez terminemos los cambios que queremos realizar al codigo debemos subirlos al repositorio en nuestra rama; para esto debemos seleccionar la rama, añadir los cambios que queremos realizar, comprometerlos y subirlos siguiendo esta serie de comandos.

> `git status -s`

* Este comando te indicara cual es la rama en la que te encuentras y cuales son los archivos que fueron modificados con una *M*, cuales fueron Añadidos con una *A* y cuales aun no fueron añadidos con *??* veras que los archivos no estan actualizados porque sus signos estan marcados de color rojo.

* Supongamos que el archivo que queremos añadir o actualizar es un archivo de texto y se llama archivo-x, para esto simplemente utilizamos el siguiente comando.

> `git add archivo-x.txt`

* Si quisieramos añadir mas de un archivo solo debemos agregar un espacio al nombre del primer archivo y escribir el nombre del siguiente y asi sucesivamente; tambien podriamos realizar el comando `git add .` que añade todos los archivos de la carpeta al stage, pero esto no es una buena practica; ya que puede subir archivos no deseados a la instancia y entorpecer el flujo de trabajo haciendo que colicionen archivos de distintas ramas y generar perdidas de trabajo tanto de tu rama como la de tus compañeros es por eso que se recomienda no utilizar este comando.

* Una vez añadido el archivo si utilizamos el comando `git status -s` veremos que su signo ya no esta en color rojo si no en color verde, esto no significa que esta guardado en el repositorio solo indica que fue añadido a una instancia de trabajo conocida como stage.

* Ahora debemos realizar un comentario para indicar los cambios que realizamos esto es importante para poder pasar a la instancia de guardado conocida como commit, el commit debe ser entendido como un empaquetado de datos donde le ponemos un nombre a una caja en la cual ponemos los cambios que realizamos, este paquete esta comprometido para ser subido al repositorio. El repositorio solo recibe paquetes y los ubica en los lugares correspondientes, ademas comentar los cambios es necesario para que el control de versiones se efectue de forma ordenada. Para efectuar el commit realizamos el siguiente comando con el con el comentario que queramos indicar entre comillas.

> `git commit -m "comentario x"`

* Una vez comprometido ya tenemos todo en orden para subirlo al repositorio desde nuestra rama. Desde aqui debemos usar un comando que va a realizar una verificacion del repositorio principal y lo actualizara en su defecto al mismo tiempo va iniciar un proceso conocido como merge que nos hara elegir que version de cada archivo queremos conservar, es importante seleccionar bien estas versiones para evitar conflictos con el repositorio. Este comando es.

> `git pull`

* Despues de realizar dicho merge se sube al repositorio remoto desde nuestra rama con el siguiente comando.

> `git push -u origin tu-rama`

* Una vez realizado push se debera informar al gestor del Hub que llevara a cabo la actualizacion de la rama de pruebas y posteriormente de la rama Main si todo se encuentra en orden.

---