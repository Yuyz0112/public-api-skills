# GET /user/invites/{invite_id}

**Resource:** [User's Invites](../resources/User-s-Invites.md)
**Invitation Details**
**Operation ID:** `user'-s-invites-invitation-details`

Gets the details of an invitation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `invite_id` | path | iam_invite_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Invitation Details response |
| 4XX | Invitation Details response failure |

**Success Response Schema:**

[iam_single_invite_response](../schemas/iam/iam-single-invite-response.md)

## Security

- **api_email**
- **api_key**
