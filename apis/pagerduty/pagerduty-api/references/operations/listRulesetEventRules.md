# GET /rulesets/{id}/rules

**Resource:** [Rulesets](../resources/Rulesets.md)
**List Event Rules**
**Operation ID:** `listRulesetEventRules`

List all Event Rules on a Ruleset.
<!-- theme: warning -->
> ### End-of-life
> Rulesets and Event Rules will end-of-life soon. We highly recommend that you [migrate to Event Orchestration](https://support.pagerduty.com/docs/migrate-to-event-orchestration) as soon as possible so you can take advantage of the new functionality, such as improved UI, rule creation, APIs and Terraform support, advanced conditions, and rule nesting.

Rulesets allow you to route events to an endpoint and create collections of Event Rules, which define sets of actions to take based on event content.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#rulesets)

Note: Create and Update on rules will accept 'description' or 'summary' interchangeably as an extraction action target. Get and List on rules will always return 'summary' as the target. If you are expecting 'description' please change your automation code to expect 'summary' instead.

Scoped OAuth requires: `event_rules.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of Event Rule objects. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

