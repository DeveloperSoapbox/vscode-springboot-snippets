# Spring Boot Snippets for VS Code

This extension for Visual Studio Code adds useful snippets for Spring Boot.  These are especially useful for creating REST apis, and configuring database connection properties.

## Usage

For a detailed walkthrough, please use this youtube video - https://www.youtube.com/watch?v=qI7hTw8aMaU

Type part of a snippet, press `enter`, and the snippet unfolds.

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (macOS) to activate snippets from within the editor.

### Java Snippets

| Snippet                      | Purpose                                                              |
| ---------------------------- | -------------------------------------------------------------------- |
| `spring-crudctrl`            | Spring controller with CRUD actions implemented                      |
| `spring-crudrepo`            | Spring Data JPA CRUD repository with REST api annotation             |
| `spring-entity`              | JPA entity with ID field                                             |
| `spring-ctrl-getall`         | Controller GET action for collection                                 |
| `spring-ctrl-getone`         | Controller GET action for single item                                |
| `spring-ctrl-post`           | Controller POST action                                               |
| `spring-ctrl-put`            | Controller PUT action                                                |
| `spring-ctrl-delete`         | Controller DELETE action                                             |

### application.properties / application.yaml Snippets

| Snippet                      | Purpose                                                              |
| ---------------------------- | -------------------------------------------------------------------- |
| `spring-sqlite`              | SQLite database jdbc url and properties                              |
| `spring-sqlserver`           | SQL Server database jdbc url and properties                          |
| `spring-oracle`              | Oracle database jdbc url and properties                              |
| `spring-postgresql`          | PostgreSQL database jdbc url and properties                          |
| `spring-mysql`               | MySQL database jdbc url and properties                               |
| `spring-h2`                  | H2 database jdbc url and properties                                  |

## Installation

1. Install Visual Studio Code 1.44.0 or higher
1. Launch Code
1. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
1. Select `Install Extension`
1. Choose the extension
1. Reload Visual Studio Code

