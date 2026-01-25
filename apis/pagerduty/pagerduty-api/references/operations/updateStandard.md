# PUT /standards/{id}

**Resource:** [Standards](../resources/Standards.md)
**Update a standard**
**Operation ID:** `updateStandard`

Updates a standard

Scoped OAuth requires: `standards.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

**Success Response Schema:**

[Standard](../schemas/Standard/Standard.md)

