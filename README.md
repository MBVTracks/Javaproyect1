1. - Creamos un tag con el comando git tag + el nombre de la versión de nuestro proyecto, por ejemplo v0.1 y -m para añadir un mensaje:

	
2. - Con git push, subimos esa etiqueta al repositorio remoto:

	

	
	




- a continuacion con git log, podemos ver las ‘versiones’ anteriores que hicimos a nuestro proyecto.

2. -  con git checkout podemos movernos por las distintas versiones, en este caso, volvemos a la primera versión del código (a16affc):

	
3. - Hacemos un cambio en el código:

	


4. - Intentamos hacer commit:
	

- Nos sale un mensaje de que nuestro HEAD se encuentra ‘desasociado’, al apuntar a una confirmación anterior a la rama master. Si volvemos a la rama master nos dice que tenemos cambios pendientes para realizar en otra confirmación y que para ello creemos una rama en el repositorio. Para poder revertir los cambios en esa confirmación utilizamos git resert o git revert.

5. - Por último, recuperamos la versión tag de CarpetaCasa en CarpetaInstituto, para ello vamos a carpeta instituto y vemos como aquí no hay ninguna etiqueta:

		
- para recuperar ese tag, utilizamos el comando git fetch –tag/s:

