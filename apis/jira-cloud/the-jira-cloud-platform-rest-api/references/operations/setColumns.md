# PUT /rest/api/3/filter/{id}/columns

**Resource:** [Filters](../resources/Filters.md)
**Set columns**
**Operation ID:** `setColumns`

Sets the columns for a filter. Only navigable fields can be set as columns. Use [Get fields](#api-rest-api-3-field-get) to get the list fields in Jira. A navigable field has `navigable` set to `true`.

The parameters for this resource are expressed as HTML form data. For example, in curl:

`curl -X PUT -d columns=summary -d columns=description https://your-domain.atlassian.net/rest/api/3/filter/10000/columns`

**[Permissions](#permissions) required:** Permission to access Jira, however, columns are only set for:

 *  filters owned by the user.
 *  filters shared with a group that the user is a member of.
 *  filters shared with a private project that the user has *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for.
 *  filters shared with a public project.
 *  filters shared with the public.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the filter. |

## Request Body

The IDs of the fields to set as columns. In the form data, specify each field as `columns=id`, where `id` is the *id* of a field (as seen in the response for [Get fields](#api-rest-api-<ver>-field-get)). For example, `columns=summary`.

**Required:** Yes

**Content Types:** `*/*`, `application/json`, `multipart/form-data`

**Schema:** [ColumnRequestBody](../schemas/Column/ColumnRequestBody.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  a non-navigable field is set as a column.
 *  the user does not have permission to view the filter. |
| 403 | Returned if the requesting user is not an owner of the filter. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
