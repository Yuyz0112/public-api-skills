# DELETE /api/v4/projects/{id}/issues/{issue_iid}

**Resource:** [Projects](../resources/Projects.md)
**Delete a project issue**
**Operation ID:** `deleteApiV4ProjectsIdIssuesIssueIid`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `issue_iid` | path | integer | Yes | The internal ID of a project issue |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

