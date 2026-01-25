# GET /rulesets/{id}

**Resource:** [Rulesets](../resources/Rulesets.md)
**Get a Ruleset**
**Operation ID:** `getRuleset`

Get a Ruleset.
<!-- theme: warning -->
> ### End-of-life
> Rulesets and Event Rules will end-of-life soon. We highly recommend that you [migrate to Event Orchestration](https://support.pagerduty.com/docs/migrate-to-event-orchestration) as soon as possible so you can take advantage of the new functionality, such as improved UI, rule creation, APIs and Terraform support, advanced conditions, and rule nesting.

Rulesets allow you to route events to an endpoint and create collections of Event Rules, which define sets of actions to take based on event content.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#rulesets)

Scoped OAuth requires: `event_rules.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The Ruleset object. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

