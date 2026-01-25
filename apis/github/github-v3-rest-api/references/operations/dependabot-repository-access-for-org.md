# GET /organizations/{org}/dependabot/repository-access

**Resource:** [dependabot](../resources/dependabot.md)
**Lists the repositories Dependabot can access in an organization**
**Operation ID:** `dependabot/repository-access-for-org`

Lists repositories that organization admins have allowed Dependabot to access when updating dependencies.
> [!NOTE]
>    This operation supports both server-to-server and user-to-server access.
Unauthorized users will not see the existence of this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | The page number of results to fetch. |
| `per_page` | query | integer | No | Number of results per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[dependabot-repository-access-details](../schemas/dependabot-repository-access-details/dependabot-repository-access-details.md)

