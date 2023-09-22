# Nutrition Endpoints

## Recipes

### List Template Recipes | Any Plan

GET /api/v1/nutrition/recipes/templates


### List All Recipes or Custom Only | Pro

GET /api/v1/nutrition/recipes?isCustomOnly=


### Create custom recipe | Pro

POST /api/v1/nutrition/recipes


### Associate Recipe (Dish) as Completed | Pro

POST /api/v1/nutrition/recipes/{recipe_id}/{user_id}


### Update Custom Recipe | Pro

PATCH /api/v1/nutrition/recipes/{recipet_id}


### Delete Custom Recipe | Pro

DELETE /api/v1/nutrition/recipes/{recipe_id}


## Supplements

### List Template Supplements | Any Plan

GET /api/v1/nutrition/supplements/templates


### List All Supplements or Custom Only | Pro

GET /api/v1/nutrition/supplements?isCustomOnly=


### Create Custom Supplement | Pro

POST /api/v1/nutrition/supplements


### Associate Supplement Intake as Completed | Pro

POST /api/v1/nutrition/supplements/{supplement_id}/{user_id}


### Update Custom Supplement | Pro

PATCH /api/v1/nutrition/supplements/{supplement_id}


### Delete Custom Supplement | Pro

DELETE /api/v1/nutrition/supplements/{supplement_id}
