
**Cuando trabajamos con el consola y usamos alguna bandera con el __(--)__ significa que lo prosigue una palabra completa**

```git
git --version
```

** Y cuando usamos alguna bandera con el __(-)__ significa que lo prosigue es una abreviatura**

```git
git -am
```


# Comandos de GIT

 -  Indica la versión de git que tenemos instalada
```git
git --version
```

- Nos permite realizar configuraciones globales en nuestro equipo.
```git
# Para obtener ayuda sobre el comando

git --help config

# Para indicar el nombre de usuario que aparecera en los commits que realicemos

git config --global user.name ["nombre"]

# Para indicar el nombre de usuario que aparecera en los commits que realicemos

git config --global user.email ["email"]

# Para observar los cambios realizados en las configuraciones

git config --global -e 
```

- Nos muestra la ayuda de GIT, información de los comandos permitidos
```git
git help
```

- Nos muestra la ayuda de GIT, con la información que podriamos encontrar en la web sobre como funciona y que banderas acepta este comando.
```git
git help [command]
git help commit 
```

- Nos inicializa un repositorio en local
```git
git init
```

- Nos da la información sobre los commits, el branch donde estamos posicionados. y en primera instancia nos sirve para vizualizar archivos modificados o archivos que git aún no les esta haciendo seguimiento con archivos o carpetas nuevas.
```git
git status
```

- Nos añade los archivos a un stage, previo a hacer un commit.
```git
# Agrega el archivo o archivos de un path al stage

git add [file/path]

# Agrega todo lo que no se a modificado o lo nuevo al stage

git add .

```

- Nos permite sacar del stage algún archivo o directorio que se alla cargado en el stage y no queramos que se guarde en el commit
```git
# Sacamos un archivo o directorio en concreto del stage
git reset [fileName/path]

# Sacamos todo lo que habia en el stage
git reset [fileName/path]
```

- Nos permite guardar con un nombre todo lo que habia en el stage, en un punto del tiempo.
```git
git commit -m "mensaje del commit"
```


- Para recuperar todo el repositorio a como estaba en el commit anterior
```git
git checkout -- .
```


```git
git 
```
```git
git 
```
```git
git 
```








