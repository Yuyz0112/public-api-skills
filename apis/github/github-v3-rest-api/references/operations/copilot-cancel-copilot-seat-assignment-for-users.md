# DELETE /orgs/{org}/copilot/billing/selected_users

**Resource:** [copilot](../resources/copilot.md)
**Remove users from the Copilot subscription for an organization**
**Operation ID:** `copilot/cancel-copilot-seat-assignment-for-users`

> [!NOTE]
> This endpoint is in public preview and is subject to change.

Sets seats for all users specified to "pending cancellation".
This will cause the specified users to lose access to GitHub Copilot at the end of the current billing cycle unless they retain access through team membership.
For more information about disabling access to Copilot, see "[Revoking access to Copilot for members of your organization](https://docs.github.com/copilot/managing-copilot/managing-github-copilot-in-your-organization/managing-access-to-github-copilot-in-your-organization/revoking-access-to-copilot-for-members-of-your-organization)."

Only organization owners can cancel Copilot seats for their organization members.

The response contains the total number of seats set to "pending cancellation".

OAuth app tokens and personal access tokens (classic) need either the `manage_billing:copilot` or `admin:org` scopes to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | Copilot Business or Enterprise is not enabled for this organization, billing has not been set up for this organization, a public code suggestions policy has not been set for this organization, the seat management setting is set to enable Copilot for all users or is unconfigured, or a user's seat cannot be cancelled because it was assigned to them via a team. |
| 500 | (reference) |

