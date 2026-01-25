# GET /advisories/{ghsa_id}

**Resource:** [security-advisories](../resources/security-advisories.md)
**Get a global security advisory**
**Operation ID:** `security-advisories/get-global-advisory`

Gets a global security advisory using its GitHub Security Advisory (GHSA) identifier.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[global-advisory](../schemas/global-advisory/global-advisory.md)

