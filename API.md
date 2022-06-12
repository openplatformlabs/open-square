| Url           | Method | Description               | Request               | Response    | Status Code |
| ------------- | ------ | ------------------------- | --------------------- | ----------- | ----------- |
| /v1/users     | GET    | Get the list of all users |                       | userList    | 200, 400    |
| /v1/users/:id | GET    | Get the detail of a user  |                       | user        | 200, 400    |
| /v1/users     | POST   | Create a new user         | email, password, name | null        | 200, 400    |
| /v1/users/:id | PUT    | Update a user             | password              | null        | 200, 400    |
| /v1/users/:id | DELETE | Delete a user             |                       | null        | 200, 400    |
| /v1/auth      | POST   | Issue access token        | email, password       | accessToken | 200, 400    |
