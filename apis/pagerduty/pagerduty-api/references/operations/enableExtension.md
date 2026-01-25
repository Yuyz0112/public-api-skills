# POST /extensions/{id}/enable

**Resource:** [Extensions](../resources/Extensions.md)
**Enable an extension**
**Operation ID:** `enableExtension`

Enable an extension that is temporarily disabled. (This API does not require a request body.)

Extensions are representations of Extension Schema objects that are attached to Services.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#extensions)

Scoped OAuth requires: `extensions.write`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The extension that was successfully enabled. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

