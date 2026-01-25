# DELETE /extensions/{id}

**Resource:** [Extensions](../resources/Extensions.md)
**Delete an extension**
**Operation ID:** `deleteExtension`

Delete an existing extension.

Once the extension is deleted, it will not be accessible from the web UI and new incidents won't be able to be created for this extension.

Extensions are representations of Extension Schema objects that are attached to Services.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#extensions)

Scoped OAuth requires: `extensions.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The extension was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

