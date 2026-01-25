# GET /standards/scores/{resource_type}/{id}

**Resource:** [Standards](../resources/Standards.md)
**List a resource's standards scores**
**Operation ID:** `listResourceStandards`

List standards applied to a specific resource

Scoped OAuth requires: `standards.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

**Success Response Schema:**

[StandardApplied](../schemas/Standard/StandardApplied.md)

