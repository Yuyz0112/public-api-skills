# GET /orgs/{org}/members/{username}/copilot

**Resource:** [copilot](../resources/copilot.md)
**Get Copilot seat assignment details for a user**
**Operation ID:** `copilot/get-copilot-seat-details-for-user`

> [!NOTE]
> This endpoint is in public preview and is subject to change.

Gets the GitHub Copilot seat details for a member of an organization who currently has access to GitHub Copilot.

The seat object contains information about the user's most recent Copilot activity. Users must have telemetry enabled in their IDE for Copilot in the IDE activity to be reflected in `last_activity_at`.
For more information about activity data, see [Metrics data properties for GitHub Copilot](https://docs.github.com/copilot/reference/metrics-data).

Only organization owners can view Copilot seat assignment details for members of their organization.

OAuth app tokens and personal access tokens (classic) need either the `manage_billing:copilot` or `read:org` scopes to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The user's GitHub Copilot seat details, including usage. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | Copilot Business or Enterprise is not enabled for this organization or the user has a pending organization invitation. |
| 500 | (reference) |

**Success Response Schema:**

[copilot-seat-details](../schemas/copilot-seat-details/copilot-seat-details.md)

