# GET /rest/api/3/statuscategory/{idOrKey}

**Resource:** [Workflow status categories](../resources/Workflow-status-categories.md)
**Get status category**
**Operation ID:** `getStatusCategory`

Returns a status category. Status categories provided a mechanism for categorizing [statuses](#api-rest-api-3-status-idOrName-get).

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `idOrKey` | path | string | Yes | The ID or key of the status category. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the status category is not found. |

**Success Response Schema:**

[StatusCategory](../schemas/Status/StatusCategory.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
