# POST /service_dependencies/associate

**Resource:** [Service Dependencies](../resources/Service-Dependencies.md)
**Associate service dependencies**
**Operation ID:** `createServiceDependency`

Create new dependencies between two services.

Business services model capabilities that span multiple technical services and that may be owned by several different teams.

A service can have a maximum of 2,000 dependencies with a depth limit of 100. If the limit is reached, the API will respond with an error.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#business-services)

Scoped OAuth requires: `services.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of service relationships that were successfully associated. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

