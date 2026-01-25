# GET /v1/files/{file_key}/nodes

**Resource:** [Files](../resources/Files.md)
**Get file JSON for specific nodes**
**Operation ID:** `getFileNodes`

Returns the nodes referenced to by `ids` as a JSON object. The nodes are retrieved from the Figma file referenced to by `file_key`.

The node ID and file key can be parsed from any Figma node url: `https://www.figma.com/file/{file_key}/{title}?node-id={id}`

The `name`, `lastModified`, `thumbnailUrl`, `editorType`, and `version` attributes are all metadata of the specified file.

The `linkAccess` field describes the file link share permission level. There are 5 types of permissions a shared link can have: `"inherit"`, `"view"`, `"edit"`, `"org_view"`, and `"org_edit"`. `"inherit"` is the default permission applied to files created in a team project, and will inherit the project's permissions. `"org_view"` and `"org_edit"` restrict the link to org users.

The `document` attribute contains a Node of type `DOCUMENT`.

The `components` key contains a mapping from node IDs to component metadata. This is to help you determine which components each instance comes from.

By default, no vector data is returned. To return vector data, pass the geometry=paths parameter to the endpoint.
Each node can also inherit properties from applicable styles. The styles key contains a mapping from style IDs to style metadata.

Important: the nodes map may contain values that are `null`. This may be due to the node id not existing within the specified file.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to export JSON from. This can be a file key or branch key. Use `GET /v1/files/:key` with the `branch_data` query param to get the branch key. |
| `ids` | query | string | Yes | A comma separated list of node IDs to retrieve and convert. |
| `version` | query | string | No | A specific version ID to get. Omitting this will get the current version of the file. |
| `depth` | query | number | No | Positive integer representing how deep into the node tree to traverse. For example, setting this to 1 will return only the children directly underneath the desired nodes. Not setting this parameter returns all nodes.

Note: this parameter behaves differently from the same parameter in the `GET /v1/files/:key` endpoint. In this endpoint, the depth will be counted starting from the desired node rather than the document root node. |
| `geometry` | query | string | No | Set to "paths" to export vector data. |
| `plugin_data` | query | string | No | A comma separated list of plugin IDs and/or the string "shared". Any data present in the document written by those plugins will be included in the result in the `pluginData` and `sharedPluginData` properties. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: file_content:read, files:read
