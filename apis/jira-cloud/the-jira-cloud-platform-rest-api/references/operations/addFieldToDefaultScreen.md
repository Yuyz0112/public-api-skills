# POST /rest/api/3/screens/addToDefault/{fieldId}

**Resource:** [Screens](../resources/Screens.md)
**Add field to default screen**
**Operation ID:** `addFieldToDefaultScreen`

Adds a field to the default tab of the default screen.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the field. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the field it not found or the field is already present. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
