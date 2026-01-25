# GET /orgs/{org}/rulesets/rule-suites

**Resource:** [repos](../resources/repos.md)
**List organization rule suites**
**Operation ID:** `repos/get-org-rule-suites`

Lists suites of rule evaluations at the organization level.
For more information, see "[Managing rulesets for repositories in your organization](https://docs.github.com/organizations/managing-organization-settings/managing-rulesets-for-repositories-in-your-organization#viewing-insights-for-rulesets)."

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[rule-suites](../schemas/rule-suites/rule-suites.md)

