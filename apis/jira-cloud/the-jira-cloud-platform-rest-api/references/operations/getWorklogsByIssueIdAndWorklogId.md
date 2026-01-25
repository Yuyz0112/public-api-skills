# POST /rest/internal/api/latest/worklog/bulk

**Resource:** [rest](../resources/rest.md)
**Get worklogs by issue id and worklog id**
**Operation ID:** `getWorklogsByIssueIdAndWorklogId`

Returns worklog details for a list of issue ID and worklog ID pairs.

This is an internal API for bulk fetching worklogs by their issue and worklog IDs. Worklogs that don't exist will be filtered out from the response.

The returned list of worklogs is limited to 1000 items.

**[Permissions](#permissions) required:** This is an internal service-to-service API that requires ASAP authentication. No user permission checks are performed as this bypasses normal user context.

## Request Body

A JSON object containing a list of issue ID and worklog ID pairs.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [BulkWorklogKeyRequestBean](../schemas/Bulk/BulkWorklogKeyRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request contains more than 1000 worklog pairs, is empty, or has invalid format. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 500 | Returned if there is an internal server error. |

**Success Response Schema:**

[BulkWorklogKeyResponseBean](../schemas/Bulk/BulkWorklogKeyResponseBean.md)

## Security

- **basicAuth**
