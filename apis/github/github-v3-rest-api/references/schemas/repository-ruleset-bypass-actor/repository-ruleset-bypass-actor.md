# repository-ruleset-bypass-actor

An actor that can bypass rules in a ruleset

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actor_id` | integer | No | The ID of the actor that can bypass a ruleset. Required for `Integration`, `RepositoryRole`, and `Team` actor types. If `actor_type` is `OrganizationAdmin`, `actor_id` is ignored. If `actor_type` is `DeployKey`, this should be null. `OrganizationAdmin` is not applicable for personal repositories. |
| `actor_type` | enum: Integration, OrganizationAdmin, RepositoryRole... | Yes | The type of actor that can bypass a ruleset. |
| `bypass_mode` | enum: always, pull_request, exempt | No | When the specified actor can bypass the ruleset. `pull_request` means that an actor can only bypass rules on pull requests. `pull_request` is not applicable for the `DeployKey` actor type. Also, `pull_request` is only applicable to branch rulesets. When `bypass_mode` is `exempt`, rules will not be run for that actor and a bypass audit entry will not be created. |

