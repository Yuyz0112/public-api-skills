# POST /rest/api/3/config/fieldschemes

**Resource:** [Field schemes](../resources/Field-schemes.md)
**Create field scheme**
**Operation ID:** `createFieldAssociationScheme`

Endpoint for creating a new field association scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

The request containing the name and description of the field association scheme

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateFieldAssociationSchemeRequest](../schemas/Create/CreateFieldAssociationSchemeRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the creation was successful. |
| 400 | Returned if the request is invalid. If request is malformed, returns a collection of errors. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions |
| 404 | Returned if the feature flag is disabled or the scheme ID is not found. |

**Success Response Schema:**

[CreateFieldAssociationSchemeResponse](../schemas/Create/CreateFieldAssociationSchemeResponse.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
