# 1.1 Ejercicio 1 


## **Creación de Repositorio**  
Vamos a crear una carpeta la cual llamaremos repo1, ahora en visual studio code, iniciamos con el terminal en bash, haciendo **GIT  INIT** de la siguiente manera



 ![Esta es la imagen de inicio del repositorio](./IMG/1.png)

# 1.3 Stagin area  

Nuestro fichero ahora si se hace un **GIT ADD .** el punto nos permitirá iniciar dentro de la carpeta 

 ![Esta es la imagen de stagin area](./IMG/2.png)


ahora nuestro archivos se encuentran en **stagin area**, procedemos a subirlo con...


### **GIT Commit**  

procedemos a subir nuestros archivos a nuestro repositorio local


 ![Esta es la imagen de commit](./IMG/3.png)

# 1.4 Git Push  

Ahora trataremos de enviar el git a la nube

![Esta es la imagen de git push](./IMG/4.png)

nos damos cuenta que no  tenemos un destino para el repositorio que se  encuentra en la nube



# 1.5 Git Remote 

si ejecutamos  este comando 

![Esta es la imagen de git remoto](./IMG/5.png)

nos nos saldra ningun contenido porque lo que esta haciendo es mostrar si tenemos un repositorio remoto.

# 1.6 Repositorio Remoto

Crearemos un repositorio remoto


![Esta es la imagen de Repositorio remoto](./IMG/6.png)

ahora lo asociamos a nuetro repositorio local 

![Esta es la imagen de git push](./IMG/7.png)


# 1.7 Git Rem -v
Si solvemos a ejecutar el comando de git remote -v nos daremos cuenta de lo siguiente:
Indica que nuestro repositorio local se ha podido asociar al repositorio remoto

![Esta es la imagen de git remote -v](./IMG/8.png)

# 1.8 Commit local

Para subir los cambios que hemos hechos en el local para el repositorio remoto, lo que tendremos que hacer es un git push.

![Esta es la imagen de git push](./IMG/10.png)

# 1.9 Repositorio remoto

>Hemos agregado cada repositorio con un git add.
>>subimos los repositorios con un git commit

>>>Finalmente agregamos esos repositorios a un repositorio remoto

![Esta es la imagen de git push](./IMG/11.png)



#  Ejercicio 2

## 2.1 Creación  repositorio remoto
si hemos creamos un repositorio en github,  este sera un repositorio remoto

![Esta es la imagen de creacion repositorio remoto](./IMG/12.png)


## 2.2 Clonacion repositorio

Se ha comentado que la forma practica para trabajar en un repositorio es clonarlo, por lo tanto procederemos a hacerlo.

![Esta es la imagen de clon del repositorio](./IMG/13.png)

## 2.3 Fichero Readme

Vamos a crear un fichero readme.md dentro del repositorio que hemos clonado, agregamos el repositorio a stagin area, y ahora con un commit, lo subiremos a nuestro repositorio loccal

![Esta es la imagen de clon del repositorio](./IMG/14.png)



## 2.4 Manual Marckdown

este paso ya lo haremos en el siguiente repositorio que hemos creado y sobre la cual se ha crado el readme.


# 3.1 Bloque GIT:v: 

Bloque de ejercico de git


![Esta es la imagen de clon del repositorio](./IMG/18.png)


# 4.1 FAST FORWARD :v: 
El fast forward es que nos permite agregar un brach a la rama principal, este automaticamente se utiliza.

>Creamos una carpeta la cual llamaremos repo04, 
>>agregamos un **readme.md**, e iniciamos
iniciamos nuestra carpeta local para que sea un repositorio local.

>>> - [x] **Git init .**
>>> - [x] **Git add .**
>>> - [x] **Git commit -m "repo04"**
>>> - [x] **Creacion repositorio  remoto**
![Esta es la imagen de creacion repositorio remoto](./IMG/15.png)

>>> - [x] **git add origin and push**
![Esta es la imagen sobre git push](./IMG/16.png)

>>> - [x] **Creamos rama con nombre y fecha**
con un git branch <> podemos crear ramas, en este caso creamos una con nuestro nombre y fecha
![Esta es la imagen sobre git branch](./IMG/17.png)


>>> - [x] **Realizamos 3 commits sobre la rama que hemos creado con nuestro nombre**
luego de hacer los commits tendremos verificamos que el head direcciona sobre nuestra branch sobre el tercer commit
![Esta es la imagen sobre git commit sobre branch](./IMG/19.png)

>>> - [x] **Fucionar mi rama en master**
mi branch tiene que juntarse con main, que es la rama principal, entonces nos ubicamos primero en main, seguidamente buscamos la rama, 
![Esta es la imagen sobre git commit push sobre branch](./IMG/21.png)


>>> - [x] **Push hacia la nube**
haremos un push hacia la nube de la siguiente manera

![Esta es la imagen sobre git commit push sobre branch hacia la nube](./IMG/22.png)


Ahora eliminamos el branch en local
![Esta es la imagen sobre git commit push sobre branch hacia la nube](./IMG/23.png)

# 5.1 NO FAST FORWARD :v: 

Continuamos con nuestra actividad, seguiremos los primeros pasos del ejercicio 4, lo que nosotros necesitamos saber es la diferencia entre commits con no forwar, en la siguiente img,

![Esta es la imagen sobre git commit push sobre branch hacia la nube con un no forward](./IMG/24.png)


>>> - [x] **Resultado**
ahora veremos como con el comando **git log --all --decorate --oneline --graph** nos mostrar informacion importante

![Esta es la imagen sobre git commit push sobre branch hacia la nube con un no forward](./IMG/25.png)


###  **Diferencia merge ff y no-ff**

Con el Merge ff, nos permite fusionar la rama a la rrama main sin autorizacion, esta es la que ejecutamos  por defecto, y con no-ff ocurre lo contrario, permitiendo un historial de su avance 