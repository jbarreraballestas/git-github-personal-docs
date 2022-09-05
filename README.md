# Documentación personal sobre el uso de git y github

## Ver las opciones para configuración de git

```
git config
```
## Ver como está configurado git

```
git config --list
```

## Configurar el nombre del usuario global en git

```
git config --global user.name "Nombre de Usuario"
```

## Configurar el correo del usuario global en git

```
git config --global user.name "usuario@correo.com"
```

## Crear un repositorio de git en la carpeta actual

```
git init
```

## Estado de los archivos del proyecto

```
git status
```

## Agregar archivos al rastreo de git

```
git add ARCHIVO.md
```

## Agregar comentarios sobre los cambios realizados

```
git commit -m "Se creó el archivo ARCHIVO.md"
```

## Elimina archivos del staging de la cache en memoria

```
git rm --cached ARCHIVO.md
```

## Mostrar el historial de commits y cambios en un archivo

```
git show ARCHIVO.md
```

## Mostrar cambios entre dos commits, mas antiguo seguido mas reciente

```
git diff hash_anterior hash_reciente
```

## Ver el historial de cambios en el proyecto

```
git log
```

## Ver los archivos o el proyecto en una version anterior

```
git checkout hash_anterior ARCHIVO.md
```

## Ver los archivos o el proyecto en la version actual despues de haber hecho un checkout

```
git checkout main ARCHIVO.md
```

## Agregar commit de los archivos previamente agregados

```
git commit -am "Se realizarón cambios sobre x, y, z"
```

