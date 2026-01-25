# PUT /rest/api/3/issuetype/{issueTypeId}/properties/{propertyKey}

**Resource:** [Issue type properties](../resources/Issue-type-properties.md)
**Set issue type property**
**Operation ID:** `setIssueTypeProperty`

Creates or updates the value of the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties). Use this resource to store and update data against an issue type.

The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 characters.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueTypeId` | path | string | Yes | The ID of the issue type. |
| `propertyKey` | path | string | Yes | The key of the issue type property. The maximum length is 255 characters. |

## Request Body

The value of the property. The value has to be a valid, non-empty [JSON](https://tools.ietf.org/html/rfc4627) value. The maximum length of the property value is 32768 bytes.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the issue type property is updated. |
| 201 | Returned if the issue type property is created. |
| 400 | Returned if:

 *  the issue type ID is invalid.
 *  a property value is not provided.
 *  the property value JSON content is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to modify the issue type. |
| 404 | Returned if:

 *  the issue type is not found.
 *  the user does not have the permission view the issue type. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
