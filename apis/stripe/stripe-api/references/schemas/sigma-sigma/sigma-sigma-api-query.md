# sigma.sigma_api_query

A saved query object represents a query that can be executed for a run.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `name` | string | Yes | The name of the query. |
| `object` | enum: sigma.sigma_api_query | Yes | String representing the object's type. Objects of the same type share the same value. |
| `sql` | string | Yes | The sql statement for the query. |

