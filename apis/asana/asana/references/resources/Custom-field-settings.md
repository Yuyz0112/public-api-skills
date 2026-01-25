# Custom field settings

Custom fields are attached to a particular project with the custom field settings resource. This resource both represents the many-to-many join of the custom field and project as well as stores information that is relevant to that particular pairing. For instance, the `is_important` property determines some possible application-specific handling of that custom field.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/projects/{project_gid}/custom_field_settings` | Get a project's custom fields | [View](../operations/getCustomFieldSettingsForProject.md) |
| GET | `/portfolios/{portfolio_gid}/custom_field_settings` | Get a portfolio's custom fields | [View](../operations/getCustomFieldSettingsForPortfolio.md) |
| GET | `/goals/{goal_gid}/custom_field_settings` | Get a goal's custom fields | [View](../operations/getCustomFieldSettingsForGoal.md) |
| GET | `/teams/{team_gid}/custom_field_settings` | Get a team's custom fields | [View](../operations/getCustomFieldSettingsForTeam.md) |
