# GET /v1/files/{file_key}/variables/local

**Resource:** [Variables](../resources/Variables.md)
**Get local variables**
**Operation ID:** `getLocalVariables`

**This API is available to full members of Enterprise orgs.**

The `GET /v1/files/:file_key/variables/local` endpoint lets you enumerate local variables created in the file and remote variables used in the file. Remote variables are referenced by their `subscribed_id`.

As a part of the Variables related API additions, the `GET /v1/files/:file_key` endpoint now returns a `boundVariables` property, containing the `variableId` of the bound variable. The `GET /v1/files/:file_key/variables/local` endpoint can be used to get the full variable or variable collection object.

Note that `GET /v1/files/:file_key/variables/published` does not return modes. Instead, you will need to use the `GET /v1/files/:file_key/variables/local` endpoint, in the same file, to examine the mode values.
        

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to get variables from. This can be a file key or branch key. Use `GET /v1/files/:key` with the `branch_data` query param to get the branch key. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |
| 500 | (reference) |

## Security

- **PersonalAccessToken**
- **OAuth2**: file_variables:read
