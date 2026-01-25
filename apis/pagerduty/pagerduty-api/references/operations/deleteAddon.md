# DELETE /addons/{id}

**Resource:** [Add-ons](../resources/Add-ons.md)
**Delete an Add-on**
**Operation ID:** `deleteAddon`

Remove an existing Add-on.

Addon's are pieces of functionality that developers can write to insert new functionality into PagerDuty's UI.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#add-ons)

Scoped OAuth requires: `addons.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The Add-on was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

