# Workout Endpoints


## Exercises

**Create custom exercise** - POST /api/v1/workouts/exercises

**Get custom exercise by id** - GET /api/v1/workouts/exercises/{exercise_id}

**Get default exercise by id** - GET /api/v1/workouts/exercises/default/{exercise_id}

**Get custom exercises** - GET /api/v1/workouts/exercises

**Get default exercises** - GET /api/v1/workouts/exercises/default

**Update custom exercise** - PATCH /api/v1/workouts/exercises/{exercise_id}

**Delete custom exercise** - DELETE /api/v1/workouts/exercises/{exercise_id}


## Workouts

**Create custom workout** - POST /api/v1/workouts

**Get custom workout by id** - GET /api/v1/workouts/{workouts_id}

**Get default workout by id** - GET /api/v1/workouts/default/{workouts_id}

**Get custom workouts** - GET /api/v1/workouts

**Get default workouts** - GET /api/v1/workouts/default

**Update custom workout** - PATCH /api/v1/workouts/{workout_id}

**Delete custom workout** - DELETE /api/v1/workouts/{workout_id}


## Body Parts

**Get body parts** - GET /api/v1/workouts/bodyParts


## Http References

**Create custom http ref** - POST /api/v1/workouts/httpRefs

**Get custom http ref** - GET /api/v1/workouts/httpRefs

**Get default http ref** - GET /api/v1/workouts/httpRefs/default

**Update custom http ref** - PATCH /api/v1/workouts/httpRefs/{httpRef_id}

**Delete custom http ref** - DELETE /api/v1/workouts/httpRefs/{httpRef_id}


## Workout Calendar

**Create workout reminder** - POST /api/v1/calendar/workouts

**Get workout reminder by id** - GET /api/v1/calendar/workouts/{workout_id}

**Get all user's workout reminders** - GET /api/v1/calendar/workouts/users/{user_id}

**Update workout reminder** - PATCH /api/v1/calendar/workouts/{workout_id}

**Delete workout reminder** - DELETE /api/v1/calendar/workouts/{workout_id}


## Workout Completion

**Mark exercise as completed** - POST /api/v1/calendar/completed/users/{user_id}/workouts/{workout_id}/exercises/{exercise_id}


## Workout Pause

**Create exercise pause** - POST /api/v1/calendar/pauses/workouts/{workout_id}/exercises/{exercise_id}

**Get exercise pause by id** - GET /api/v1/calendar/pauses/{pause_id}

**Get all user's exercise pauses** - GET /api/v1/calendar/pauses/users/{user_id}

**Update exercise pause** - PATCH /api/v1/calendar/pauses/{pause_id}

**Delete exercise pause** - DELETE /api/v1/calendar/pauses/{pause_id}


[Top](#workout-endpoints)  
