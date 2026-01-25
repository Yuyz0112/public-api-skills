# GET /addons

**Resource:** [Add-ons](../resources/Add-ons.md)
**List installed Add-ons**
**Operation ID:** `listAddon`

List all of the Add-ons installed on your account.

Addon's are pieces of functionality that developers can write to insert new functionality into PagerDuty's UI.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#add-ons)

Scoped OAuth requires: `addons.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of installed Add-ons. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

