# Workout Endpoints

## Body Parts

**List All Body Parts (Unlogged)** - GET /api/v1/workouts/bodyParts


## Media References

**List Default Media References (Unlogged)** - GET /api/v1/workouts/httpRefs/default

**List Custom Media References (Pro)** - GET /api/v1/workouts/httpRefs

**Create Custom Media Reference (Pro)** - POST /api/v1/workouts/httpRefs

**Update Custom Media Reference (Pro)** - PATCH /api/v1/workouts/httpRefs/{httpRef_id}

**Delete Custom Meida Reference (Pro)** - DELETE /api/v1/workouts/httpRefs/{httpRef_id}


## Exercises

**List Default Exercises (Unlogged)** - GET /api/v1/workouts/exercises/default

**List Custom Exercises (Pro)** - GET /api/v1/workouts/exercises

**Create Custom Exercise (Pro)** - POST /api/v1/workouts/exercises

**Associate Exercise as Completed (Pro)** - POST /api/v1/workouts/exercises/completed?exercise_id=int&workout_id=

**Update Custom Exercise (Pro)** - PATCH /api/v1/workouts/exercises/{exercise_id}

**Delete Custom Exercise (Pro)** - DELETE /api/v1/workouts/exercises/{exercise_id}


## Workouts

**List Default Workouts (Unlogged)** - GET /api/v1/workouts/default

**List Custom Workouts (Pro)** - GET /api/v1/workouts

**Create Custom Workout (Pro)** - POST /api/v1/workouts 

**Update Custom Workout (Pro)** - PATCH /api/v1/workouts/{workout_id}

**Delete Custom Workout (Pro)** - DELETE /api/v1/workouts/{workout_id}