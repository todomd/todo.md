# Description
Repository about how to create a TODO list using markdown.

# Content EN
- [What is TODO.md?](#What-is-`TODO.md`?)
- [Why keep a TODO.md?](#Why-keep-a-`TODO.md`?)
- [Why are we not using online management tools?](#Why-are-we-not-using-online-management-tools?)
- [TODO.md format](#`TODO.md`-format)
- [Examples](#examples)
- [See also](#See-also)

----

## What is `TODO.md`?

The `TODO.md` format is based on [GFM - GitHub Flavored Markdown - Task Lists](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown).

- TODO.md is a file that contains tasks organized in multiple sections.
- Tasks in TODO.md can be visualized using [Kanban Board](https://en.wikipedia.org/wiki/Kanban_board) where sections become columns on the board.
- Inspired by [Keep a Changelog](https://github.com/olivierlacan/keep-a-changelog)

`TODO.md` is a file that contains tasks organized in multiple sections.

Tasks in `TODO.md` can be visualized using [Kanban Board](https://en.wikipedia.org/wiki/Kanban_board) where sections become columns on the board.

## Why keep a `TODO.md`?

For a project, there any many sources of information like Documentation, Issue forum, Wiki pages, etc. It is hard to find out about the current progress.

Keeping a `TODO.md` file makes it easier for anyone who wants to know about the project's plans and work that needs to be done.

## Why are we not using online management tools?

Often times, a new project starts with a list of tasks to outline what needs to be done quickly.

Although some online tools are useful to manage larger projects efficiently, using them in the early stages will add more effort and overhead for small projects.

A few other reasons like: portable plain text format, same project directory, offline working, privacy, versioning (using git), minimalist tool, etc.

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
- [README_ES](README_ES.md)
