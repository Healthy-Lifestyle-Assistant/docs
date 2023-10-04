# Healthy Lifestyle Assistant

A healthy lifestyle is a way of living that lowers the risk of being seriously ill or dying early. Not all diseases are preventable, but a large portion of deaths, particularly those from coronary heart disease and lung cancer, can be avoided. Scientific studies have identified certain types of behavior that contribute to the development of noncommunicable diseases and early death. Health is not just about avoiding disease. It’s also about physical, mental and social wellbeing. When a healthy lifestyle is adopted, a more positive model is provided for other people in the family, particularly children. 

Healthy Lifestyle Assistant is a web application that aims to support people to change their behavior and improve their health in order to live healthier, longer lives.

More technically, the application is built around (1) exercises and workouts, (2) nutrition, (3) meditation, and (4) a calendar with reminders of the listed activities.

Workout is typically one training. Workout consists of one or more exercises. Exercises have their title and description, reference to particular body parts, and related media references. 
Workouts are associated with reminders like each Monday, each Thursday, etc. Application reminds users of these events.

Exercises can be default and custom. If a user has a basic plan subscription, then only default exercises are available for such a user. For users with a pro subscription also available custom exercises, so they can create their own exercises. Similar logic works for workouts as well.

Nutrition (supplements) and meditation (mental health) are planned to be included in the future. At this moment the project is focused on workouts.


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
