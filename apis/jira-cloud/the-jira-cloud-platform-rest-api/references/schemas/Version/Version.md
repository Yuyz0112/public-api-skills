# Version

Details about a project version.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `approvers` | VersionApprover[] | No | If the expand option `approvers` is used, returns a list containing the approvers for this version. |
| `archived` | boolean | No | Indicates that the version is archived. Optional when creating or updating a version. |
| `description` | string | No | The description of the version. Optional when creating or updating a version. The maximum size is 16,384 bytes. |
| `driver` | string | No | If the expand option `driver` is used, returns the Atlassian account ID of the driver. |
| `expand` | string | No | Use [expand](em>#expansion) to include additional information about version in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `operations` Returns the list of operations available for this version.
 *  `issuesstatus` Returns the count of issues in this version for each of the status categories *to do*, *in progress*, *done*, and *unmapped*. The *unmapped* property contains a count of issues with a status other than *to do*, *in progress*, and *done*.
 *  `driver` Returns the Atlassian account ID of the version driver.
 *  `approvers` Returns a list containing approvers for this version.

Optional for create and update. |
| `id` | string | No | The ID of the version. |
| `issuesStatusForFixVersion` | any | No | If the expand option `issuesstatus` is used, returns the count of issues in this version for each of the status categories *to do*, *in progress*, *done*, and *unmapped*. The *unmapped* property contains a count of issues with a status other than *to do*, *in progress*, and *done*. |
| `moveUnfixedIssuesTo` | string (uri) | No | The URL of the self link to the version to which all unfixed issues are moved when a version is released. Not applicable when creating a version. Optional when updating a version. |
| `name` | string | No | The unique name of the version. Required when creating a version. Optional when updating a version. The maximum length is 255 characters. |
| `operations` | SimpleLink[] | No | If the expand option `operations` is used, returns the list of operations available for this version. |
| `overdue` | boolean | No | Indicates that the version is overdue. |
| `project` | string | No | Deprecated. Use `projectId`. |
| `projectId` | integer (int64) | No | The ID of the project to which this version is attached. Required when creating a version. Not applicable when updating a version. |
| `releaseDate` | string (date) | No | The release date of the version. Expressed in ISO 8601 format (yyyy-mm-dd). Optional when creating or updating a version. |
| `released` | boolean | No | Indicates that the version is released. If the version is released a request to release again is ignored. Not applicable when creating a version. Optional when updating a version. |
| `self` | string (uri) | No | The URL of the version. |
| `startDate` | string (date) | No | The start date of the version. Expressed in ISO 8601 format (yyyy-mm-dd). Optional when creating or updating a version. |
| `userReleaseDate` | string | No | The date on which work on this version is expected to finish, expressed in the instance's *Day/Month/Year Format* date format. |
| `userStartDate` | string | No | The date on which work on this version is expected to start, expressed in the instance's *Day/Month/Year Format* date format. |

