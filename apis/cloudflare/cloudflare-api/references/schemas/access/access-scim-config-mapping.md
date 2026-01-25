# access_scim_config_mapping

Transformations and filters applied to resources before they are provisioned in the remote SCIM service.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Whether or not this mapping is enabled. |
| `filter` | string | No | A [SCIM filter expression](https://datatracker.ietf.org/doc/html/rfc7644#section-3.4.2.2) that matches resources that should be provisioned to this application. |
| `operations` | object | No | Whether or not this mapping applies to creates, updates, or deletes. |
| `schema` | string | Yes | Which SCIM resource type this mapping applies to. |
| `strictness` | enum: strict, passthrough | No | The level of adherence to outbound resource schemas when provisioning to this mapping. ‘Strict’ removes unknown values, while ‘passthrough’ passes unknown values to the target. |
| `transform_jsonata` | string | No | A [JSONata](https://jsonata.org/) expression that transforms the resource before provisioning it in the application. |

## Nested Fields

### `operations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `create` | boolean | No | Whether or not this mapping applies to create (POST) operations. |
| `delete` | boolean | No | Whether or not this mapping applies to DELETE operations. |
| `update` | boolean | No | Whether or not this mapping applies to update (PATCH/PUT) operations. |

