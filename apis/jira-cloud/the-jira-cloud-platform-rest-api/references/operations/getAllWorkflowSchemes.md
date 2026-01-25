# GET /rest/api/3/workflowscheme

**Resource:** [Workflow schemes](../resources/Workflow-schemes.md)
**Get all workflow schemes**
**Operation ID:** `getAllWorkflowSchemes`

Returns a [paginated](#pagination) list of all workflow schemes, not including draft workflow schemes.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[PageBeanWorkflowScheme](../schemas/Page/PageBeanWorkflowScheme.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
