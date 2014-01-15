# WithIt Api Documentation

The agreement between client apps and the backend server.

## Friendships

#### Index friendships

    GET /friendships
    
Optional parameters:

* user_id: `integer`

#### Fetch a friendship

    GET /friendships/{id}
    
## Invitations

#### Index invitations

    GET /invitations

Optional parameters:

* user_id: `integer`

#### Fetch an invitation

    GET /invitations/{id}
    
## Memberships

#### Index memberships

    GET /memberhips

Optional parameters

* user_id: `integer`

#### Fetch a membership

    GET /memberships/{id}
    
## Polls

#### Fetch a poll

    GET /polls/{id}

## Users

#### Fetch a user

    GET /users/{id}

#### Create a user

    POST /users
  
Required parameters:

* username: `string`
* password: `string`
