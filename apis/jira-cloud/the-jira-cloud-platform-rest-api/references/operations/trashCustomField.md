# POST /rest/api/3/field/{id}/trash

**Resource:** [Issue fields](../resources/Issue-fields.md)
**Move custom field to trash**
**Operation ID:** `trashCustomField`

Moves a custom field to trash. See [Edit or delete a custom field](https://confluence.atlassian.com/x/Z44fOw) for more information on trashing and deleting custom fields.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a custom field. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the custom field is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
