# Onboarding

For questions and support please refer to the “Onboarding” channel in the Slack chat.

- [ ] [Work with Documentation](#work-with-documentation)
- [ ] [Work with Codebase](#work-with-codebase)
- [ ] [Understand Kanban Board](#understand-kanban-board)
- [ ] [Fit Requirements for Your Local Machine](#fit-requirements-for-your-local-machine)
- [ ] [Clone Repositories and Run Code](#clone-repositories-and-run-code)
- [ ] [Test Application](#test-application)


## Work with Documentation

- [ ] Read [Project’s description](https://github.com/Healthy-Lifestyle-Assistant/docs/blob/main/README.md)
- [ ] Read [User stories](https://github.com/Healthy-Lifestyle-Assistant/docs/tree/main/User-Stories)
- [ ] Overview [Domain area diagram](https://github.com/Healthy-Lifestyle-Assistant/docs/blob/main/Diagrams/Domain-Diagram.md)
- [ ] Overview [Database diagram](https://github.com/Healthy-Lifestyle-Assistant/docs/blob/main/Diagrams/Database-Diagram.md)
- [ ] Overview [Deploy diagram](https://github.com/Healthy-Lifestyle-Assistant/docs/blob/main/Diagrams/Deploy-Diagram.md)
- [ ] Read [REST API endpoints](https://github.com/Healthy-Lifestyle-Assistant/docs/tree/main/REST-API)

## Work with Codebase

Navigate through repositories on GitHub. Don’t clone them at this stage.

### Backend

- [ ] Go to [Backend repository](https://github.com/Healthy-Lifestyle-Assistant/backend) 
- [ ] Discover dependencies of the project in the `build.gradle` file.
- [ ] Discover project structure in the `src` directory: `main` directory for source code, and `test` directory for tests.
- [ ] Discover a typical structure of the modules like `users` and `workout` in the `main` directory. These modules are dedicated to the business logic related to the users and workouts correspondingly. Such modules contain `model` and `repository` directories to deal with ORM and database, `service` directory for business logic, `dto` (means Data transfer objects) for transforming model data to other forms, `controller` for routing HTTP requests.
- [ ] Discover common modules like `security`, `exception`, `config`, `validation`.
- [ ] Discover `resources` directory and its configuration files.
- [ ] Discover `test` directory. It has a similar structure to `main` directory and contains unit and end-to-end tests.
- [ ] Discover `.github` directory. It contains instructions for GitHub Actions. When pull request is created, then this file starts automatically by GitHub, and performs a build command to ensure that there are no errors. After successful build a pull request can be merged.
- [ ] Discover `Actions` tab where a history of GitHub Actions is stored.
- [ ] Discover `Issues` tab, it contains a list of the tasks to do.

### Frontend

- [ ] Go to [Frontend repository](https://github.com/Healthy-Lifestyle-Assistant/frontend)
- [ ] Discover dependencies of the project in the `package.json` file.
- [ ] Discover project structure in the `src` directory: `views` directory contains full HTML page, `components` should contain components that are building blocks for HTML pages, file `store.js` manages state of the application, file `router/index.js` is responsible for routing between pages.
- [ ] Discover `.github` directory. It contains instructions for GitHub Actions. When pull request is created, then this file starts automatically by GitHub, and performs a build command to ensure that there are no errors. After successful build a pull request can be merged.
- [ ] Discover `Actions` tab where a history of GitHub Actions is stored.
- [ ] Discover `Issues` tab, it contains a list of the tasks to do.

[Top](#onboarding)


## Understand Kanban Board
- [ ] Go to [Kanban Board](https://github.com/orgs/Healthy-Lifestyle-Assistant/projects/1)
- [ ] Discover Board’s structure: Todo, In-progress, On-review, Done.

[Top](#onboarding)


## Fit Requirements for Your Local Machine

- [ ] Install [GitBash](https://git-scm.com/downloads)
- [ ] Install [Docker Desktop](https://docs.docker.com/desktop/install/windows-install/)
- [ ] Install [JDK 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html) 
- [ ] Install [Gradle 8](https://docs.gradle.org/current/userguide/installation.html) 
- [ ] Install [Node 18](https://nodejs.org/en/download)
- [ ] Install [PostgreSQL 12](https://www.postgresql.org/download/) and [PgAdmin](https://www.pgadmin.org/download/)
- [ ] Install [Postman](https://www.postman.com/downloads/)
- [ ] Install [Intellij IDEA Community](https://www.jetbrains.com/idea/download)
- [ ] Install [VS Code](https://code.visualstudio.com/download)
- [ ] Install [Google Chrome](https://www.google.com/chrome/)

[Top](#onboarding)


## Clone Repositories and Run Code

- [ ] Create a separate directory on your machine like `C:/HLA/` or `C:/Projects/HLA/`.

### Frontend

- [ ] Navigate to the `HLA` directory, open GitBash from this directory.
- [ ] In GitBash type `git clone https://github.com/Healthy-Lifestyle-Assistant/frontend.git`
- [ ] Ensure that the `frontend` directory appears.
- [ ] In VS Code, select `Open folder` and choose `HLA/frontend`.
- [ ] Ensure your are on the `main` branch (left bottom corner).
- [ ] In a console and type `npm install`.
- [ ] In a console and type `npm run serve`, ensure there are no errors.
- [ ] In Chrome go to `localhost:8080`.
- [ ] Ensure that application works.

### Backend

- [ ] Navigate to the `HLA` directory, open GitBash from this directory.
- [ ] In GitBash type `git clone https://github.com/Healthy-Lifestyle-Assistant/backend.git`
- [ ] Ensure that the `backend` directory appears.
- [ ] In Intellij IDEA select `Open Project` and add `HLA/backend`. If the IDE informs that JDK is not selected, select JDK 17.
- [ ] Navigate to the App class in the `main` directory.
- [ ] Press on a green run button and select `Modify Run Configuration`.

![App Class](./img/app-class.JPG)

- [ ] In the section “Environment variables” put “PROFILE=dev”, apply changes.

![Run Configuration](./img/run-configuration.JPG)

- [ ] Run “App” configuration, ensure there are no errors.

[Top](#onboarding)


## Test Application

### Manual Testing

- [ ] Run both front and back.
- [ ] Navigate through the application.
- [ ] Singup and login with the created user.

### Backend Testing with Postman

- [ ] Run backend.
- [ ] In Postman, test any unprotected URL like “localhost:8085/api/v1/exercises/default”.

![Postman](./img/postman.JPG)

[Top](#onboarding)
