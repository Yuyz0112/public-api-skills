# POST /goals/{goal_gid}/addSupportingRelationship

**Resource:** [Goal relationships](../resources/Goal-relationships.md)
**Add a supporting goal relationship**
**Operation ID:** `addSupportingRelationship`

Creates a goal relationship by adding a supporting resource to a given goal.

Returns the newly created goal relationship record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The supporting resource to be added to the goal

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully created the goal relationship. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
