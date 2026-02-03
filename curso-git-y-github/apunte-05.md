# Gestión de Versiones y Revisión
Uso de los comandos Git Tag y Git Switch.

```md
> Un tag es como una etiqueta que puedes aplicar a un commit para identificarlo fácilmente en el futuro
```

## Colocar Tags al último commit

```bash
git tag -a <tag> -m "Mensaje"
```

Ejemplo:
```bash
git tag -a v1.0 -m "Primer versión estable"
```

## Ver descripción del tag
```bash
git show -a <tag>
```

Ejemplo:
```bash
git show -a v1.0 
```

## Eliminar tag
```bash
git tag -d <tag>
```

Ejemplo:
```bash
git tag -d v1.0 
```

## Revisión de un punto (commit) en particular (solo mirar) 
```bash
git switch --detach <hash>
```

Cuando termines de hacer pruebas, regresa a main
```bash
git switch main
```