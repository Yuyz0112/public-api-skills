# GET /memberships/{membership_id}

**Resource:** [User's Account Memberships](../resources/User-s-Account-Memberships.md)
**Membership Details**
**Operation ID:** `user'-s-account-memberships-membership-details`

Get a specific membership.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `membership_id` | path | iam_membership_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Membership Details response |
| 4XX | Membership Details response failure |

**Success Response Schema:**

[iam_single_membership_response_with_policies](../schemas/iam/iam-single-membership-response-with-policies.md)

## Security

- **api_email**
- **api_key**
