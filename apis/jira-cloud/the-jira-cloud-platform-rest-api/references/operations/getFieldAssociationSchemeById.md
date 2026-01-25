# GET /rest/api/3/config/fieldschemes/{id}

**Resource:** [Field schemes](../resources/Field-schemes.md)
**Get field scheme**
**Operation ID:** `getFieldAssociationSchemeById`

Endpoint for fetching a field association scheme by its ID

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The scheme id to fetch |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if a field association scheme matches the given scheme ID |
| 403 | Returned if the user does not have the required permissions |
| 404 | Returned if provided ID does not match any field association schemes |

**Success Response Schema:**

[GetFieldAssociationSchemeByIdResponse](../schemas/Get/GetFieldAssociationSchemeByIdResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
