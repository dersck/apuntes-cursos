# Manejo de Historial y Corrección de Errores
Uso de los comandos Git Reset vs Git Revert

```md
> Para el uso de estos comandos, necesitamos obtener el Hash de los commits a donde queremos volver o corregir
```

## Generar un commit notificando cambios 

```bash
git revert
```
Crea un nuevo commit que "revierte" los cambios realizados por un commit específico

```md
> Ojo: usarlo cuando ya mandaste al repo
```

Ejemplo:
```bash
git revert [hash]
```

```md
> Modifica el mensaje del commit y guarda cambios (en Vim, ESC + :wq)
```

## Volver a un commit anterior

```bash
git reset
```
Te devuelve a un commit anterior, eliminando los cambios en el historial como si nunca hubieran ocurrido

```md
> Ojo: usarlo cuando estás en local
```

Ejemplo:
```bash
git reset --hard [hash]
```

```md
> --soft elimina los archivos
> --mix regresar los commits
> --hard deshace todos los cambios
```