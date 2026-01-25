# GET /rest/api/3/project/{projectIdOrKey}/version

**Resource:** [Project versions](../resources/Project-versions.md)
**Get project versions paginated**
**Operation ID:** `getProjectVersionsPaginated`

Returns a [paginated](#pagination) list of all versions in a project. See the [Get project versions](#api-rest-api-3-project-projectIdOrKey-versions-get) resource if you want to get a full list of versions without pagination.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |
| `orderBy` | query | enum: description, -description, +description... | No | [Order](#ordering) the results by a field:

 *  `description` Sorts by version description.
 *  `name` Sorts by version name.
 *  `releaseDate` Sorts by release date, starting with the oldest date. Versions with no release date are listed last.
 *  `sequence` Sorts by the order of appearance in the user interface.
 *  `startDate` Sorts by start date, starting with the oldest date. Versions with no start date are listed last. |
| `query` | query | string | No | Filter the results using a literal string. Versions with matching `name` or `description` are returned (case insensitive). |
| `status` | query | string | No | A list of status values used to filter the results by version status. This parameter accepts a comma-separated list. The status values are `released`, `unreleased`, and `archived`. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `issuesstatus` Returns the number of issues in each status category for each version.
 *  `operations` Returns actions that can be performed on the specified version.
 *  `driver` Returns the Atlassian account ID of the version driver.
 *  `approvers` Returns a list containing the approvers for this version. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 404 | Returned if the project is not found or the user does not have permission to view it. |

**Success Response Schema:**

[PageBeanVersion](../schemas/Page/PageBeanVersion.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
