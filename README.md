1. - Creamos un tag con el comando git tag + el nombre de la versi�n de nuestro proyecto, por ejemplo v0.1 y -m para a�adir un mensaje:

	
2. - Con git push, subimos esa etiqueta al repositorio remoto:

	

	
	




- a continuacion con git log, podemos ver las �versiones� anteriores que hicimos a nuestro proyecto.

2. -  con git checkout podemos movernos por las distintas versiones, en este caso, volvemos a la primera versi�n del c�digo (a16affc):

	
3. - Hacemos un cambio en el c�digo:

	


4. - Intentamos hacer commit:
	

- Nos sale un mensaje de que nuestro HEAD se encuentra �desasociado�, al apuntar a una confirmaci�n anterior a la rama master. Si volvemos a la rama master nos dice que tenemos cambios pendientes para realizar en otra confirmaci�n y que para ello creemos una rama en el repositorio. Para poder revertir los cambios en esa confirmaci�n utilizamos git resert o git revert.

5. - Por �ltimo, recuperamos la versi�n tag de CarpetaCasa en CarpetaInstituto, para ello vamos a carpeta instituto y vemos como aqu� no hay ninguna etiqueta:

		
- para recuperar ese tag, utilizamos el comando git fetch �tag/s:

