# Workout Endpoints

## Body Parts

### List All Body Parts | Any Plan

GET /api/v1/workouts/bodyParts


## Media References

### List Template Media References | Any Plan

GET /api/v1/workouts/mediaRefs/templates


### List All Media References or Custom Only | Pro

GET /api/v1/workouts/mediaRefs?isCustomOnly=


### Create Custom Media Reference | Pro

POST /api/v1/workouts/mediaRefs


### Update Custom Media Reference | Pro

PATCH /api/v1/workouts/mediaRefs/{mediaRef_id}


### Delete Custom Meida Reference | Pro

DELETE /api/v1/workouts/mediaRefs/{mediaRef_id}


## Exercises

### List Template Exercises | Any Plan

GET /api/v1/workouts/exercises/templates


### List All Exercises or Custom Only | Pro

GET /api/v1/workouts/exercises?isCustomOnly=


### Create Custom Exercise | Pro

POST /api/v1/workouts/exercises


### Associate Exercise as Completed | Pro

POST /api/v1/workouts/exercises/{exercise_id}/{user_id}


### Update Custom Exercise | Pro

PATCH /api/v1/workouts/exercises/{exercise_id}


### Delete Custom Exercise | Pro

DELETE /api/v1/workouts/exercises/{exercise_id}


## Workouts

### List Template Workouts | Any Plan

GET /api/v1/workouts/templates


### List All Workouts or Custom Only | Pro

GET /api/v1/workouts?isCustomOnly=


### Create Custom Workout | Pro

POST /api/v1/workouts 


### Update Custom Workout | Pro

PATCH /api/v1/workouts/{workout_id}


### Delete Custom Workout | Pro

DELETE /api/v1/workouts/{workout_id}
