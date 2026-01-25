# GET /orgs/{org}/copilot/billing

**Resource:** [copilot](../resources/copilot.md)
**Get Copilot seat information and settings for an organization**
**Operation ID:** `copilot/get-copilot-organization-details`

> [!NOTE]
> This endpoint is in public preview and is subject to change.

Gets information about an organization's Copilot subscription, including seat breakdown
and feature policies. To configure these settings, go to your organization's settings on GitHub.com.
For more information, see "[Managing policies for Copilot in your organization](https://docs.github.com/copilot/managing-copilot/managing-policies-for-copilot-business-in-your-organization)."

Only organization owners can view details about the organization's Copilot Business or Copilot Enterprise subscription.

OAuth app tokens and personal access tokens (classic) need either the `manage_billing:copilot` or `read:org` scopes to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | There is a problem with your account's associated payment method. |
| 500 | (reference) |

**Success Response Schema:**

[copilot-organization-details](../schemas/copilot-organization-details/copilot-organization-details.md)

