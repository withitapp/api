# WithIt Api Documentation

The agreement between client apps and the backend server.

## Friendships

#### Index friendships

    GET /friendships
    
Optional parameters:

* alpha_id: `integer`
* beta_id: `integer`

#### Fetch a friendship

    GET /friendships/{id}
    
## Invitations

#### Index invitations

    GET /invitations

Optional parameters:

* sender_id: `integer`
* receiver_id: `integer`

#### Fetch an invitation

    GET /invitations/{id}
    
## Memberships

#### Index memberships

    GET /memberships

Optional parameters

* user_id: `integer`
* poll_id: `integer`
* 
#### Create a membership

    POST /memberships

Required parameters

* user_id: `integer`
* poll_id: `integer`

#### Fetch a membership

    GET /memberships/{id}
    
## Polls

#### Fetch a poll

    GET /polls/{id}
    
#### Create a poll

    POST /polls
    
Required parameters:

* title: `string`
* user_id: `integer`

## Users

#### Fetch a user

    GET /users/{id}

#### Create a user

    POST /users
  
Required parameters:

* username: `string`
* password: `string`
