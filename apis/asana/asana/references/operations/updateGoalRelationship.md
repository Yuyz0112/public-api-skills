# PUT /goal_relationships/{goal_relationship_gid}

**Resource:** [Goal relationships](../resources/Goal-relationships.md)
**Update a goal relationship**
**Operation ID:** `updateGoalRelationship`

An existing goal relationship can be updated by making a PUT request on the URL for
that goal relationship. Only the fields provided in the `data` block will be updated;
any unspecified fields will remain unchanged.

Returns the complete updated goal relationship record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The updated fields for the goal relationship.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the goal relationship. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
