# tallerGit
Documentación e info para el taller de Git de 42 Málaga Fundación Telefónica

Historial de commits:
	git log --all --full-history
	
Todos los archivos de ese commit:
	git ls-tree --name-only -r <commit_hash>

Si un archivo existe en un commit:
	git show <commit_hash>:"<file_name>"

Traerse el archivo al "presente":
	git show <commit_hash>:"<file_name>" > "<new_file_name>"
