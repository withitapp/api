# WithIt Api Documentation

The agreement between client apps and the backend server.

## Friendships

#### Fetch a friendship

    GET /friendships/{id}.json
    
No parameter

## Invitations

    GET /invitations/{id}.json
    
No parameter

## Memberships

#### Fetch a membership

    GET /memberships/{id}.json
    
No parameters

## Polls

#### Fetch a poll

    GET /polls/{id}.json

No paramters

## Users

#### Fetch a user

    GET /users/{id}.json

No parameter  

#### Create a user

    POST /users
  
Required parameters:

* username: `string`
* password: `string`
