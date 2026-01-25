# GET /rest/api/3/version/{id}

**Resource:** [Project versions](../resources/Project-versions.md)
**Get version**
**Operation ID:** `getVersion`

Returns a project version.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project containing the version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the version. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about version in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `operations` Returns the list of operations available for this version.
 *  `issuesstatus` Returns the count of issues in this version for each of the status categories *to do*, *in progress*, *done*, and *unmapped*. The *unmapped* property represents the number of issues with a status other than *to do*, *in progress*, and *done*.
 *  `driver` Returns the Atlassian account ID of the version driver.
 *  `approvers` Returns a list containing the Atlassian account IDs of approvers for this version. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the version is not found or the user does not have the necessary permission. |

**Success Response Schema:**

[Version](../schemas/Version/Version.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
