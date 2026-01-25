# GET /user/repos

**Resource:** [repos](../resources/repos.md)
**List repositories for the authenticated user**
**Operation ID:** `repos/list-for-authenticated-user`

Lists repositories that the authenticated user has explicit permission (`:read`, `:write`, or `:admin`) to access.

The authenticated user has explicit permission to access repositories they own, repositories where they are a collaborator, and repositories that they can access through an organization membership.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `visibility` | query | enum: all, public, private | No | Limit results to repositories with the specified visibility. |
| `affiliation` | query | string | No | Comma-separated list of values. Can include:  
 * `owner`: Repositories that are owned by the authenticated user.  
 * `collaborator`: Repositories that the user has been added to as a collaborator.  
 * `organization_member`: Repositories that the user has access to through being a member of an organization. This includes every repository on every team that the user is on. |
| `type` | query | enum: all, owner, public... | No | Limit results to repositories of the specified type. Will cause a `422` error if used in the same request as **visibility** or **affiliation**. |
| `sort` | query | enum: created, updated, pushed... | No | The property to sort the results by. |
| `direction` | query | enum: asc, desc | No | The order to sort by. Default: `asc` when using `full_name`, otherwise `desc`. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

Array of [repository](../schemas/repository/repository.md)

