# GIT Básico <!-- Se usa # para escribir un título -->

## Instalación <!-- Con dos ## se pone un subtítulo-->

Instalación desde el asistente de Git

## Comandos para credenciales en nuestro equipo

<!--   Se ponen tres ``` para indicar los comandos -->
```

gir config --global user.name "nombreusuario"
git config --global user.email "correousuario"

```

## Crear un repositorio git

```
git init
```

## Comprobar el estado de git

Ver la situación en la que están los cambios desde el último commit

```
git status
```

### Añadir archivos al staging area

Añade todos los cambios pendientes

```
git add-A
```

## Crear un commit

Para guardar un conjunto de cambios y crear un punto de control usamos los commit

```

git commit -m "mensaje del commit"

```

## Deshacer cambios a partir de los commit

2 opciones

```
git reset --soft <código-commit>
```

Con --soft podemos volver a un commit anterior sin deshacer cambios

```
git reset --hard <código-commit>
```

Con --hard podemos volver a un commit anterior deshaciendo todos los cambios