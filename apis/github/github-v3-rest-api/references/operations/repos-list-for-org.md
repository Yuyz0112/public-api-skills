# GET /orgs/{org}/repos

**Resource:** [repos](../resources/repos.md)
**List organization repositories**
**Operation ID:** `repos/list-for-org`

Lists repositories for the specified organization.

> [!NOTE]
> In order to see the `security_and_analysis` block for a repository you must have admin permissions for the repository or be an owner or security manager for the organization that owns the repository. For more information, see "[Managing security managers in your organization](https://docs.github.com/organizations/managing-peoples-access-to-your-organization-with-roles/managing-security-managers-in-your-organization)."

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `type` | query | enum: all, public, private... | No | Specifies the types of repositories you want returned. |
| `sort` | query | enum: created, updated, pushed... | No | The property to sort the results by. |
| `direction` | query | enum: asc, desc | No | The order to sort by. Default: `asc` when using `full_name`, otherwise `desc`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)

