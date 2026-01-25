# DELETE /orgs/{org}/invitations/{invitation_id}

**Resource:** [orgs](../resources/orgs.md)
**Cancel an organization invitation**
**Operation ID:** `orgs/cancel-invitation`

Cancel an organization invitation. In order to cancel an organization invitation, the authenticated user must be an organization owner.

This endpoint triggers [notifications](https://docs.github.com/github/managing-subscriptions-and-notifications-on-github/about-notifications).

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |
| 422 | (reference) |

