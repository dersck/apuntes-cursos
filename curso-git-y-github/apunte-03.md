# Gestión de ramas en Git
Comandos para la creación, fusión y eliminación eficiente

## Verificar en qué rama me encuentro
```bash
git branch
```

## Crear y moverme a una rama
```bash
git switch -c nombre_rama
```
## Hacer merge a main
```md
> "Cuando trabajas en una nueva rama, realizas commits y cuando hacer todo lo necesario, hay que devolver los cambios a la rama principal"
```
```bash
git switch main
```
Estando en la rama principal:
```bash
git merge rama_secundaria
```

## Eliminar ramas
```md
> "Cuando haces merge, la rama que creaste, ya no tiene sentido"
```
```bash
git branch -D rama_secundaria
```