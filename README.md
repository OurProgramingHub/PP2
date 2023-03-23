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
* Una vez creada una carpeta, desde la terminal vamos a iniciar un repositorio local para poder trabajar en el atravez del siguiente comando.

> `git init`

* luego de esto podemos empezar a trabajar con el repositorio.

> Clonar el repositorio.
* El repositorio original del Hub debe ser clonado, para ello utilizaremos el siguiente comando.

> `git clone `

> Pasar el trabajo al repositorio
* Una vez terminemos los cambios que queremos realizar al codigo debemos subirlos al repositorio en nuestra rama; para esto debemos seleccionar la rama añadir los cambios que queremos realizar comentarlo y subirlo siguiendo esta serie de comandos.

> `git status`
* Este comando te indicara cual es la rama en la que te encuentras y cuales son los archivos que fueron modificados y veras que el archivo no esta guardado en el repositorio porque esta marcado de color rojo. 
* Supongamos que el archivo que queremos añadir o actualizar se llama archivo-x, para esto simplemente utilizamos el siguiente comando.

> `git add archivo-x`

* Una vez añadido el archivo si utilizamos el comando `git status` veremos que ya no esta en color rojo si no en color verde, esto no significa que esta guardado en el repositorio solo indica que fue añadido a una instancia de trabajo conocida como stage.
* Ahora debemos realizar un commit para indicar los cambios que realizamos esto es importante para poder pasar a la instancia de guardado el commit debe ser entendido como un empaquetado de datos donde le ponemos un nombre a una caja donde ponemos los cambios que realizamos, el repositorio solo recibe paquetes y los ubica en los lugares  

---