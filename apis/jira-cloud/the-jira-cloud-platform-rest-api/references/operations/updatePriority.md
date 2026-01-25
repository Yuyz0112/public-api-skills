# PUT /rest/api/3/priority/{id}

**Resource:** [Issue priorities](../resources/Issue-priorities.md)
**Update priority**
**Operation ID:** `updatePriority`
⚠️ **Deprecated**

Updates an issue priority.

At least one request body parameter must be defined.

Deprecation applies to iconUrl param in request body which will be sunset on 16th Mar 2025. For more details refer to [changelog](https://developer.atlassian.com/changelog/#CHANGE-1525).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the issue priority. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdatePriorityDetails](../schemas/Update/UpdatePriorityDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 404 | Returned if the issue priority isn't found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
