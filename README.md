# ShareDocuments
Documents

--Primero Descargar una copia del Master
git clone "la url del proyecto"
--dentro de la carpeta que se descarga los archivos del proyecto
git remote -v 
--nos mostrara dos urls y eligimos el mismo del proyecto de url
git remote add upstream "la url del proyecto"
--Comprobamos
git remote -v 
--Creamos una rama o branch
git checkout -b "nombre del branch"
--Para cambiar de branch si en caso pidan pero normalmente no pasa
git checkout "nombre del branch"
--Para ver el listado de los branch que hemos creado
git branch -a
--Para ver en que branch estamos
git status
--Agregar los cambios al archivo que modificamos
git add Nombre del Archivo mas su extension
--Si en caso nos hemos confundido y queremos desaser cambios
git reset HEAD nombre del archivo mas su extension
--Agregar un comentario de lo que estamos haciendo
git commit -a --m "Comentario de lo que has hecho"
--Subir el cambio en el repositorio
git push origin  transaction
