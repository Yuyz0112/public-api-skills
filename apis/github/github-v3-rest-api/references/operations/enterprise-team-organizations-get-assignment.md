# GET /enterprises/{enterprise}/teams/{enterprise-team}/organizations/{org}

**Resource:** [enterprise-team-organizations](../resources/enterprise-team-organizations.md)
**Get organization assignment**
**Operation ID:** `enterprise-team-organizations/get-assignment`

Check if an enterprise team is assigned to an organization

## Responses

| Status | Description |
|--------|-------------|
| 200 | The team is assigned to the organization |
| 404 | The team is not assigned to the organization |

**Success Response Schema:**

[organization-simple](../schemas/organization-simple/organization-simple.md)

