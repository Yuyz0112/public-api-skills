# POST /enterprises/{enterprise}/teams/{enterprise-team}/organizations/add

**Resource:** [enterprise-team-organizations](../resources/enterprise-team-organizations.md)
**Add organization assignments**
**Operation ID:** `enterprise-team-organizations/bulk-add`

Assign an enterprise team to multiple organizations.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully assigned the enterprise team to organizations. |

**Success Response Schema:**

Array of [organization-simple](../schemas/organization-simple/organization-simple.md)

