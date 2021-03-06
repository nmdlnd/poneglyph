# Documentation for frontend

> Docs description here.

## Table of Contents

- [Documentation for frontend](#documentation-for-frontend)
  - [Table of Contents](#table-of-contents)
  - [π¦ Repostitoriesπ](#-repostitories)
  - [βοΈ Spesificationπ](#οΈ-spesification)
    - [Frontpages](#frontpages)
    - [Backoffice](#backoffice)
  - [π§± Tech Stack π](#-tech-stack-)
    - [Core](#core)
    - [Styling](#styling)
    - [Utils](#utils)
  - [ποΈ Application Structure π](#οΈ-application-structure-)
  - [π Getting Started π](#-getting-started-)
  - [π€ Authors π](#-authors-)
  - [π€ Contribution π](#-contribution-)
  - [π License π](#-license-)

## π¦ Repostitories[π](#table-of-contents)

Related repositories:
- [`main`](hhttps://github.com/adeka-factory/poneglyph): Main documentation and design
- [`frontend-ui`](https://github.com/adeka-factory/poneglyph/spec/../../../../../web-ui.md): Frontend application
- [`backend-api`](https://github.com/adeka-factory/poneglyph/spec/../../../web-api.md): Backend application

## βοΈ Spesification[π](#table-of-contents)

Enviroment have a two options : 
 - `development` pages in progress
 - `done` pages already done

### Frontpages

| Path           | Pages / Component | Description         | Environment   |
| -------------- | ----------------- | ------------------- | ------------- |
| `/`            | `PageHome`        | Home                | -             |
| `/about`       | `PageAbout`       | About               | -             |
| `/users`       | `PageUsers`       | All users           | -             |
| `/:slug`       | `PageUserProfile` | Single user profile | -             |
| `/items`       | `PageItems`       | All items           | -             |
| `/items/:slug` | `PageItem`        | Single item detail  | -             |
| `/register`    | `PageRegister`    | Register new user   | -             |
| `/login`       | `PageLogin`       | Login user          | -             |
| `/logout`      | `PageLogout`      | Logout user         | -             |
| `/settings`    | `PageSettings`    | User settings       | `done`             |
| `/404`         | `PageNotFound`    | Not found           | `development` |
| `/upload`      | `PageUpload`      | Upload mode         | `development` |
| `/debug`       | `PageDebug`       | Debug mode          | `development` |

### Backoffice

| Path                      | Pages / Component | Description       | Environment |
| ------------------------- | ------------------| ----------------- | ----------- |
| `/`                       | `PageHome`        | Home              | -           |
| `/404`                    | `PageNotFound`    | Not found         | -           |
| `admin/users`             | `PageUsers`       | All users         | -           |
| `admin/users/:username`   | `PageUser`        | Single user info  | -           |
| `admin/items`             | `PageItems`       | All items         | -           |
| `admin/items/:slug`       | `PageItem`        | Single item info  | -           |
| `admin/images`            | `PageImages`      | All images        | -           |
| `admin/images/:slug`      | `PageImage`       | Single image info | -           |
| `admin/login`             | `PageLogin`       | Login user        | -           |
| `admin/logout`            | `PageLogout`      | Logout user       | -           |


## π§± Tech Stack [π](#table-of-contents)

All the frontend/web dependencies sorted by priority:

### Core

- [**Git**]() β Distributed version control system
  - [**GitHub**]() β Provides hosting for software development and version control using Git.
- [**JavaScript**]() β The primary programming language
  - [**Node.js**]() β JavaScript runtime environment and package manager.
  - [**Yarn**]() β JavaScript runtime environment and package manager.
- [**REST API**]() β REpresentational State Transfer, architectural style for distributed hypermedia systems.
- [**React**]() β JavaScript library for building user interfaces
  - [**Webpack**]() β JavaScript module bundler.

### Styling

- [**CSS IN JS**]() β For make reusable styling in react components.
  - [**Emotion**]() β Provides hosting for software development
  - [**Styled components**]() β Provides hosting for software development.
  - [**react-responsive**]() β Provides hosting for software development.

### Utils
- [**Prettier**]() β For make reusable styling in react components.
- [**Husky**]() β For make reusable styling in react components.
- [**webpack-analyze**]() β For make reusable styling in react components.

## ποΈ Application Structure [π](#table-of-contents)

WIP

## π Getting Started [π](#table-of-contents)

WIP

## π€ Authors [π](#table-of-contents)

WIP

## π€ Contribution [π](#table-of-contents)

WIP

## π License [π](#table-of-contents)