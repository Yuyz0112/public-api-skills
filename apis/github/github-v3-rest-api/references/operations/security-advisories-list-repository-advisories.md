# GET /repos/{owner}/{repo}/security-advisories

**Resource:** [security-advisories](../resources/security-advisories.md)
**List repository security advisories**
**Operation ID:** `security-advisories/list-repository-advisories`

Lists security advisories in a repository.

The authenticated user can access unpublished security advisories from a repository if they are a security manager or administrator of that repository, or if they are a collaborator on any security advisory.

OAuth app tokens and personal access tokens (classic) need the `repo` or `repository_advisories:read` scope to to get a published security advisory in a private repository, or any unpublished security advisory that the authenticated user has access to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `sort` | query | enum: created, updated, published | No | The property to sort the results by. |
| `per_page` | query | integer | No | The number of advisories to return per page. For more information, see "[Using pagination in the REST API](https://docs.github.com/rest/using-the-rest-api/using-pagination-in-the-rest-api)." |
| `state` | query | enum: triage, draft, published... | No | Filter by state of the repository advisories. Only advisories of this state will be returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [repository-advisory](../schemas/repository-advisory/repository-advisory.md)

