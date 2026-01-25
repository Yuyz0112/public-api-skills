# GET /repos/{owner}/{repo}/rules/branches/{branch}

**Resource:** [repos](../resources/repos.md)
**Get rules for a branch**
**Operation ID:** `repos/get-branch-rules`

Returns all active rules that apply to the specified branch. The branch does not need to exist; rules that would apply
to a branch with that name will be returned. All active rules that apply will be returned, regardless of the level
at which they are configured (e.g. repository or organization). Rules in rulesets with "evaluate" or "disabled"
enforcement statuses are not returned.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [repository-rule-detailed](../schemas/repository-rule-detailed/repository-rule-detailed.md)

