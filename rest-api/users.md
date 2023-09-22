# User & Auth Endpoints

### Signup (create user) | Any Plan

POST /api/v1/signup


### Login | Any Plan

POST /api/v1/login


### Is aAthenticated (Validate Token) | Any Plan

GET /api/v1/authenticate (ROLE_USER)


### Get User Details | Any Plan

GET /api/v1/users/{user_id} (ROLE_USER)


### Update User | Any Plan

PATCH /api/v1/users/{user_id} (ROLE_USER)


### Delete User | Any Plan

DELETE /api/v1/users/{user_id} (ROLE_USER)
