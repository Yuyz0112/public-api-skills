# GET /users/{username}/repos

**Resource:** [repos](../resources/repos.md)
**List repositories for a user**
**Operation ID:** `repos/list-for-user`

Lists public repositories for the specified user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `type` | query | enum: all, owner, member | No | Limit results to repositories of the specified type. |
| `sort` | query | enum: created, updated, pushed... | No | The property to sort the results by. |
| `direction` | query | enum: asc, desc | No | The order to sort by. Default: `asc` when using `full_name`, otherwise `desc`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [minimal-repository](../schemas/minimal-repository/minimal-repository.md)

