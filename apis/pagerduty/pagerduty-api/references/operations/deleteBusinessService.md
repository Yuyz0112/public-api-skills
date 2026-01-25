# DELETE /business_services/{id}

**Resource:** [Business Services](../resources/Business-Services.md)
**Delete a Business Service**
**Operation ID:** `deleteBusinessService`

Delete an existing Business Service.

Once the service is deleted, it will not be accessible from the web UI and new incidents won't be able to be created for this service.

Business services model capabilities that span multiple technical services and that may be owned by several different teams.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#business-services)

Scoped OAuth requires: `services.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The Business Service was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

