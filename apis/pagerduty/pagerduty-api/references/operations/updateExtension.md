# PUT /extensions/{id}

**Resource:** [Extensions](../resources/Extensions.md)
**Update an extension**
**Operation ID:** `updateExtension`

Update an existing extension.

Extensions are representations of Extension Schema objects that are attached to Services.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#extensions)

Scoped OAuth requires: `extensions.write`


## Request Body

The extension to be updated.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The extension that was updated. |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

