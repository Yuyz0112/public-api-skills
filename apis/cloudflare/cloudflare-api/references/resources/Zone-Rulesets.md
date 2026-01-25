# Zone Rulesets

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/zones/{zone_id}/rulesets` | List zone rulesets | [View](../operations/listZoneRulesets.md) |
| POST | `/zones/{zone_id}/rulesets` | Create a zone ruleset | [View](../operations/createZoneRuleset.md) |
| GET | `/zones/{zone_id}/rulesets/phases/{ruleset_phase}/entrypoint` | Get a zone entry point ruleset | [View](../operations/getZoneEntrypointRuleset.md) |
| PUT | `/zones/{zone_id}/rulesets/phases/{ruleset_phase}/entrypoint` | Update a zone entry point ruleset | [View](../operations/updateZoneEntrypointRuleset.md) |
| GET | `/zones/{zone_id}/rulesets/phases/{ruleset_phase}/entrypoint/versions` | List a zone entry point ruleset's versions | [View](../operations/listZoneEntrypointRulesetVersions.md) |
| GET | `/zones/{zone_id}/rulesets/phases/{ruleset_phase}/entrypoint/versions/{ruleset_version}` | Get a zone entry point ruleset version | [View](../operations/getZoneEntrypointRulesetVersion.md) |
| GET | `/zones/{zone_id}/rulesets/{ruleset_id}` | Get a zone ruleset | [View](../operations/getZoneRuleset.md) |
| PUT | `/zones/{zone_id}/rulesets/{ruleset_id}` | Update a zone ruleset | [View](../operations/updateZoneRuleset.md) |
| DELETE | `/zones/{zone_id}/rulesets/{ruleset_id}` | Delete a zone ruleset | [View](../operations/deleteZoneRuleset.md) |
| POST | `/zones/{zone_id}/rulesets/{ruleset_id}/rules` | Create a zone ruleset rule | [View](../operations/createZoneRulesetRule.md) |
| DELETE | `/zones/{zone_id}/rulesets/{ruleset_id}/rules/{rule_id}` | Delete a zone ruleset rule | [View](../operations/deleteZoneRulesetRule.md) |
| PATCH | `/zones/{zone_id}/rulesets/{ruleset_id}/rules/{rule_id}` | Update a zone ruleset rule | [View](../operations/updateZoneRulesetRule.md) |
| GET | `/zones/{zone_id}/rulesets/{ruleset_id}/versions` | List a zone ruleset's versions | [View](../operations/listZoneRulesetVersions.md) |
| GET | `/zones/{zone_id}/rulesets/{ruleset_id}/versions/{ruleset_version}` | Get a zone ruleset version | [View](../operations/getZoneRulesetVersion.md) |
| DELETE | `/zones/{zone_id}/rulesets/{ruleset_id}/versions/{ruleset_version}` | Delete a zone ruleset version | [View](../operations/deleteZoneRulesetVersion.md) |
| GET | `/zones/{zone_id}/rulesets/{ruleset_id}/versions/{ruleset_version}/by_tag/{rule_tag}` | List a zone ruleset version's rules by tag | [View](../operations/listZoneRulesetVersionRulesByTag.md) |
