# Practica 4

## Creación de una Máquina Virtual

Primero me dirigí al portal de azure, y en su barra de busqueda puse "Maquinas virtuales", y me fuí a la opción de "Maquinas virtuales", y ahí en la barra de opciones, le di en "crear", ahí seleccione "Máquina virtual de Azure".

![](img\1.png)

Aquí simplemente cambie los siguientes aspectos:

- Grupo de recursos: Aquí cree uno nuevo para la practica llamado "Sesion4-VM", el "VM" es de "Virtual Machine".

- Nombre de la máquina virtual: Aquí le puse un nombre a la máquina virtual, solo le puse "Virtual-Machine-1".

- Región: La región la puse en "Central US", no es la más cerca que habia, pero tuve que seleccionar esa para que me dejara seleccionar otros aspectos más adelante.

- Imagen: Este es el sistema operativo que la máquina virtual tendra, seleccione windows 11, ya que nunca lo e probado y me gustaría hacerlo xd.

- Tamaño: Esta es la característica por la cuál seleccione "Central US", y se escoge automaticamente, ya que es la única disponible "estándar".

- Nombre de usuario: Este es el nombre de usuario que tendra la cuenta de windows de la máquina virtual, solo le puse "MrGv1".

- Contraseña: La contraseña de la cuenta de windows que se usara en la máquina virtual.

- Confirmo que dispongo de una licencia válida de Windows 10 con derechos de hospedaje multiinquilino.: No se de que sea eso, pero Jesús nos dijo que la marcaramos.

![](img\2.png)

Luego solo le dí al botón de "Revisar y crear", y cuándo valido los datos, cree la maquina virtual, en lo que se implementaba, descargué una aplicación de la tienda de Microsoft para abrir las máquianas virtuales, aplicación que nos recomendo Jesús.

![](img\3.png)

Una vez implementada la máquina, me dirigí a ella, le di en el botón de "coenctar" y a "RDP".

![](img\4.png)

Una vez ahí le di al botón de "Descargar archivo RDP".

![](img\5.png)

Una vez acabado de descargar, abri el archivo con la aplicación que descargué anteriormente de la Microsoft Store.

![](img\6.png)

Una vez ahí puse el usuario y contraseña que puse en la creación de la máquina virtual, y una vez ahí, configure los aspectos básicos de Windows y listo estaba en mi Máquina virtual.

![](img\7.png)

Después cree otra máquina virtual, igual que la otra, exepto que el nombre de la máquina virtual por "Máquina-Virtual-2" y el nombre del usuario a "MrGv2", y lo puse en el mismo grupo de recursos que la anterior máquina virtual.

![](img\8.png)

Para este no descargue ningún archivo, en cambio me fuí al grupo de recursos, fuí a la red virtual que se creo junto a las máquinas virtuales, solo es una, ya que ambas maquians están conectadas a la misma red.

![](img\9.png)

Después ahí me fuí a la lista de pestañas de la izquierda, y en el bloque de "Configuración", y de ahí a la pestaña de "Dispositivos conectados".

![](img\10.png)

Ahí solo vi la Dirección IP de la segunda máquina virtual que cree.

![](img\11.png)

Después en la primera máquina virtual, abrí powershell como administrador, y escribi "mstsc /v:10.0.0.5".

![](img\12.png)

![](img\13.png)

El cómando es para abrir la segunda máquina virtual, entonces se abrio la ventana que me pedia el nombre y usuario de la segunda máquina, después me pregunto si estaba seguro de que quería conectarme, le di que si.

![](img\14.png)

![](img\15.png)

Después se abrio la máquina, la configure, y así es cómo abrí una máquina virtual dentro de otra máquina virtual.

![](img\16.png)

Ya por úlitmo detuve lás máquians virtuales, por que cada una de estas cobra por cada hora que estre funcionando, aunque no la estés usando, se cobra.

![](img\17.png)

![](img\18.png)