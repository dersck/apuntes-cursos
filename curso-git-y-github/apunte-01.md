# Configuración y Comandos Básicos

Comandos para poder inicializar proyectos, solicitar ayuda sobre comandos y establecer parámetros iniciales para identificación

## Verificar instalación y versión de Git

```bash
git --version
```

## Inicialización de proyectos
### En la ruta base del proyecto

```bash
git init
```

## Ayuda sobre comandos

```bash
git --help
git [comando] --help
```

## Configuración del entorno
### Configuración del entorno global
Esta configuración que se configure, será para todos los proyectos

```bash
git config --global user.name "Joel Rosas"
git config --global user.email "bryandrsk95@gmail.com"
```

### Configuración del entorno local
Esta configuración que se configure, será local, para ciertos repositorios

```bash
git config user.name "Joel Rosas"
git config user.email "bryandrsk95@gmail.com"
```