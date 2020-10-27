# Administracion-de-discos


**Importante, en el video veremos que habla de discos y volúmenes, podemos pensar en el disco como el dispositivo físico que podemos comprar y añadir a nuestro PC y los volúmenes como las particiones lógicas que podemos hacer a nuestros discos.**

**Un disco puede tener cero, uno o más volúmenes.**



**1. ¿Qué características tiene el formato de disco?**

* MBR: Registro de Arranque Maestro es usado para crear una tabla de particiones, tiene ciertas limitaciones, es usado para discos duros que tienen una capacidad menor de 2 TB y solo puede trabajar con 4 particiones primarias.

* GPT  GPT sustituye al MBR que se usaba en la BIOS, en las particiones utiliza entradas de 64 bits para el direccionamiento,por lo que esra pensado para discos de mayor capacidad el tamaño máximo de cada partición es mayor y ofrece varios terabytes

**2. En el video se creo un disco de 64000 GB (64 TB), en nuestro caso creamos  un nuevo disco de 10 GB en VirtualBox, tendrás que apagar la máquina virtual para poderlo crear.**

**Debes ir a configuración > almacenamiento > en el controlador IDE añadir nuevo disco y crear tipo VDI de 10 GB. Si no te aclaras busca algún video en internet, es un problema que te podría surgir en la realidad y deberías poder solventarlo tu solo.**

**3. Envía un pantallazo del administrador de discos en el que se vea el nuevo disco de 10GB y otro pantallazo desde el administrador de archivos donde se vean todos los HDs que tenemos**

**4. Al formatear un disco duro (HD) ¿que 3 sistemas de archivos podemos usar?**
FAT32 NTFS exFAT

**5. Reduce el nuevo disco creado en 2000 MB, de esta forma tendremos 2 volumenes y formatea el nuevo con NTFS como el anterior, envia pantallazo desde el administrador de archivos.**

**6. Extiende el Volumen de 8 GB para volver a tener un HD de 10GB, despues de esto elimina el volumen (no el disco).**

**7. ¿Qué pasaría si borramos el volumen C:**

VIDEO administrar discos, desde el Administrador del servidor
**8. Envia un pantallazo de los volúmenes que tienes en tu servidor desde el administrador de servidor.**

**9. Crea un nuevo volumen de 6Gb, letra E: y etiqueta Datos**

**10. Crea un nuevo volumen resto de Gb que quedan en el disco, letra F: y etiqueta Datos2**

**11. Cambia la letra del volumen F: a Z:**

**12. Envía pantallazo desde el explorador de archivos pantallazo donde se vean los nuevos volumenes recien creados.**
