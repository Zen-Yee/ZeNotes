# Common HTTP Status

## Success Responses
| Code           | Meaning                       | When to Use                                                |
| -------------- | ----------------------------- | ---------------------------------------------------------- |
| 200 OK         | Request succeeded             | Standard GET, PUT, PATCH requests that return data         |
| 201 Created    | Resource created              | When creating a new resource (POST /signup, POST /posts)   |
| 204 No Content | Success but no data to return | Deleting a resource or updating without returning anything |

## Client Errors (4xx)
| Code                     | Meaning                       | When to Use                                              |
| ------------------------ | ----------------------------- | -------------------------------------------------------- |
| 400 Bad Request          | Invalid input                 | Missing fields, invalid JSON, failed validation          |
| 401 Unauthorized         | Not authenticated             | User tries to access protected route without valid token |
| 403 Forbidden            | Authenticated but not allowed | User has token but insufficient permissions              |
| 404 Not Found            | Resource doesn’t exist        | Post, comment, or user not found                         |
| 409 Conflict             | Conflict with existing data   | Duplicate email, username, or conflicting resource       |
| 422 Unprocessable Entity | Semantically invalid request  | Email format invalid, password too short                 |

## Server Errors (5xx)
| Code                     | Meaning                       | When to Use                                              |
| ------------------------ | ----------------------------- | -------------------------------------------------------- |
| 400 Bad Request          | Invalid input                 | Missing fields, invalid JSON, failed validation          |
| 401 Unauthorized         | Not authenticated             | User tries to access protected route without valid token |
| 403 Forbidden            | Authenticated but not allowed | User has token but insufficient permissions              |
| 404 Not Found            | Resource doesn’t exist        | Post, comment, or user not found                         |
| 409 Conflict             | Conflict with existing data   | Duplicate email, username, or conflicting resource       |
| 422 Unprocessable Entity | Semantically invalid request  | Email format invalid, password too short                 |
