# PUT /addons/{id}

**Resource:** [Add-ons](../resources/Add-ons.md)
**Update an Add-on**
**Operation ID:** `updateAddon`

Update an existing Add-on.

Addon's are pieces of functionality that developers can write to insert new functionality into PagerDuty's UI.

Given a configuration containing a `src` parameter, that URL will be embedded in an `iframe` on a page that's available to users from a drop-down menu.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#add-ons)

Scoped OAuth requires: `addons.write`


## Request Body

The Add-on to be updated.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The Add-on that was updated. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

