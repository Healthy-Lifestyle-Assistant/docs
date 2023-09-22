# Developers Guide

## Requirements for Local Machines

- JDK 17
- Maven >=3
- Node 18
- Docker
- PostgreSQL 12

## How to Run Application

### Frontend

```sh
cd /path/to/HLA/
git clone https://github.com/Healthy-Lifestyle-Assistant/frontend.git

cd frontend/
npm install

npm run serve
```

### Backend

```sh
cd /path/to/HLA/
git clone https://github.com/Healthy-Lifestyle-Assistant/backend.git

# Open project in Intellij IDEA
# Wait until dependencies intalled
# Run/Debug App.main()
```

## How to Run Backend Tests Before Commit

```sh
# Open project in Intellij IDEA
# Gradle > verification > spotlessApply

cd /path/to/backend/
./gradlew clean build
```

## Guides

- Create new issue for each task
- Create new branch for each issue. Before that checkout to main branch and merge changes to it.
- Run tests on local machine before commit
- In commit description paste issue title and number
- Create draft pull request if still working on it
- Create pull request and request code review 

### Branches Naming

```txt
feature/123-some-description
fix/123-some-description
build/123-some-description
cicd/123-some-description
docs/123-some-description
```
