# API documentation

## /login

| method | path | description | success | failure |
|--------|------|-------------|---------|---------|
| POST   | /    | login a user | 200    | 401 |

## /users

| method | path | description | success | failure |
|--------|------|-------------|---------|---------|
| GET    | /    | list all users | 200 | 403 |
| GET    | /:id | get single user| 200 | 403, 404 |
| POST   | /    | add a new user | 201 | 400 |
| PUT    | /:id | update user info | 201 | 403 |
| PATCH  | /:id/password | update user password | 201 | 403 |
| DELETE | /:id | delete a single user | 204 | 403 |

## /clients

| method | path | description | success | failure |
|--------|------|-------------|---------|---------|
| GET    | /    | list all clients | 200 | 403 |
| GET    | /:id | list single client | 200 | 403, 404 |
| POST   | /    | add a new client   | 201 | 403 |
| DELETE | /:id | delete a client    | 204 | 403 |

## /resources

| method | path | description | success | failure |
|--------|------|-------------|---------|---------|
| GET    | /    | list all resources | 200 | 403 |
| GET    | /:id | list a single resource | 200 | 403, 404 |
| POST   | /    | add a new resource | 201 | 403 |
| DELETE | /:id | delete a resource | 204 | 403 |

## /codes

| method | path | description | success | failure |
|--------|------|-------------|---------|---------|
| GET    | /:code | get a single code | 200 | 403, 404 |
| POST   | /    | add a new code | 201 | 400, 403 |

## /apikeys

| method | path | description | success | failure |
|--------|------|-------------|---------|---------|
| GET    | /    | list all apikeys | 200 | 403 |
| GET    | /:id | get a single apikey | 200 | 403, 404 |
| POST   | /    | add a new apikey | 201 | 403 |
| DELETE | /:id | delete an apikey | 204 | 403 |
