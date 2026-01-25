# POST /rest/api/3/priorityscheme

**Resource:** [Priority schemes](../resources/Priority-schemes.md)
**Create priority scheme**
**Operation ID:** `createPriorityScheme`

Creates a new priority scheme.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreatePrioritySchemeDetails](../schemas/Create/CreatePrioritySchemeDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is completed. |
| 202 | Returned if the request is accepted. |
| 400 | Returned if the request isn't valid.

**Mappings Validation Errors**

 *  ``The priorities with IDs [ID 1, ID 2, ...] require mapping. Please provide mappings in the 'in' mappings object, where these priorities are the keys with corresponding values.`` The listed priority ID(s) have not been provided as keys for ``in`` mappings but are required, add them to the mappings object. |
| 401 | Returned if the authentication credentials are incorrect. |
| 403 | Returned if the user doesn't have the necessary permissions. |
| 409 | Returned if an action with this priority scheme is still in progress. |

**Success Response Schema:**

[PrioritySchemeId](../schemas/Priority/PrioritySchemeId.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
