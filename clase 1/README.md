# Clase 01 - GIT

## Archivo Marckdown

## Como Saber si tengo Git instalado 

```sh
git --version
```
## Comando de consola 

### limpio la consola
 ```sh
clear
```
### iniciar git
```sh
git init
```

### listar archivos en consola
```sh
ls -la
```

### como entrar en una carpeta en consola
```sh
cd <directorio>
```

### como saber donde estoy
```sh
pwd
```

### eliminar directorio
```sh
rm -rf <directorio>
```

### retroceder directorio
```sh
..
```

### como saber donde estoy
```sh
pwd
```
### crear carpeta
```sh
mkdir <nombredecarpeta>
```
### crear archivo html
```sh
touch .index
```

### configuracion inicial de GIT
#### Configuracion de Usuario
```sh
git config user.name "facu"
```

#### Configuracion de mail
```sh
 git config user.email "facuzylinski@gmail.com"
```

#### como saber si hice bien lo anterior
```sh
git config --get-regexp user
```

#### vincular archivo al git
```sh
git add <archivo>
```
#### vincular todos los archivos al git
```sh
git add .
```

#### verificar si se vinculo
```sh
git status
```
#### realizar un commit
```sh
git commit -m "mensaje"
```

#### forma abreviada de add y commit
```sh
git commit -am "mensaje"
```
#### verificar si se realizo el commit
```sh
git log
```
##### ver log en forma resumida
```sh
git log --oneline
```
##### ver de que fecha, antes de que fecha, despues de que fecha y los ultimos commit segun la cantidad q pongas (-1,-2,-3,-n)
```sh
git log --since"2021-12-2020"
git log --after"2021-12-2020"
git log --before"2021-12-2020"
git log -1
```

#### vincular con repocitorio git
```sh
git remote add origin https://github.com/facuzyli/git-repo-it.git
```

#### vincular con repocitorio git
```sh
git push -u origin main
```
#### paga guardar una vez vinculado
```sh
git push 
```
#### vincular con repocitorio git
```sh
git push -u origin main
```
#### eliminiar repocitorio
```sh
git remote rm origin
```
#### ver repositorios
```sh
git push remote -v
```