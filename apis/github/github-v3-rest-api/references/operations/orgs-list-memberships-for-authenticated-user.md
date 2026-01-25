# GET /user/memberships/orgs

**Resource:** [orgs](../resources/orgs.md)
**List organization memberships for the authenticated user**
**Operation ID:** `orgs/list-memberships-for-authenticated-user`

Lists all of the authenticated user's organization memberships.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `state` | query | enum: active, pending | No | Indicates the state of the memberships to return. If not specified, the API returns both active and pending memberships. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [org-membership](../schemas/org-membership/org-membership.md)

