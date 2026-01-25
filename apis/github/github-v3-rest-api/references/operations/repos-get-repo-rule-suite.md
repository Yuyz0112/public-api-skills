# GET /repos/{owner}/{repo}/rulesets/rule-suites/{rule_suite_id}

**Resource:** [repos](../resources/repos.md)
**Get a repository rule suite**
**Operation ID:** `repos/get-repo-rule-suite`

Gets information about a suite of rule evaluations from within a repository.
For more information, see "[Managing rulesets for a repository](https://docs.github.com/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/managing-rulesets-for-a-repository#viewing-insights-for-rulesets)."

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[rule-suite](../schemas/rule-suite/rule-suite.md)

