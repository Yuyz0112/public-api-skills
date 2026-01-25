# PUT /memberships/{membership_id}

**Resource:** [User's Account Memberships](../resources/User-s-Account-Memberships.md)
**Update Membership**
**Operation ID:** `user'-s-account-memberships-update-membership`

Accept or reject this account invitation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `membership_id` | path | iam_membership_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Membership response |
| 4XX | Update Membership response failure |

**Success Response Schema:**

[iam_single_membership_response_with_policies](../schemas/iam/iam-single-membership-response-with-policies.md)

## Security

- **api_email**
- **api_key**
