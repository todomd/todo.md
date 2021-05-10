# Descripción
Repositorio acerca de cómo hacer una lista de TO-DO en markdown.

# Contenido ES
- [Estructura de los directorios](#Estructura-de-los-directorios)
- [¿Qué es un TODO.md?](#¿qué-es-un-`TODO.md`?)
- [¿Por qué dejar un TODO.md?](#¿por-qué-dejar-un-`TODO.md`?)
- [¿Por qué no usar una herramienta online?](#¿Por-qué-no-usar-una-herramienta-online?)
- [Formato del TODO.md](#formato-del-`TODO.md`)
- [Ejemplos](#ejemplos)
- [Ver también](#ver-también)

## Estructura de los directorios
```txt
.
├── README.md
├── LICENSE
└── Examples_TODO
    └── TODO.md
    └── TODO2.md
    └── TODO3.md
    └── TODO[..].md
```
## ¿Qué es un `TODO.md`?

El `TODO.md` es un formato basado en [GFM - GitHub Flavored Markdown - Task Lists](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown).

`TODO.md` es un archivo que contiene tareas organizadas en múltiples secciones.

Tareas en `TODO.md` pueden ser visualizadas con [Tabla Kanban EN](https://en.wikipedia.org/wiki/Kanban_board) dónde las secciones se convierten en columnas de una tabla.

## ¿Por qué dejar un `TODO.md`?

Para un proyecto, hay muchas fuentes de información como: documentación, foro de problemas, la pág. de Wiki, etc. Por lo cual, es difícil conocer el progreso actual.

Manteniendo un archivo `TODO.md` hace esto más fácil para cualquiera que quiera saber acerca del plan de proyecto y trabajar en lo que se necesite terminar.

## ¿Por qué no usar una herramienta online?

Más a menudo, en un nuevo proyecto se empieza con una lista de tareas para plasmar lo que se debe hacerse rápidamente.

Aunque algunas herramientas online son útiles para manejar grandes proyectos de forma eficiente, usarlos al inicio de un proyecto (en sus primeras etapas) agregará más esfuerzo y gastos generales para un MVP (o [PVM](https://es.wikipedia.org/wiki/Producto_viable_m%C3%ADnimo)) del producto.

### Formato del `TODO.md`

- `TODO.md` puede tener múltiples columnas.
- Cada columna tiene tareas que comienzan con un signo de casilla de verificación `- [ ]` o solo un guión `- `
- El nombre de columna de las tareas completas debe contener `✓` o `[x]`.
- Hay "2 espacios" al final de cada título de la tarea que sirven como salto de líneas en las pág. de Github.
- Tags, menciones, estimaciones, fecha, ticket id, etc. se puede ingresar al final del título de la tarea.
- Una tarea con 2 espacios de indexación en el título es una sub-tarea o descripción.

```md
# Nombre del proyecto
Descripción del proyecto

### Nombre de la columna
- [ ] Título de la tarea ~3d #tipo @nombre yyyy-mm-dd
  - [ ] Sub-tarea o descripción

### Columna completada ✓
- [x] Título de la tarea completada
```

- Las casillas de verificación son usadas como se describe en [GFM - GitHub Flavored Markdown - Task Lists](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown) pero esto es opcional.
- Una lista de tareas sin casilla de verificación se ve como esto:

```md
## Nombre de la columna
- Título de la tarea ~3d #tipo @nombre yyyy-mm-dd
  - Sub-tarea o descripción

### Columna completada ✓
- Título de la tarea completada
```
## Extra: Tareas rechazadas
- [-] Ejemplo de tarea rechazada
## Ejemplos
- [Ejemplo 1 de TODO.md](TODO_examples/TODO.md)
- [Ejemplo 2 de TODO.md](TODO_examples/TODO2.md)

## Ver también
- [Extensión de Vscode: Kanban Board](https://marketplace.visualstudio.com/items?itemName=coddx.coddx-alpha&ssr=false)
- [Extensión de Vscode: Kanban](https://marketplace.visualstudio.com/items?itemName=mkloubert.vscode-kanban)
- [README EN](README.md)