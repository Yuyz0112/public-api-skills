# POST /extensions

**Resource:** [Extensions](../resources/Extensions.md)
**Create an extension**
**Operation ID:** `createExtension`

Create a new Extension.

Extensions are representations of Extension Schema objects that are attached to Services.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#extensions)

Scoped OAuth requires: `extensions.write`


## Request Body

The extension to be created

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The extension that was created |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |

