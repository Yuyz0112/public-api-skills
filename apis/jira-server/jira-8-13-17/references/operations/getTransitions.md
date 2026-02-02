# GET /issue/{issueIdOrKey}/transitions

**Resource:** [issue](../resources/issue.md)
**Operation ID:** `getTransitions`

Get a list of the transitions possible for this issue by the current user, along with fields that are required and their types.
 <p/>
 Fields will only be returned if <code>expand=transitions.fields</code>.
 <p/>
 The fields in the metadata correspond to the fields in the transition screen for that transition.
 Fields not in the screen will not be in the metadata.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `transitionId` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

