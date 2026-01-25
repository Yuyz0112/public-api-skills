# Rulesets

Rulesets allow you to route events to an endpoint and create collections of Event Rules, which define sets of actions to take based on event content.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rulesets` | List Rulesets | [View](../operations/listRulesets.md) |
| POST | `/rulesets` | Create a Ruleset | [View](../operations/createRuleset.md) |
| GET | `/rulesets/{id}` | Get a Ruleset | [View](../operations/getRuleset.md) |
| PUT | `/rulesets/{id}` | Update a Ruleset | [View](../operations/updateRuleset.md) |
| DELETE | `/rulesets/{id}` | Delete a Ruleset | [View](../operations/deleteRuleset.md) |
| GET | `/rulesets/{id}/rules` | List Event Rules | [View](../operations/listRulesetEventRules.md) |
| POST | `/rulesets/{id}/rules` | Create an Event Rule | [View](../operations/createRulesetEventRule.md) |
| GET | `/rulesets/{id}/rules/{rule_id}` | Get an Event Rule | [View](../operations/getRulesetEventRule.md) |
| PUT | `/rulesets/{id}/rules/{rule_id}` | Update an Event Rule | [View](../operations/updateRulesetEventRule.md) |
| DELETE | `/rulesets/{id}/rules/{rule_id}` | Delete an Event Rule | [View](../operations/deleteRulesetEventRule.md) |
