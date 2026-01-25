# GET /rest/api/3/application-properties

**Resource:** [Jira settings](../resources/Jira-settings.md)
**Get application property**
**Operation ID:** `getApplicationProperty`

Returns all application properties or an application property.

If you specify a value for the `key` parameter, then an application property is returned as an object (not in an array). Otherwise, an array of all editable application properties is returned. See [Set application property](#api-rest-api-3-application-properties-id-put) for descriptions of editable properties.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key` | query | string | No | The key of the application property. |
| `permissionLevel` | query | string | No | The permission level of all items being returned in the list. |
| `keyFilter` | query | string | No | When a `key` isn't provided, this filters the list of results by the application property `key` using a regular expression. For example, using `jira.lf.*` will return all application properties with keys that start with *jira.lf.*. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the application property is not found or the user does not have permission to view it. |

**Success Response Schema:**

Array of [ApplicationProperty](../schemas/Application/ApplicationProperty.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
