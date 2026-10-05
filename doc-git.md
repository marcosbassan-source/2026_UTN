

## PARA INICIAR UN REPOSITORIO EN GIT:

GIT INIT

Cuando iniciamos un repo los archivos estan en estado "untracked" (sin seguimiento)

git add index.html (esto le da seguimiento al archivo mencionado)

git add . (le da seguimiento a todos los archivos de tu directorio root (raiz) )

O podes ignorar archivos creando en la raiz el archivo .gitignore

## VERSIONAR

Para versionar el codigo debe estar añadido.El codigo que se versiona es el que esta añadido hasta el momento

git commit -m "Primera version en GIT" (crea una version en tu repo)

## Para cambiar el nombre del ranch principal (opcional)

Git branch -M main

## Configuramos una direccion remota para nuestro repo

Git remote add origin

## Enviar el codigo 

git push -u origin main

## Para saber cual es la direccion remota
git remote -v

## Para trabajar en paralelo sin romper la pagina

git checkout -b "titulo que yo quiera ponerle" (la b es para crear, si no pones la b pasas de uno al otro)

## Para subir la nueva rama a git hub
 
git push -u origin "nombre de la rama" 

## Para combinar las ramas usamos: 

git merge "nombre de la rama que queres traer"


