# GET /enterprises/{enterprise}/teams/{enterprise-team}/organizations

**Resource:** [enterprise-team-organizations](../resources/enterprise-team-organizations.md)
**Get organization assignments**
**Operation ID:** `enterprise-team-organizations/get-assignments`

Get all organizations assigned to an enterprise team

## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of organizations the team is assigned to |

**Success Response Schema:**

Array of [organization-simple](../schemas/organization-simple/organization-simple.md)

