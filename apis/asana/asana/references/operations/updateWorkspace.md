# PUT /workspaces/{workspace_gid}

**Resource:** [Workspaces](../resources/Workspaces.md)
**Update a workspace**
**Operation ID:** `updateWorkspace`

A specific, existing workspace can be updated by making a PUT request on the URL for that workspace. Only the fields provided in the data block will be updated; any unspecified fields will remain unchanged.
Currently the only field that can be modified for a workspace is its name.
Returns the complete, updated workspace record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The workspace object with all updated properties.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update for the workspace was successful. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
