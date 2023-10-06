## Backend API's
### GET
* **User** &rarr; /api/user/confirm_email?token= &rarr; "confirm email by token".
* **Event** &rarr; /api/events &rarr; "get list of events".
* **Event Form** &rarr; /api/eventForm &rarr; "get all event form".
* **Event Form** &rarr; /api/eventForm/:id &rarr; "get event form by id".

### POST
* **User** &rarr; /api/user/signup &rarr; "create new user".
* **User** &rarr; /api/user/login &rarr; "login user".
* **Event** &rarr; /api/events/request &rarr; "create new event".
* **Event Form** &rarr; /api/eventForm &rarr; "create new event form".

### PATCH
* **User** &rarr; /api/user/update/ &rarr; "update user profile".
* **User** &rarr; /api/user/control/:email &rarr; "control a user (status, role)".

### DELETE