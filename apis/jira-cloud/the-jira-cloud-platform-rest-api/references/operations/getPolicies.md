# GET /rest/api/3/data-policy/project

**Resource:** [App data policies](../resources/App-data-policies.md)
**Get data policy for projects**
**Operation ID:** `getPolicies`

Returns data policies for the projects specified in the request.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ids` | query | string | No | A list of project identifiers. This parameter accepts a comma-separated list. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid or includes invalid or not-permitted project identifiers. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the client is not authorized to make the request. |

**Success Response Schema:**

[ProjectDataPolicies](../schemas/Project/ProjectDataPolicies.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
