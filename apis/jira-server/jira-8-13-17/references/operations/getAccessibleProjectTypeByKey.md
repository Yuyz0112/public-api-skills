# GET /project/type/{projectTypeKey}/accessible

**Resource:** [project](../resources/project.md)
**Operation ID:** `getAccessibleProjectTypeByKey`

Returns the project type with the given key, if it is accessible to the logged in user.
 This takes into account whether the user is licensed on the Application that defines the project type.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

