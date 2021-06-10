# Few coding conventions to follow

## File structure

**React**

- place each page on its own directory
- place all the components at the roots level components and group if required
  **_example_**

```bash
src
    |--assets
    |--components
    |--layouts
    |--routes
    |--utils
    |--pages
    |   |--HomePage
    |   |   |--HomePage.js
    |   |--WorkPage
    |   |   |--WorkPage.js
    |   |   |--index.js
    | ...
```

**SLIM**

**_File structure followed in superadmin backend_**

```bash
    |--app
    |   |--dependencies.php
    |   |--middleware.php
    |   |--roues.php
    |   |...
    |--logs
    |--public
    |   |--.htaccess
    |   |--index.php
    |--src
    |   |--Application
    |   |--Domain
    |   |--Auth // all auth related actions/models
    |   |--Owera
    |   |   |--Staffs
    |   |   |   |--Models
    |   |   |   |   |--Staff.php
    |   |   |   |   |--Staff.php
    |   |   |   |--Actions
    |   |   |   |   |--StaffListAction.php
    |   |   |   |   |--StaffDetailAction.php
```

## Indentation/Whitespaces

- use 4 space indentation

## Comments

- aim write declarative code i.e. your code be as explanatory as possible without having the need to write comments
- write comments only absolutely necessary

Learn more on comments [Here](https://youtu.be/2a_ytyt9sf8)

## Naming Conventions

- Use `PascalCase` for class names
- use `camelCase` for property/variables Names(Javascript)

Learn more on function naming conventions, arguments on functions, etc [Here](https://youtu.be/7EmboKQH8lM)

## Formatting

Example of .editorconfig for formatting conventions

```bash
# editorconfig.org
root = true
[*]
indent_style = space
indent_size = 4
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true
quote_type = single
```

## Best practises for REST Api architecture

Follow Stack overflows [article](https://stackoverflow.blog/2020/03/02/best-practices-for-rest-api-design/)

## Version Control branching workflow

Follow [this](https://nvie.com/posts/a-successful-git-branching-model/) workflow

## Git commits conventions

Follow conventionalcommits for writting better commit messages. [More](https://www.conventionalcommits.org/en/v1.0.0/#specification)
