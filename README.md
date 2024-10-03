# CLASE 06 - BootCamp

## Repaso Git

# Creo el repositorio 

# Listo elestado de los archivos

'''sh
git status
'''

# Haciendo un commit

1. agrego al áreao de staging, los argchivos que necesito que foemen parte del commit

'''
git ad <nombre-archivo>
git ad <nombre-archivo> <nombre-archivo> <nombre-archivo> 
git add  # agrega todos los archivs que tengo en el working directory (WD)

2. HAGO EL COMMIT

'''
SH
git commit -m "mensaje descriptivo"
'''

'''
git commit (sin el -m se abre el nano para poder escribir un mensaje mucho más largo)
'''
se escribie y con ctrol + O graba el mensaje y con ctrol + X cierro en nano

# Cambiar el editor por nano

'''
    sh
git config --global core.editor nano
git config --global core.editor "code --wait"

# Ver listado de comits que hice en el repo 

'''
    sh
git log # version larga
git log --online # versión corta
'''