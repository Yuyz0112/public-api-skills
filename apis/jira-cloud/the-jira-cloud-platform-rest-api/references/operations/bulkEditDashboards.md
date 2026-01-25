# PUT /rest/api/3/dashboard/bulk/edit

**Resource:** [Dashboards](../resources/Dashboards.md)
**Bulk edit dashboards**
**Operation ID:** `bulkEditDashboards`

Bulk edit dashboards. Maximum number of dashboards to be edited at the same time is 100.

**[Permissions](#permissions) required:** None

The dashboards to be updated must be owned by the user, or the user must be an administrator.

## Request Body

The details of dashboards being updated in bulk.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BulkEditShareableEntityRequest](../schemas/Bulk/BulkEditShareableEntityRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[BulkEditShareableEntityResponse](../schemas/Bulk/BulkEditShareableEntityResponse.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
