# GET /workspaces/{workspace_gid}/tasks/search

**Resource:** [Tasks](../resources/Tasks.md)
**Search tasks in a workspace**
**Operation ID:** `searchTasksForWorkspace`

<b>Required scope: </b><code>tasks:read</code>

To mirror the functionality of the Asana web app's advanced search feature, the Asana API has a task search endpoint that allows you to build complex filters to find and retrieve the exact data you need.
#### Premium access
Like the Asana web product's advance search feature, this search endpoint will only be available to premium Asana users. A user is premium if any of the following is true:

- The workspace in which the search is being performed is a premium workspace - The user is a member of a premium team inside the workspace

Even if a user is only a member of a premium team inside a non-premium workspace, search will allow them to find data anywhere in the workspace, not just inside the premium team. Making a search request using credentials of a non-premium user will result in a `402 Payment Required` error.
#### Pagination
Search results are not stable; repeating the same query multiple times may return the data in a different order, even if the data do not change. Because of this, the traditional [pagination](https://developers.asana.com/docs/#pagination) available elsewhere in the Asana API is not available here. However, you can paginate manually by sorting the search results by their creation time and then modifying each subsequent query to exclude data you have already seen. Page sizes are limited to a maximum of 100 items, and can be specified by the `limit` query parameter.
#### Eventual consistency
Changes in Asana (regardless of whether they’re made though the web product or the API) are forwarded to our search infrastructure to be indexed. This process can take between 10 and 60 seconds to complete under normal operation, and longer during some production incidents. Making a change to a task that would alter its presence in a particular search query will not be reflected immediately. This is also true of the advanced search feature in the web product.
#### Rate limits
You may receive a `429 Too Many Requests` response if you hit any of our [rate limits](https://developers.asana.com/docs/#rate-limits).
#### Custom field parameters
| Parameter name | Custom field type | Accepted type |
|---|---|---|
| custom_fields.{gid}.is_set | All | Boolean |
| custom_fields.{gid}.value | Text | String |
| custom_fields.{gid}.value | Number | Number |
| custom_fields.{gid}.value | Enum | Enum option ID |
| custom_fields.{gid}.starts_with | Text only | String |
| custom_fields.{gid}.ends_with | Text only | String |
| custom_fields.{gid}.contains | Text only | String |
| custom_fields.{gid}.less_than | Number only | Number |
| custom_fields.{gid}.greater_than | Number only | Number |


For example, if the gid of the custom field is 12345, these query parameter to find tasks where it is set would be `custom_fields.12345.is_set=true`. To match an exact value for an enum custom field, use the gid of the desired enum option and not the name of the enum option: `custom_fields.12345.value=67890`.

**Not Supported**: searching for multiple exact matches of a custom field, searching for multi-enum custom field

*Note: If you specify `projects.any` and `sections.any`, you will receive tasks for the project **and** tasks for the section. If you're looking for only tasks in a section, omit the `projects.any` from the request.*

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the section's tasks. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tasks:read
