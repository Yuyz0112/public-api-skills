# PUT /rest/api/3/field/{fieldId}

**Resource:** [Issue fields](../resources/Issue-fields.md)
**Update custom field**
**Operation ID:** `updateCustomField`

Updates a custom field.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |

## Request Body

The custom field update details.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateCustomFieldDetails](../schemas/Update/UpdateCustomFieldDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the custom field is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
