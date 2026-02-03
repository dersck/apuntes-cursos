# Comandos Básicos y Flujo de Trabajo

Comandos para poder inicializar proyectos, solicitar ayuda sobre comandos y establecer parámetros iniciales para identificación

## Ver el status actual de los archivos del repositorio
```bash
git status
```

## Ver el status actual de los archivos del repositorio
```bash
git status
```

## Mandar cambios al staging area
### Añadir TODOS los archivos que han tenido cambios
```bash
git add .
```

### Añadir archivos en específico
```bash
git add <file>
```

```md
> 📂 PROYECTO --> $git add --> 📂 STAGING AREA --> $git commit --> 📂 .GIT
```

## Regresar archivos del staging area al proyecto
```bash
git restore --staged <file>
```

## Generar un snapshot
```bash
git commit -m "Mensaje del snapshot del cambio al <file>"
```

## Bitácora de cambios
```bash
git log
```