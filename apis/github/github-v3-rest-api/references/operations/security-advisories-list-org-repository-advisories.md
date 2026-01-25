# GET /orgs/{org}/security-advisories

**Resource:** [security-advisories](../resources/security-advisories.md)
**List repository security advisories for an organization**
**Operation ID:** `security-advisories/list-org-repository-advisories`

Lists repository security advisories for an organization.

The authenticated user must be an owner or security manager for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` or `repository_advisories:write` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sort` | query | enum: created, updated, published | No | The property to sort the results by. |
| `per_page` | query | integer | No | The number of advisories to return per page. For more information, see "[Using pagination in the REST API](https://docs.github.com/rest/using-the-rest-api/using-pagination-in-the-rest-api)." |
| `state` | query | enum: triage, draft, published... | No | Filter by the state of the repository advisories. Only advisories of this state will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [repository-advisory](../schemas/repository-advisory/repository-advisory.md)

