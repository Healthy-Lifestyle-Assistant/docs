# Chat Endpoints

## Chats

### List All User’s Chats | Pro

GET /api/v1/chats/{user_id}


### Get Chat By Id | Pro

GET /api/v1/chats/{chat_id}


### Create Chat | Pro

POST /api/v1/chats


### Update Chat (Title Only) | Pro

PATCH /api/v1/chats/{chat_id}


### Delete Chat | Pro

DELETE /api/v1/chats/{chat_id}


## Messages

### List All Chat’s Messages | Pro

GET /api/v1/chats/{chat_id}/messages


### Create Message | Pro

POST /api/v1/chats/{chat_id}/messages
