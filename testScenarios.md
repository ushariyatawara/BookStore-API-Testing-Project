# API Test Scenarios

## GET /users
- Verify whether list of users is retrieved successfully
- Verify whether response structure contains `id`, `email`, `first_name`, `last_name`

## GET /users/{id}
- Verify whether retrieving a single existing user returns 200
- Verify whether retrieving a non-existing user returns 404

## POST /users
- Verify whether creating a user with valid data succeeds
- Verify whether creating a user with missing or invalid data returns 400

## DELETE /users/{id}
- Verify whether deleting an existing user returns 204
- Verify whether deleting a non-existing user returns 404