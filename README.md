# MANUAL-GIT

## COMANDOS

- `$ git init` --> Inicializa una carpeta como repositorio git
- `$ git status` --> Muestra es estado de los archivos
  - rojo --> modificados pero no en stage
  - verde --> archivos en stage, listos para agregarlos a commit
- `$ git log` --> Muestra lista de commits del más nuevo hacia atrás
- `$ git add <archivos o carpetas>` --> agrega al stage los archivos o las carpetas
- `$ git commit [-m | -a]` Crea un nuevo commit con un mensaje
  - `-m` no abre editor de texto y pone el mensaje seguido
  - `-a` corre el commando `git add .` antes de hacer commit
- `$ git diff [archivo]` muestra los cambios en los archivos modificados
