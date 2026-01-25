# workers-observability_query

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | string | Yes |  |
| `description` | string | Yes |  |
| `environmentId` | string | Yes | ID of your environment |
| `generated` | boolean | Yes | Flag for alerts automatically created |
| `id` | string | Yes | ID of the query |
| `name` | string | Yes | Query name |
| `parameters` | object | Yes |  |
| `updated` | string | Yes |  |
| `userId` | string | Yes |  |
| `workspaceId` | string | Yes | ID of your workspace |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `calculations` | object[] | No | Create Calculations to compute as part of the query. |
| `datasets` | string[] | No | Set the Datasets to query. Leave it empty to query all the datasets. |
| `filterCombination` | enum: and, or, AND... | No | Set a Flag to describe how to combine the filters on the query. |
| `filters` | object[] | No | Configure the Filters to apply to the query. |
| `groupBys` | object[] | No | Define how to group the results of the query. |
| `havings` | object[] | No | Configure the Having clauses that filter on calculations in the query result. |
| `limit` | integer | No | Set a limit on the number of results / records returned by the query |
| `needle` | object | No | Define an expression to search using full-text search. |
| `orderBy` | object | No | Configure the order of the results returned by the query. |

#### `parameters.calculations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `alias` | string | No |  |
| `key` | string | No |  |
| `keyType` | enum: string, number, boolean | No |  |
| `operator` | enum: uniq, count, max... | Yes |  |

#### `parameters.filters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes |  |
| `operation` | enum: includes, not_includes, starts_with... | Yes |  |
| `type` | enum: string, number, boolean | Yes |  |
| `value` | any | No |  |

#### `parameters.groupBys`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: string, number, boolean | Yes |  |
| `value` | string | Yes |  |

#### `parameters.havings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `key` | string | Yes |  |
| `operation` | enum: eq, neq, gt... | Yes |  |
| `value` | number | Yes |  |

#### `parameters.needle`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `isRegex` | boolean | No |  |
| `matchCase` | boolean | No |  |
| `value` | any | Yes |  |

#### `parameters.orderBy`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `order` | enum: asc, desc | No | Set the order of the results |
| `value` | string | Yes | Configure which Calculation to order the results by. |

