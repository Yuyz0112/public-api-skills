# GET /user/invites

**Resource:** [User's Invites](../resources/User-s-Invites.md)
**List Invitations**
**Operation ID:** `user'-s-invites-list-invitations`

Lists all invitations associated with my user.

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Invitations response |
| 4XX | List Invitations response failure |

**Success Response Schema:**

[iam_schemas-collection_invite_response](../schemas/iam/iam-schemas-collection-invite-response.md)

## Security

- **api_email**
- **api_key**
