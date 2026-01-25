# GET /addons/{id}

**Resource:** [Add-ons](../resources/Add-ons.md)
**Get an Add-on**
**Operation ID:** `getAddon`

Get details about an existing Add-on.

Addon's are pieces of functionality that developers can write to insert new functionality into PagerDuty's UI.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#add-ons)

Scoped OAuth requires: `addons.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The requested Add-on. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

