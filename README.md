# WithIt Api Documentation

The agreement between client apps and the backend server.

## Friendships

#### Fetch a friendship

    GET /friendships/{id}.json
    
## Invitations

#### Fetch an invitation

    GET /invitations/{id}.json
    
## Memberships

#### Fetch a membership

    GET /memberships/{id}.json
    
## Polls

#### Fetch a poll

    GET /polls/{id}.json

## Users

#### Fetch a user

    GET /users/{id}.json

#### Create a user

    POST /users
  
Required parameters:

* username: `string`
* password: `string`
