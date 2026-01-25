# POST /business_services

**Resource:** [Business Services](../resources/Business-Services.md)
**Create a Business Service**
**Operation ID:** `createBusinessService`

Create a new Business Service.

Business services model capabilities that span multiple technical services and that may be owned by several different teams.

There is a limit of 5,000 business services per account. If the limit is reached, the API will respond with an error.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#business-services)

Scoped OAuth requires: `services.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The Business Service that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

