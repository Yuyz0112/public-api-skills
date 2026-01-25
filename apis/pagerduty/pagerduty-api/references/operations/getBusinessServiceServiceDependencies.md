# GET /service_dependencies/business_services/{id}

**Resource:** [Service Dependencies](../resources/Service-Dependencies.md)
**Get Business Service dependencies**
**Operation ID:** `getBusinessServiceServiceDependencies`

Get all immediate dependencies of any Business Service.

Business Services model capabilities that span multiple technical services and that may be owned by several different teams.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#business-services)

Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of service relationships. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

