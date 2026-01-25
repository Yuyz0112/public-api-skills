# GET /event_orchestrations/{id}/enablements

**Resource:** [Event Orchestrations](../resources/Event-Orchestrations.md)
**List Enablements for an Event Orchestration**
**Operation ID:** `listEventOrchestrationFeatureEnablements`

<!-- theme: warning -->
> ### Limited GA
> This feature is in Limited General Availability for some customers with the PagerDuty AIOps add-on. Please contact your account team or Support to request access.

List all feature enablement settings for an Event Orchestration. Currently, only the `aiops` enablement is supported.

For any account with the AIOps product addon, every Event Orchestration will have AIOps features enabled by default.

**Warning conditions**:
- If the account is not entitled to use AIOps features, a warning will be returned alongside the enablement data.

Scoped OAuth requires: `event_orchestrations.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The list of feature enablement settings for the Event Orchestation. |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

