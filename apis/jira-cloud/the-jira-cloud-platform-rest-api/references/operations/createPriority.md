# POST /rest/api/3/priority

**Resource:** [Issue priorities](../resources/Issue-priorities.md)
**Create priority**
**Operation ID:** `createPriority`
⚠️ **Deprecated**

Creates an issue priority.

Deprecation applies to iconUrl param in request body which will be sunset on 16th Mar 2025. For more details refer to [changelog](https://developer.atlassian.com/changelog/#CHANGE-1525).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreatePriorityDetails](../schemas/Create/CreatePriorityDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user doesn't have the necessary permission. |

**Success Response Schema:**

[PriorityId](../schemas/Priority/PriorityId.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
