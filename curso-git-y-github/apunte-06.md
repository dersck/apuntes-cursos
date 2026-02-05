# Conflictos de Ramas en Git
Uso del comando Git Merge.

> Cuando se colabora con equipos, suele haber conflictos al 2 personas modificar el mismo archivo.

## Unificar ramas
Estando en la rama principal
```bash
git merge <rama-secundaria>
```

Ejemplo:
```bash
git merge developer
```

```md
> Si hay conflictos, depurar los posibles inconvenientes, guardar el archivo e intentar de nuevo el merge
```

> [!IMPORTANT]
>
> Después de hacer merge, la rama pierde el sentido de su existencia. Así que hay que eliminarla

```bash
git branch -d <rama-secundaria>
```
