# POST /goals/{goal_gid}/removeSupportingRelationship

**Resource:** [Goal relationships](../resources/Goal-relationships.md)
**Removes a supporting goal relationship**
**Operation ID:** `removeSupportingRelationship`

Removes a goal relationship for a given parent goal.

## Request Body

The supporting resource to be removed from the goal

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully removed the goal relationship. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
