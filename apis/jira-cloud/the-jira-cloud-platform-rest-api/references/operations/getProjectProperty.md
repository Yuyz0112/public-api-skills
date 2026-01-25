# GET /rest/api/3/project/{projectIdOrKey}/properties/{propertyKey}

**Resource:** [Project properties](../resources/Project-properties.md)
**Get project property**
**Operation ID:** `getProjectProperty`

Returns the value of a [project property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties).

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the property.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `propertyKey` | path | string | Yes | The project property key. Use [Get project property keys](#api-rest-api-3-project-projectIdOrKey-properties-get) to get a list of all project property keys. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect. |
| 403 | Returned if the user does not have permission to view the project. |
| 404 | Returned if the project or property is not found. |

**Success Response Schema:**

[EntityProperty](../schemas/Entity/EntityProperty.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
