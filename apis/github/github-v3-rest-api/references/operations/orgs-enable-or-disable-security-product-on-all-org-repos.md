# POST /orgs/{org}/{security_product}/{enablement}

**Resource:** [orgs](../resources/orgs.md)
**Enable or disable a security feature for an organization**
**Operation ID:** `orgs/enable-or-disable-security-product-on-all-org-repos`
⚠️ **Deprecated**

> [!WARNING]
> **Closing down notice:** The ability to enable or disable a security feature for all eligible repositories in an organization is closing down. Please use [code security configurations](https://docs.github.com/rest/code-security/configurations) instead. For more information, see the [changelog](https://github.blog/changelog/2024-07-22-deprecation-of-api-endpoint-to-enable-or-disable-a-security-feature-for-an-organization/).

Enables or disables the specified security feature for all eligible repositories in an organization. For more information, see "[Managing security managers in your organization](https://docs.github.com/organizations/managing-peoples-access-to-your-organization-with-roles/managing-security-managers-in-your-organization)."

The authenticated user must be an organization owner or be member of a team with the security manager role to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:org`, `write:org`, or `repo` scopes to use this endpoint.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Action started |
| 422 | The action could not be taken due to an in progress enablement, or a policy is preventing enablement |

