# Meditation Endpoints

### List Template Meditations | Any Plan

GET /api/v1/meditations/templates


### List All Meditations or Custom Only | Pro

GET /api/v1/meditations?isCustomOnly=


### Create Custom Meditation | Pro

POST /api/v1/meditations


### Associate Meditation as Completed | Pro

POST /api/v1/meditations/{meditation_id}/{user_id}


### Update Custom Meditation | Pro

PATCH /api/v1/meditations/{meditation_id}


### Delete Custom Meditation | Pro

DELETE /api/v1/meditations/{meditation_id}
