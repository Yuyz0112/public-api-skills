# Automation Actions

Automation Actions invoke jobs that are staged in Runbook Automation or Process Automation.


## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/automation_actions/actions` | List Automation Actions | [View](../operations/getAllAutomationActions.md) |
| POST | `/automation_actions/actions` | Create an Automation Action | [View](../operations/createAutomationAction.md) |
| GET | `/automation_actions/actions/{id}` | Get an Automation Action | [View](../operations/getAutomationAction.md) |
| PUT | `/automation_actions/actions/{id}` | Update an Automation Action | [View](../operations/updateAutomationAction.md) |
| DELETE | `/automation_actions/actions/{id}` | Delete an Automation Action | [View](../operations/deleteAutomationAction.md) |
| POST | `/automation_actions/actions/{id}/invocations` | Create an Invocation | [View](../operations/createAutomationActionInvocation.md) |
| GET | `/automation_actions/actions/{id}/services` | Get all service references associated with an Automation Action | [View](../operations/getAutomationActionsActionServiceAssociations.md) |
| POST | `/automation_actions/actions/{id}/services` | Associate an Automation Action with a service | [View](../operations/createAutomationActionServiceAssocation.md) |
| GET | `/automation_actions/actions/{id}/services/{service_id}` | Get the details of an Automation Action / service relation | [View](../operations/getAutomationActionsActionServiceAssociation.md) |
| DELETE | `/automation_actions/actions/{id}/services/{service_id}` | Disassociate an Automation Action from a service | [View](../operations/deleteAutomationActionServiceAssociation.md) |
| GET | `/automation_actions/actions/{id}/teams` | Get all team references associated with an Automation Action | [View](../operations/getAutomationActionsActionTeamAssociations.md) |
| POST | `/automation_actions/actions/{id}/teams` | Associate an Automation Action with a team | [View](../operations/createAutomationActionTeamAssociation.md) |
| GET | `/automation_actions/actions/{id}/teams/{team_id}` | Get the details of an Automation Action / team relation | [View](../operations/getAutomationActionsActionTeamAssociation.md) |
| DELETE | `/automation_actions/actions/{id}/teams/{team_id}` | Disassociate an Automation Action from a team | [View](../operations/deleteAutomationActionTeamAssociation.md) |
| GET | `/automation_actions/invocations` | List Invocations | [View](../operations/listAutomationActionInvocations.md) |
| GET | `/automation_actions/invocations/{id}` | Get an Invocation | [View](../operations/getAutomationActionsInvocation.md) |
| GET | `/automation_actions/runners` | List Automation Action runners | [View](../operations/getAutomationActionsRunners.md) |
| POST | `/automation_actions/runners` | Create an Automation Action runner. | [View](../operations/createAutomationActionsRunner.md) |
| GET | `/automation_actions/runners/{id}` | Get an Automation Action runner | [View](../operations/getAutomationActionsRunner.md) |
| PUT | `/automation_actions/runners/{id}` | Update an Automation Action runner | [View](../operations/updateAutomationActionsRunner.md) |
| DELETE | `/automation_actions/runners/{id}` | Delete an Automation Action runner | [View](../operations/deleteAutomationActionsRunner.md) |
| GET | `/automation_actions/runners/{id}/teams` | Get all team references associated with a runner | [View](../operations/getAutomationActionsRunnerTeamAssociations.md) |
| POST | `/automation_actions/runners/{id}/teams` | Associate a runner with a team | [View](../operations/createAutomationActionsRunnerTeamAssociation.md) |
| GET | `/automation_actions/runners/{id}/teams/{team_id}` | Get the details of a runner / team relation | [View](../operations/getAutomationActionsRunnerTeamAssociation.md) |
| DELETE | `/automation_actions/runners/{id}/teams/{team_id}` | Disassociate a runner from a team | [View](../operations/deleteAutomationActionsRunnerTeamAssociation.md) |
