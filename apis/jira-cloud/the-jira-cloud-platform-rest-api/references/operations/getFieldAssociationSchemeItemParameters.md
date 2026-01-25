# GET /rest/api/3/config/fieldschemes/{id}/fields/{fieldId}/parameters

**Resource:** [Field schemes](../resources/Field-schemes.md)
**Get field parameters**
**Operation ID:** `getFieldAssociationSchemeItemParameters`

Retrieve field association parameters on a field association scheme

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | the ID of the field association scheme to retrieve parameters for |
| `fieldId` | path | string | Yes | the ID of the field |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the parameters fetched were successful. |
| 400 | Returned if the request is invalid. If request is malformed, returns a collection of errors. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions |

**Success Response Schema:**

[GetFieldAssociationParametersResponse](../schemas/Get/GetFieldAssociationParametersResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
