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

#### verificar si se realizo el commit
```sh
git log
```

