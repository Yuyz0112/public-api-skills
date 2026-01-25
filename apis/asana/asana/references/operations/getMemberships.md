# GET /memberships

**Resource:** [Memberships](../resources/Memberships.md)
**Get multiple memberships**
**Operation ID:** `getMemberships`

Returns compact `goal_membership`, `project_membership`, `portfolio_membership`, or `custom_field_membership` records. The possible types for `parent` in this request are `goal`, `project`, `portfolio`, or `custom_field`. An additional member (user GID or team GID) can be passed in to filter to a specific membership.

Alternatively, when `parent` is absent, you can use the `member` and `resource_subtype` parameters together to fetch all memberships of a specific type for a given member. For example, passing `member` as a team GID and `resource_subtype` as `project_membership` will return all project memberships for that team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `parent` | query | string | No | Globally unique identifier for `goal`, `project`, `portfolio`, or `custom_field`. This parameter is optional when `resource_subtype` is provided along with `member`. |
| `member` | query | string | No | Globally unique identifier for `team` or `user`. When used with `resource_subtype` and without `parent`, returns all memberships of the specified subtype for this member. |
| `resource_subtype` | query | enum: project_membership | No | The type of membership to return. Required when `parent` is absent. Currently supported value is `project_membership` (when `member` is a team GID, returns all project memberships for that team). |
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the requested membership. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
