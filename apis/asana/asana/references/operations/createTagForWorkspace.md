# POST /workspaces/{workspace_gid}/tags

**Resource:** [Tags](../resources/Tags.md)
**Create a tag in a workspace**
**Operation ID:** `createTagForWorkspace`

<b>Required scope: </b><code>tags:write</code>

Creates a new tag in a workspace or organization.

Every tag is required to be created in a specific workspace or
organization, and this cannot be changed once set. Note that you can use
the workspace parameter regardless of whether or not it is an
organization.

Returns the full record of the newly created tag.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The tag to create.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created the newly specified tag. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: tags:write
