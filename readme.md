#  __MD y Git__  

## EJERCICIO1:
##### 
>- [x] 1.1 - Crea un directorio llamado __repo01__ en local (***en terminal***) y Identifica que el repositorio se ha iniciado.
>>![no_se_ve_na_JAJA_Q_LOKO](./Capturas%20MD%20y%20GIT/1.1.PNG "JAJA Q LOKO")
>- [x] 1.2 - añade un documento llamado __readme.md__ dentro del repositorio (recuerda que ***MD*** es la extension de los ficheros de __Markdown__) y documenta en u interior todos los pasos que vas realizando para crear un repositorio,etc. Puedes añadir fotos o lo que creas conveniente
>- [x] 1.3 - Añade el fichero que acabamos de añadir al reposiorio al __staging area__, visualiza el estado del repositorio (__con git status__) y ha un __snapshot__ (***commit***) del fichero hacia nuestro repositorio local.¿En que "file status ***lifecycle***" se encuentra el fichero?
> + Se añade a ***SA*** con ***git add***  
![no_se_ve_na_JAJA_Q_LOKO](./Capturas%20MD%20y%20GIT/1.3.PNG "JAJA Q LOKO")
>- [x] 1.4 - Intenta subir los ficheros alrepositorio remoto mediante el comando __git push__ ¿se te ocurre que esta pasando?
>
>- No se encuentra configurado un repositorio remoto
>
>- [x] 1.5 - Ejecuta el comando __git remote -v__ e investiga porque no nos aparece nada
>- __git remote -v__ imprimirá la lista de nombres de repositorios guardados, por tanto no sale ninguno por que no tengo ninguno guardado
>- [x] 1.6 - Crea un repositorio remoto llamado __repo01__,asocialo a turepositorio local
>- al vincularlo e a echo autentificarme por ser el primer repositorio que añado desde aqui
>![no_se_ve_na_JAJA_Q_LOKO](./Capturas%20MD%20y%20GIT/1.6.PNG "JAJA Q LOKO")
>- [x] 1.7 - Vuelve a ejecutarel comando __git remote -v__ nuevamente y explica por que ahora si que aparece
>-aparece por que he "linkeado" los repositorios (ahora tiene un destino para el contenido del repositorio)
>>![no_se_ve_na_JAJA_Q_LOKO](./Capturas%20MD%20y%20GIT/1.7.PNG "JAJA Q LOKO")
>- [x] 1.8 - Sube los cambios que hemos subido al snapshot local (***comit***) hacia el repositorio remoto
>![no_se_ve_na_JAJA_Q_LOKO](./Capturas%20MD%20y%20GIT/1.8.PNG "JAJA Q LOKO")
>- [x] 1.9 - Ves al repositorio remoto (en este caso __GitHub__) y comprueba que se haya realizado el ***comit*** correctamente y observa que pasa en el repositorio 
___
## EJERCICIO2:
##### 

>- [x] 2.1 -Crea un repositorio __repo02__ desde __GitHub__.¿Seria considerado un repositorio?
> - Mientras la carpeta __.Git__ este dentro de este sera un repositorio
>- [x] 2.2 - Posteriormente,clonalo (mediante el comando __git clone__), lo que realizara una copia del repositorio remoto en nuestro equipo, creando con ello un repositorio local a partir del repositorio remoto
>- [x] 2.3 - Añade un fichero __readme.md__ y ejecuta los comandos pertinentes hasta llegar a poder realizar un ***commit***
>- he echo una compia del readme.md que tengoen __repo01__ en __repo02__
>- [x] 2.4 - Haz un resumen de los comandos de __Git__ con los que hemos tabajado. Puedes utilizar tablas, imagenes, titulos, enlaces, etc.


| Comando | Descripción |
| ------- | ----------- |
| `git init` | Inicializa un nuevo repositorio Git en el directorio actual. |
| `git clone <URL>` | Clona un repositorio Git existente en un nuevo directorio. |
| `git add <archivo>` | Añade un archivo al área de preparación (staging area) para ser incluido en el próximo commit. |
| `git commit -m "<mensaje>"` | Crea un nuevo commit con los cambios en el área de preparación y asigna un mensaje descriptivo. |
| `git status` | Muestra el estado actual del repositorio, incluyendo los archivos modificados, añadidos o eliminados. |
| `git log` | Muestra el historial de commits realizados en el repositorio. |
| `git push` | Envía los commits locales al repositorio remoto. |
| `git pull` | Obtiene los cambios del repositorio remoto y los fusiona con la rama actual. |
| `git branch` | Muestra las ramas existentes en el repositorio. |
| `git checkout <rama>` | Cambia a la rama especificada, descartando los cambios no guardados. |
| `git merge <rama>` | Fusiona la rama especificada con la rama actual. |
| `git remote add <nombre> <URL>` | Asocia un nombre con un repositorio remoto en la URL especificada. |
| `git remote -v` | Muestra los repositorios remotos asociados al repositorio local. |

>## **Ejercicio 4**  
>- [x] **4.1 Crear repositorio local y remoto con nombre repo04**
>![no_se_ve_na_JAJA_Q_LOKO](./Capturas%20MD%20y%20GIT/4.1.PNG "JAJA Q LOKO")
>- [x] **4.2 Añadir README.md y subir los cambios al repositorio**  
>- [x] **4.3 Crear rama con mi nombre y fecha actual (dani18052023)**  
>- [x] **4.4 Desde la nueva rama editar el archivo**  
>- [x] **4.5 Hacer 3 commits**   
>- [x] **4.6 Fusionar la rama con main y hacer push**  
>- [x] **4.7 Eliminar solo localmente la rama fran18052023**  
>
>## **Ejercicio 5**
>- [x] **5.1 Crear repositorio local y remoto con nombre repo05**  
>- [x] **5.2 Añadir README.md**  
>- [x] **5.3 Crear rama con mi nombre y fecha actual (dani19052023)**  
>- [x] **5.4 Hacer 3 commits**  
>- [x] **5.5 Subir ambas ramas**  
>- [x] **5.6 Realizar un commit no fast-forward**  
>- [x] **5.7 Visualizar el resultado**
