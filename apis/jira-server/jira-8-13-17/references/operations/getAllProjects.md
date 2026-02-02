# GET /project

**Resource:** [project](../resources/project.md)
**Operation ID:** `getAllProjects`

Returns all projects which are visible for the currently logged in user. If no user is logged in, it returns the
 list of projects that are visible when using anonymous access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | the parameters to expand |
| `recent` | query | integer (int32) | No | if this parameter is set then only projects recently accessed by the current user (if not logged in then based on HTTP session) will be returned (maximum count limited to the specified number but no more than 20). |
| `includeArchived` | query | boolean | No | whether to include archived projects in response, default: false |
| `browseArchive` | query | boolean | No | whether to include only projects where current user can browse archive |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

