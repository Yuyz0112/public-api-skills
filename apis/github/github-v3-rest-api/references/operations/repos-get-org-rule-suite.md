# GET /orgs/{org}/rulesets/rule-suites/{rule_suite_id}

**Resource:** [repos](../resources/repos.md)
**Get an organization rule suite**
**Operation ID:** `repos/get-org-rule-suite`

Gets information about a suite of rule evaluations from within an organization.
For more information, see "[Managing rulesets for repositories in your organization](https://docs.github.com/organizations/managing-organization-settings/managing-rulesets-for-repositories-in-your-organization#viewing-insights-for-rulesets)."

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[rule-suite](../schemas/rule-suite/rule-suite.md)

