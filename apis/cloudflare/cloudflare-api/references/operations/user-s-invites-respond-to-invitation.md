# PATCH /user/invites/{invite_id}

**Resource:** [User's Invites](../resources/User-s-Invites.md)
**Respond to Invitation**
**Operation ID:** `user'-s-invites-respond-to-invitation`

Responds to an invitation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `invite_id` | path | iam_invite_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Respond to Invitation response |
| 4XX | Respond to Invitation response failure |

**Success Response Schema:**

[iam_single_invite_response](../schemas/iam/iam-single-invite-response.md)

## Security

- **api_email**
- **api_key**
