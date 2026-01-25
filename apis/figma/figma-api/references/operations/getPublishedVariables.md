# GET /v1/files/{file_key}/variables/published

**Resource:** [Variables](../resources/Variables.md)
**Get published variables**
**Operation ID:** `getPublishedVariables`

**This API is available to full members of Enterprise orgs.**

The `GET /v1/files/:file_key/variables/published` endpoint returns the variables that are published from the given file.

The response for this endpoint contains some key differences compared to the `GET /v1/files/:file_key/variables/local` endpoint:

- Each variable and variable collection contains a `subscribed_id`.
- Modes are omitted for published variable collections

Published variables have two ids: an id that is assigned in the file where it is created (`id`), and an id that is used by subscribing files (`subscribed_id`). The `id` and `key` are stable over the lifetime of the variable. The `subscribed_id` changes every time the variable is modified and published. The same is true for variable collections.

The `updatedAt` fields are ISO 8601 timestamps that indicate the last time that a change to a variable was published. For variable collections, this timestamp will change any time a variable in the collection is changed.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `file_key` | path | string | Yes | File to get variables from. This must be a main file key, not a branch key, as it is not possible to publish from branches. |

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
