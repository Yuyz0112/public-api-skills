# GET /repos/{owner}/{repo}/rulesets/rule-suites

**Resource:** [repos](../resources/repos.md)
**List repository rule suites**
**Operation ID:** `repos/get-repo-rule-suites`

Lists suites of rule evaluations at the repository level.
For more information, see "[Managing rulesets for a repository](https://docs.github.com/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/managing-rulesets-for-a-repository#viewing-insights-for-rulesets)."

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[rule-suites](../schemas/rule-suites/rule-suites.md)

