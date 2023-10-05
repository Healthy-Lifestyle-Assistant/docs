# Workout Endpoints

## Body Parts

**List All Body Parts (Unlogged)** - GET /api/v1/workouts/bodyParts


## Media References

**List Default Media References (Unlogged)** - GET /api/v1/workouts/httpRefs/default

**List Custom Media References** - GET /api/v1/workouts/httpRefs

**Create Custom Media Reference** - POST /api/v1/workouts/httpRefs

**Update Custom Media Reference** - PATCH /api/v1/workouts/httpRefs/{httpRef_id}

**Delete Custom Media Reference** - DELETE /api/v1/workouts/httpRefs/{httpRef_id}


## Exercises

**List Default Exercises (Unlogged)** - GET /api/v1/workouts/exercises/default

**Get Default Exercise by Id (Unlogged)** - GET /api/v1/workouts/exercises/default/{exercise_id}

**List Custom Exercises** - GET /api/v1/workouts/exercises

**Get Custom Exercise by Id** - GET /api/v1/workouts/exercises/{exercise_id}

**Create Custom Exercise** - POST /api/v1/workouts/exercises

**Update Custom Exercise** - PATCH /api/v1/workouts/exercises/{exercise_id}

**Delete Custom Exercise** - DELETE /api/v1/workouts/exercises/{exercise_id}

**List User's All Exercises (Default and Custom)** - GET /api/v1/exercises/users/{user_id}

**Mark Exercise as Completed (Default or Custom)** - POST /api/v1/workouts/exercises/completed?exercise_id=int&workout_id=


## Workouts

**List Default Workouts (Unlogged)** - GET /api/v1/workouts/default

**Get Default Workout by Id (Unlogged)** - GET /api/v1/workouts/default/{workout_id}

**List Custom Workouts** - GET /api/v1/workouts/custom

**Get Custom Workout by Id** - GET /api/v1/workouts/custom/{workouts_id}

**Create Custom Workout** - POST /api/v1/workouts/custom

**Update Custom Workout** - PATCH /api/v1/workouts/custom/{workout_id}

**Delete Custom Workout** - DELETE /api/v1/workouts/custom/{workout_id}

**List User's All Workouts (Default and Custom)** - GET /api/v1/workouts/users/{user_id}


## Reminders

**List All User's Workout Reminders** - GET /api/v1/calendar/workouts

**Get Workout Reminder by Id** - GET /api/v1/calendar/workouts/{workout_id}

**Create Workout Reminder** - POST /api/v1/calendar/workouts

**Update Workout Reminder** - PATCH /api/v1/calendar/workouts/{workout_id}

**Delete Workout Reminder** - DELETE /api/v1/calendar/workouts/{workout_id}
