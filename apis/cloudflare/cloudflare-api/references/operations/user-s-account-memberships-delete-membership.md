# DELETE /memberships/{membership_id}

**Resource:** [User's Account Memberships](../resources/User-s-Account-Memberships.md)
**Delete Membership**
**Operation ID:** `user'-s-account-memberships-delete-membership`

Remove the associated member from an account.

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
| 200 | Delete Membership response |
| 4XX | Delete Membership response failure |

## Security

- **api_email**
- **api_key**
