Descarga o clona el proyecto en tu maquina local, mejoralo y crea un commit o rama para subirlo! no te olvides guardar los cambios!
para configurar un repositorio desde 0 se hace lo siguiente y subirlo a github:
0. EL USER, CORREO, ACCESS TOKEN, LA URL DEL REPOSITORIO,  LE RECOMIENDO COPIAR Y GUARDARLO EN UN BLOC DE NOTAS! 
0. te diriges a github te registras y creas un repositorio de manera publica, una vez creado copias el enlace del navegador!
0.1 genera tus access token personal haces lo siguiente: entra a tu perfil de github, ingresa en settings, luego a developer settings, le das en personal access token,
luego en tokens(classic) y en caducidad selecciones nunca!
PASOS A REALIZAR DESPUES DE LO ANTERIOR:
1. descarga e instala git en tu maquina en https://git-scm.com/download/win
2. dirigete a la carpeta donde esta tu proyecto en java e inicializa git bash here.(fijate que estes en la ruta correcta!)
3. en git escribe: git init ...le das enter
4. luego en el mismo git escribe: git config user.name "tu-user-de-github", tal cual como te registraste, sin las comillas. le das enter
5. luego escribe: git config user.email "tu-correo-registrado", igual sin las comillas... le das enter
6. luego escribe: git config user.password "tu-access-token", escribire mas abajo como obtenerlo, de igual manera sin comillas y das enter.
7. posterior a eso haces escribes lo siguiente: git remote add origin "url-del-repositorio-creado-en-github", igual sin las comillas.
8. luego escribes: git add . (si incluyes el punto)
9. luego escribes: git commit -m actualizarPat
10. luego escribe: git push -u origin master
11. Autorizas el acceso ingresando el codigo mostrado en pantalla. ¡Y LISTO ESO SERIA TODO!
*****AHORA PARA SUBIR LOS CAMBIOS QUE SE REALIZAN SE HACE LO SIGUIENTE:*****
0. inicializa un git bash here en la carpeta del proyecto original y escribes lo siguiente:
a. para ver los cambios no subidos en el repositorio escribes: git status (automaticamente te mostrara en rojo lo que falta subir) le das enter!
b. luego escribes: git add name-del-archivo-con-cambio (escribes el nombre del archivo que esta en rojo)
c. luego vuelves a verificar con: git status (tiene que figurar el nombre del archivo en verde)
d. luego escribes lo siguiente: git commit -m "prueba commit1" (escribes el nombre del commit que deseas, aca si con los comillas)
e. posterior a eso escribes: git push -u origin master ("master" es la rama general, pero para versiones se sube en otra rama que creare mas adelante)
ESO SERIA TODO!!!!

****AHORA PARA CLONAR EL PROYECTO A SU MAQUINA LOCAL SE HACE LO SIGUIENTE:****
a. creas tu carpeta en tu maquina e inicializas el git bash here.
b. luego escribes: git clone url-del-repositorio (pegas el link o url del repositorio en este caso del proyecto!)
c. digamos que alguien subio un cambio al repositorio en github para descargarlo inicializas tu git bash here y escribes lo siguiente: git pull origin master
ESO SERIA TODO!

****PARA CREAR RAMAS*****
1.primero inicializamos el git bash here en la carpeta del proyecto y escribimos lo siguiente: git branch (nos muestra todas las ramas existentes). le das enter!
2. para crear otra ramas escribimos: git branch name-de-la-nueva-rama (escribes el nombre de la rama que quieres crear sin los: "---", sin espacios!) le das enter!
3. para cambiar el nombre de la rama escribimos: git branch -m nombre-de-la-rama nuevo-nombre (escribes la rama que quieres cambiar de nombre, y a su costado el nuevo nombre) le das enter!
4. si quieres cambiar a la otra rama escribres: git checkout name-de-la-rama (el nombre de la rama) , le das enter!
5. para eliminar una rama escribes lo siguiente: git branch -d name-de-la-rama (el nombre de la rama, ojo no puedes borrar la rama donde estas ubicado ultimamente, para saber te sale el nombre en verde al usar git branch), le das enter!
6. para subir los archivos a la rama creada se escribe los siguiente: git add . (le das enter)
7. luego escribes: git commit -m "commiteando la rama1" (cualquier nombre y si va las comillas)!, le das enter
8. para ver la diferencia de los archivos escribes: git diff name-rama-master name-rama-creada (le das enter)
9. para unificar los archivos de la rama1 a las master osea a la principal, primero debemos estar en la rama master utilizamos (git checkout master)y luego escribimos eso: git merge name-de-la-rama-creada rama-master (le das enter).
10. luego escribimos: git add . le das enter!
11- luego escribimos: git commit -m cambiosMaster (puede ser cualquier mensaje o name)le das enter.
12. ESO SERIA TODO A SABER! GRACIAS!
