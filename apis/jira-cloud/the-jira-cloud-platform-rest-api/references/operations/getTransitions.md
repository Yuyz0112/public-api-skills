# GET /rest/api/3/issue/{issueIdOrKey}/transitions

**Resource:** [Issues](../resources/Issues.md)
**Get transitions**
**Operation ID:** `getTransitions`

Returns either all transitions or a transition that can be performed by the user on an issue, based on the issue's status.

Note, if a request is made for a transition that does not exist or cannot be performed on the issue, given its status, the response will return any empty transitions list.

This operation can be accessed anonymously.

**[Permissions](#permissions) required: A list or transition is returned only when the user has:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.

However, if the user does not have the *Transition issues* [ project permission](https://confluence.atlassian.com/x/yodKLg) the response will not list any transitions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `issueIdOrKey` | path | string | Yes | The ID or key of the issue. |
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about transitions in the response. This parameter accepts `transitions.fields`, which returns information about the fields in the transition screen for each transition. Fields hidden from the screen are not returned. Use this information to populate the `fields` and `update` fields in [Transition issue](#api-rest-api-3-issue-issueIdOrKey-transitions-post). |
| `transitionId` | query | string | No | The ID of the transition. |
| `skipRemoteOnlyCondition` | query | boolean | No | Whether transitions with the condition *Hide From User Condition* are included in the response. Available to Connect and Forge app users with *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) and Forge apps acting on behalf of users with *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). |
| `includeUnavailableTransitions` | query | boolean | No | Whether details of transitions that fail a condition are included in the response |
| `sortByOpsBarAndStatus` | query | boolean | No | Whether the transitions are sorted by ops-bar sequence value first then category order (Todo, In Progress, Done) or only by ops-bar sequence value. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the issue is not found or the user does not have permission to view it. |

**Success Response Schema:**

[Transitions](../schemas/Transitions/Transitions.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
