## Todo List - Work with middlewares

---


### Checks Create Todos User Availability

- [] Should be able to let user create a new todo when is in free plan and have less than ten todos
- [] Should not be able to let user create a new todo when is not Pro and already have ten todos
- [] Should be able to let user create infinite new todos when is in Pro plan


### Checks Exists User Account

- [X] Should be able to find user by username in header and pass it to request.user
- [X] Should not be able to find a non existing user by username in header


### Checks Todo Exists

- [] Should be able to put user and todo in request when both exits
- [] Should not be able to put user and todo in request when user does not exists
- [] Should not be able to put user and todo in request when todo id is not uuid
- [] Should not be able to put user and todo in request when todo does not exists


### Find User By Id

- [X] Should be able to find user by id route param and pass it to request.user
- [X] Should not be able to pass user to request.user when it does not exists