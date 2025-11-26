# P4---Rebase-con-conflicto-en-Git
# Preguntas cortas de comprensión

### 1. ¿Desde qué rama ejecutaste el comando git rebase main? ¿Por qué desde esa y no desde main?

Lo hice desde la rama estilo_texto porque quiero poner los cambios que hice ahí encima de los cambios nuevos que hay en main. No lo hago desde main porque no quiero mover la rama principal, sino actualizar la secundaria.

### 2. ¿Por qué se ha producido el conflicto en notas.txt al hacer el rebase?

Porque tanto main como estilo_texto cambiaron la misma línea del archivo, pero con textos diferentes. Git no sabe cuál dejar, así que me pide que decida.

### 3. ¿Qué habría pasado si hubieras borrado una de las versiones sin fijarte bien en el texto?

Podría haber eliminado información importante o dejado el archivo con errores, lo que afectaría el proyecto.

### 4. ¿En qué se diferencia este caso de un conflicto de merge? (a nivel práctico, en lo que tú has tenido que hacer)

En lo que hice es casi igual: corregir el archivo y decirle a Git que ya está listo. La diferencia es que con rebase los cambios se reordenan para que la historia sea más limpia y sin ramificaciones. 
