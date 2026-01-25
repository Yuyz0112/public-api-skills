# GET /rest/api/3/issuetype/{issueTypeId}/properties

**Resource:** [Issue type properties](../resources/Issue-type-properties.md)
**Get issue type property keys**
**Operation ID:** `getIssueTypePropertyKeys`

Returns all the [issue type property](https://developer.atlassian.com/cloud/jira/platform/storing-data-without-a-database/#a-id-jira-entity-properties-a-jira-entity-properties) keys of the issue type.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) to get the property keys of any issue type.
 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) to get the property keys of any issue types associated with the projects the user has permission to browse.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueTypeId` | path | string | Yes | The ID of the issue type. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the issue type ID is invalid. |
| 404 | Returned if:

 *  the issue type is not found.
 *  the user does not have the required permissions. |

**Success Response Schema:**

[PropertyKeys](../schemas/Property/PropertyKeys.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
