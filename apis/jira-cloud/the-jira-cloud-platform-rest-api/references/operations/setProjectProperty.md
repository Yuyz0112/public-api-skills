# PUT /rest/api/3/project/{projectIdOrKey}/properties/{propertyKey}

**Resource:** [Project properties](../resources/Project-properties.md)
**Set project property**
**Operation ID:** `setProjectProperty`

Sets the value of the [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). You can use project properties to store custom data against the project.

The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 characters.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) or *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project in which the property is created.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `propertyKey` | path | string | Yes | The key of the project property. The maximum length is 255 characters. |

## Request Body

The value of the property. The value has to be a valid, non-empty [JSON](https://tools.ietf.org/html/rfc4627) value. The maximum length of the property value is 32768 bytes.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the project property is updated. |
| 201 | Returned if the project property is created. |
| 400 | Returned if the project key or id is invalid. |
| 401 | Returned if the authentication credentials are incorrect. |
| 403 | Returned if the user does not have permission to administer the project. |
| 404 | Returned if the project is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
