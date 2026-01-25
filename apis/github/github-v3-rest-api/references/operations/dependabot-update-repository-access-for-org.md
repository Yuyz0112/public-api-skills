# PATCH /organizations/{org}/dependabot/repository-access

**Resource:** [dependabot](../resources/dependabot.md)
**Updates Dependabot's repository access list for an organization**
**Operation ID:** `dependabot/update-repository-access-for-org`

Updates repositories according to the list of repositories that organization admins have given Dependabot access to when they've updated dependencies.

> [!NOTE]
>    This operation supports both server-to-server and user-to-server access.
Unauthorized users will not see the existence of this endpoint.

**Example request body:**
```json
{
  "repository_ids_to_add": [123, 456],
  "repository_ids_to_remove": [789]
}
```

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 403 | (reference) |
| 404 | (reference) |

