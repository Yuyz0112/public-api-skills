# PUT /rest/api/3/component/{id}

**Resource:** [Project components](../resources/Project-components.md)
**Update component**
**Operation ID:** `updateComponent`

Updates a component. Any fields included in the request are overwritten. If `leadAccountId` is an empty string ("") the component lead is removed.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the component or *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the component. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ProjectComponent](../schemas/Project/ProjectComponent.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  the user is not found.
 *  `assigneeType` is an invalid value.
 *  `name` is over 255 characters in length. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to manage the project containing the component or does not have permission to administer Jira. |
| 404 | Returned if the component is not found or the user does not have permission to browse the project containing the component. |

**Success Response Schema:**

[ProjectComponent](../schemas/Project/ProjectComponent.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
