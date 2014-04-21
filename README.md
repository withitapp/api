# WithIt Api Documentation

The agreement between client apps and the backend server.

## Users

### Fetch a User

    GET /users
    
Required parameters:

* id: `integer`

Returns a user object in JSON format

### Authenticate a User

    POST /auth
    
Required parameters:

* fb_id: `String`
* fb_token: `String`

Returns a user object in JSON format

### Fetch Friends of a User

    GET /friends

Required parameters:

* user_id: `int`

Returns an array of user objects in JSON format

### Fetch Members of a Poll

    GET /members

Required parameters:

* poll_id: `int`

Returns an array of user objects in JSON fromat
    

## Polls

### Fetch All Polls

    GET /polls
    
Returns an array of polls in JSON format

### Fetch A Poll

    GET /polls

Required parameters:

* id: `int`

Returns a poll object in JSON format

### Create a Poll

    POST /polls

Required parameters:

* title: `String`
* description: `String`
* user_id: `int`
* ends_at: `String` 

Returns the ID of the created poll

### Update a Poll

    PATCH /polls

Returns null

Required parameters:

* title: `String`
* description: `String`
* user_id: `int`
* ends_at: `String`

### Delete a Poll

    DELETE /polls

Required parameters:

* id: `int`

Returns null

## Memberships

### Create a Membership

    POST /memberships
    
Required parameters:

* user_id: `int`
* poll_id: `int`
* response: `String`

Returns the ID of the created object.

###





