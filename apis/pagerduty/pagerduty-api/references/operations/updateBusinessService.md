# PUT /business_services/{id}

**Resource:** [Business Services](../resources/Business-Services.md)
**Update a Business Service**
**Operation ID:** `updateBusinessService`

Update an existing Business Service. NOTE that this endpoint also accepts the PATCH verb.

Business services model capabilities that span multiple technical services and that may be owned by several different teams.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#business-services)

Scoped OAuth requires: `services.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The Business Service that was updated. |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

