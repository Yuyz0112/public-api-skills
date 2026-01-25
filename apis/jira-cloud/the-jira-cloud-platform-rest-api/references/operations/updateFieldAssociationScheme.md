# PUT /rest/api/3/config/fieldschemes/{id}

**Resource:** [Field schemes](../resources/Field-schemes.md)
**Update field scheme**
**Operation ID:** `updateFieldAssociationScheme`

Endpoint for updating an existing field association scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes |  |

## Request Body

The request containing the desired updates to the field association scheme

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateFieldAssociationSchemeRequest](../schemas/Update/UpdateFieldAssociationSchemeRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the update was successful. |
| 400 | Returned if the request is invalid. If request is malformed, returns a collection of errors. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions |
| 404 | Returned if the feature flag is disabled or the scheme ID is not found. |

**Success Response Schema:**

[UpdateFieldAssociationSchemeResponse](../schemas/Update/UpdateFieldAssociationSchemeResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
