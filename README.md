# Description
[EN] Repositorie about how to do TO-DO list on markdown.

# Content EN
- [Structure of directories](#Structure-of-directories)
- [What is TODO.md?](#What-is-`TODO.md`?)
- [Why keep a TODO.md?](#Why-keep-a-`TODO.md`?)
- [Why not using online management tools?](#Why-not-using-online-management-tools?)
- [TODO.md format](#`TODO.md`-format)
- [Examples](#examples)
- [See also](#See-also)

# Contenido ES
- [Estructura de los directorios](#Estructura-de-los-directorios)
- [¿Qué es un TODO.md?](#¿qué-es-un-`TODO.md`?)
- [¿Por qué dejar un TODO.md?](#¿por-qué-dejar-un-`TODO.md`?)
- [¿Por qué no usar una herramienta online?](#¿Por-qué-no-usar-una-herramienta-online?)
- [Formato del TODO.md](#formato-del-`TODO.md`)
- [Ejemplos](#ejemplos)
- [Ver también](#ver-también)
----
## Structure of directories
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

## What is `TODO.md`?

The `TODO.md` format is based on [GFM - GitHub Flavored Markdown - Task Lists](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown).

`TODO.md` is a file that contains tasks organized in multiple sections.

Tasks in `TODO.md` can be visualized using [Kanban Board](https://en.wikipedia.org/wiki/Kanban_board) where sections become columns on the board.

## Why keep a `TODO.md`?

For a project, there any many sources of information like Documentation, Issue forum, Wiki pages, etc. It is hard to find out about the current progress.

Keeping a `TODO.md` file makes it easier for anyone wants to know about the project's plans and work needs to be done.

## Why not using online management tools?

Most often, a new project starts with a list of tasks to outline what needs to be done quickly.

Although some online tools are useful to manage large projects efficiently, using them in early stages will add more effort and overhead for an MVP Product.

### `TODO.md` format

- `TODO.md` can have multiple columns.
- Each column has tasks that start with a checkbox sign `- [ ]` or just a hyphen `- `
- Completed column name must contain `✓` or `[x]`.
- There are "2 spaces" at the end of every task title to serve as line breaks on Github pages.
- Tags, mentions, estimate, date time, ticket id, etc. can be entered at the end of the task title.
- A task with 2 space indentation in the title is a sub-task or description.

```md
# Project Name
Project Description

### Column Name
- [ ] Task title ~3d #type @name yyyy-mm-dd
  - [ ] Sub-task or description

### Completed Column ✓
- [x] Completed task title
```

- Checkboxes are used as described in [GFM - GitHub Flavored Markdown - Task Lists](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown) but they are optional.
- A task list without checkboxes look like this:

```md
## Column Name
- Task title ~3d #type @name yyyy-mm-dd
  - Sub-task or description

### Completed Column ✓
- Completed task title
```
## Extra: Declined task
- [-] Example to declined task
## Examples
- [Example 1 of TODO.md](Examples_TODO/TODO.md)
- [Example 2 of TODO.md](Examples_TODO/TODO2.md)

## See also
- [Vscode Kanban Board Extension](https://marketplace.visualstudio.com/items?itemName=coddx.coddx-alpha&ssr=false)
- [Vscode Kanban Extension](https://marketplace.visualstudio.com/items?itemName=mkloubert.vscode-kanban)

---
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

El `TODO.md` format is based on [GFM - GitHub Flavored Markdown - Task Lists](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown).

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

- Checkboxes are used as described in [GFM - GitHub Flavored Markdown - Task Lists](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown) but they are optional.
- A task list without checkboxes look like this:

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
- [Ejemplo 1 de TODO.md](Examples_TODO/TODO.md)
- [Ejemplo 2 de TODO.md](Examples_TODO/TODO2.md)

## Ver también
- [Extensión de Vscode: Kanban Board](https://marketplace.visualstudio.com/items?itemName=coddx.coddx-alpha&ssr=false)
- [Extensión de Vscode: Kanban](https://marketplace.visualstudio.com/items?itemName=mkloubert.vscode-kanban)