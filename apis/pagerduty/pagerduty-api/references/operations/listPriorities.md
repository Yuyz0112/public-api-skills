# GET /priorities

**Resource:** [Priorities](../resources/Priorities.md)
**List priorities**
**Operation ID:** `listPriorities`

List existing priorities, in order (most to least severe).

A priority is a label representing the importance and impact of an incident.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#priorities)

Scoped OAuth requires: `priorities.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of priorities. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

