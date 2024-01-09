## Git y github

Cuando editamos un archivo y queremos inicar **GIT**, usamos el comando **`GIT INIT`**, luego tenemos que agregar el comando **`GIT ADD 'NOMBRE DE ARCHIVO'`** para agregar los cambios en memoria, sino aparece el siguiente inconveniente si usamos **`GIT STATUS`**

![Add](image.png)

Para agregar cambios en el archivo se usa **`GIT ADD NOMBREARCHIVO`** luego si hacemos **`GIT STATUS`** nos saldra los siguiente:

![Status](image-1.png)

Nos arroja el archivo en color verde, porque falta agregar **`GIT COMMIT -M "COMENTARIO"`** el comando sirve para guardar los cambios que hay en la cache en el repositorio, el cual luego es representado por una instancia de tiempo el cual se hizo dicho cambio, es decir crear un punto de historia de cambio, para luego si el usuario quiere, revertir los cambios.

Se puede usar infinitos commits para cada cambio pero solo una vez por ejecucion de **`GIT ADD`**, luego para ver el historia de commits, usamos el comando **`GIT LOG`**

![LOG](image-2.png)

Se puede hacer comparaciones de commits con el comando **`GIT DIFF COMMIT1 COMMIT2`**, es preferible que primero sea el mas antiguo y el segundo el mas nuevo.

![Alt text](image-3.png)

##Explicando el Staging

El staging es el lugar donde se guardan temporalmente los cambios, para luego ser llevados definitivamente al repositorio. El repositorio es el lugar donde se guardan todos los registros de los cambios realizados a los archivos.
![Alt text](image-4.png)

![Alt text](image-5.png)
