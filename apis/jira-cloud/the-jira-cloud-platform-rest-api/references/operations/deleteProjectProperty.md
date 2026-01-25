# DELETE /rest/api/3/project/{projectIdOrKey}/properties/{propertyKey}

**Resource:** [Project properties](../resources/Project-properties.md)
**Delete project property**
**Operation ID:** `deleteProjectProperty`

Deletes the [property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) from a project.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) or *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the property.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `propertyKey` | path | string | Yes | The project property key. Use [Get project property keys](#api-rest-api-3-project-projectIdOrKey-properties-get) to get a list of all project property keys. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the project property is deleted. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect. |
| 403 | Returned if the user does not have permission to administer the project. |
| 404 | Returned if the project or property is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
