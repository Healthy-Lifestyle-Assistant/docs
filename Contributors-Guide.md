# Contributors Guide

[Prerequisites](#prerequisites)  
[Frontend](#frontend)  
[Backend](#backend)  
[Branches Naming](#branches-naming)  

## Prerequisites

1. Install [GitBash](https://git-scm.com/downloads)
1. Install [Node 18](https://nodejs.org/en/download)
1. Install [PostgreSQL 12](https://www.postgresql.org/download/) and [PgAdmin](https://www.pgadmin.org/download/)
1. Install [Intellij IDEA Community](https://www.jetbrains.com/idea/download)
1. Install [VS Code](https://code.visualstudio.com/download)  
1. Install [Google Chrome](https://www.google.com/chrome/)  
1. Install [Slack Desktop](https://slack.com/downloads/windows)  
1. Install [Figma Desktop](https://www.figma.com/downloads/)  

## Frontend

```sh
git clone https://github.com/Healthy-Lifestyle-Assistant/frontend.git
cd path/to/frontend
npm install
npm run serve # localhost:8080
```

## Backend

```sh
git clone https://github.com/Healthy-Lifestyle-Assistant/backend.git
cd path/to/backend
./gradlew spotlessApply
./gralew clean build
```

To run development configuration from Intellij Idea, specify `PROFILE=dev` in the “Environment variables”.

[Top](#contributors-guide)  
