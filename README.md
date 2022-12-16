# Entornos
## Practica 1
### PARTE A 
En primer lugar crearemos un repositorio en nuestra cuenta de Github.
![image1](https://user-images.githubusercontent.com/114931679/201414455-fa226e28-433d-4600-97cd-d97882533729.png)<br>

![image2](https://user-images.githubusercontent.com/114931679/201414651-33b4f376-c9f3-4bc5-8813-86af7d703ee1.png)

Una vez creado, abriremos *Git CMD* para empezar a escribir comandos.
Entraremos a la dirección donde encontraremos la práctica a realizar, es decir la carpeta de git que está dentro de documentos, usando el comando _**cd**_

![image3](https://user-images.githubusercontent.com/114931679/201415303-97dfd872-97e3-48b2-be9c-a88f66e11f6f.png)

Dentro de la carpeta, copiaremos la url correspondiente para clonar nuestro repositorio creado anteriormente. Usaremos el comando _**git clone.**_
Se crea el directorio .git oculto

![image4](https://user-images.githubusercontent.com/114931679/201415633-a16f70b0-4134-4cce-828c-008fae6ac148.png)

Entramos al repositorio

![image5](https://user-images.githubusercontent.com/114931679/201415708-a5f3b1f3-3627-4692-82b7-1a1f72d8509b.png)

Y ahora añado el archivo Horario.html con el comando _**git add**_

![image6](https://user-images.githubusercontent.com/114931679/201415857-53ce157e-f792-4187-a62f-35ec0db42be9.png)

Ahora registraremos un cambio en el historial mediante _**git commit**_

![image7](https://user-images.githubusercontent.com/114931679/201416047-47d2d4ec-8d26-47a9-bbcf-9fe6f6de5461.png)

Guardaremos los cambios. Es necesario permitirle el acceso. Con el comando _**git push origin main**_ nos redirige a la página de github para iniciar sesión y guardar los cambios en el repositorio main. Y con el comando _**git pull origin main**_ llevaremos los cambios a la copia local.

![image8](https://user-images.githubusercontent.com/114931679/201416416-844aecf2-70d5-417b-82a8-58609d01bdbf.png)

Si entramos a nuestro repositorio en GitHub, se visualizará así:

![image9](https://user-images.githubusercontent.com/114931679/201416502-779266b7-b972-43dc-b9d1-3198f088b0bc.png)

Crearé otro archivo hola.txt para practicar hacer cambios y volver al estado original del archivo con el comando _**git checkout nombre-de-archivo**_

![image10](https://user-images.githubusercontent.com/114931679/201416591-4773dae9-831e-4fb5-a8c8-d402fa6af84b.png)

Ya aparece en el repositorio GitHub.

![image11](https://user-images.githubusercontent.com/114931679/201416695-1e153921-039f-461e-8ded-1e0581e1e48d.png)

Abro el archivo hago un par de cambios (añado hhhhh y guardo):

![image12](https://user-images.githubusercontent.com/114931679/201416771-b52d4b94-f3a9-4cff-94b1-1571d406aef5.png)

A continuación, ejecuto el comando _**git checkout**_

![image13](https://user-images.githubusercontent.com/114931679/201416846-3eca8919-ef70-4e3d-86dd-f4b938178bd5.png)

Y vuelvo a entrar para chequear que los cambios se han deshecho.

![image14](https://user-images.githubusercontent.com/114931679/201416955-2e3f7f9e-2fb2-46b1-832b-e2d5c64e678f.png)

Se ha cambiado con éxito.

### PARTE B
En primer lugar crearemos un repositorio en nuestra cuenta de Gitlab, una vez estemos registrados.

![image15](https://user-images.githubusercontent.com/114931679/201418136-49e6041c-04e5-4cd2-a792-dc927a2db7cd.png)

Abriremos *Git CMD* para empezar a escribir los comandos aprendidos.
Entraremos a la dirección donde encontraremos la práctica B, es decir la carpeta de gitlab que estará dentro de documentos, usando el comando _**cd**_
Además usaremos el comando _**git clone**_ para clonar el repositorio

![image16](https://user-images.githubusercontent.com/114931679/201420324-1ae838ca-a839-4c5e-8b26-12d4fb0a86d1.png)

Se abre el servidor de GitLab, y nos pide que nos identifiquemos para darle el permiso correspondiente.

![image17](https://user-images.githubusercontent.com/114931679/201421273-800fed4c-5d6d-4f60-85e9-904c4cea9bf4.png)
![image18](https://user-images.githubusercontent.com/114931679/201421345-09184d79-2cf6-41ba-9a42-53485ec12d68.png)

Entraremos al repositorio clonado _PracticaB_ y añadiremos con el comando _**git add**_ un documento .txt
Siempre podemos consultar si se ha creado correctamente usando _**git status**_

![image19](https://user-images.githubusercontent.com/114931679/201421998-35535e1c-4056-4552-a825-18b69460f7b5.png)

Se ha añadido el archivo y además se ha creado el documento README.ME correspondiente
![image20](https://user-images.githubusercontent.com/114931679/201422207-da00b972-ba5f-48c9-8dc3-8e87e8906ef0.png)

Ahora utilizando _**git commit -m**_ se guardarán los cambios hechos en el área de preparación, es decir el staging area. Y con _**git push origin main**_ lo subiremos al repositorio main

![image21](https://user-images.githubusercontent.com/114931679/201423137-9acab858-4232-4b78-9b77-c5769ae79ca9.png)

Ya lo tenemos subido.

![image21](https://user-images.githubusercontent.com/114931679/201423264-0d75a75c-fca7-41e2-bf66-86f198c4a30a.png)

Para que todo esté conectado, ejecutaremos el comando _**git pull origin main**_
### Los cambios realizados en el repositorio main se interconectarán con nuestra copia local.

![image22](https://user-images.githubusercontent.com/114931679/201423680-3b0dce21-6afb-4ef2-a682-9a981af748a5.png)

Ahora realizaremos la última comprobación para poder hacer los cambios que deseemos, mediante los comandos _**git reset HEAD nombre-de-archivo**_  
y _**git checkout nombre-de-archivo**_ porque ya habiamos realizado el ADD.

Añadimos una modificación dentro del documento:

![image23](https://user-images.githubusercontent.com/114931679/201424079-301a1f15-7e55-412c-90a6-43297b300a3e.png)

Ejecuto los comandos mencionados.

![image24](https://user-images.githubusercontent.com/114931679/201424295-161f94ce-3343-4227-8c42-9280a0f52579.png)

Y finalmente comprobamos que se realizan los cambios con éxito.

![image25](https://user-images.githubusercontent.com/114931679/201424398-fdeb6e1e-0ebc-4595-a4ad-f399e4d54207.png)


## CAPTURAS DEL GITLAB
![image](https://user-images.githubusercontent.com/114931679/208177228-e3220a6c-1eca-4c31-8616-454da66d4ca6.png)
![image](https://user-images.githubusercontent.com/114931679/208177256-dc9cb5b2-01ef-4b46-a48c-3d13b040d2a7.png)











































