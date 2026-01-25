# POST /services/{id}/rules/convert

**Resource:** [Services](../resources/Services.md)
**Convert a Service's Event Rules into Event Orchestration Rules**
**Operation ID:** `convertServiceEventRulesToEventOrchestration`

Convert this Service's Event Rules into functionally equivalent Event Orchestration Rules.

Sending a request to this API endpoint has several effects:

1. Automatically creates Event Orchestration Rules for this Service that will behave identically as this Service's currently configured Event Rules.
2. Makes all existing Event Rules for this Service read-only. All future updates need to be made via the newly created Event Orchestration rules.

Sending a request to this API endpoint will **not** change how future events will be processed. If past events for this Service have been evaluated via Event Rules then new events sent to this Service will also continue to be evaluated via the (now read-only) Event Rules. To change this Service so that new events start being evaluated via the newly created Event Orchestration Rules use the [Update the Service Orchestration active status for a Service API](https://developer.pagerduty.com/api-reference/855659be83d9e-update-the-service-orchestration-active-status-for-a-service).

> ### End-of-life
> Event Rules will end-of-life soon. We highly recommend that you use this API to [migrate to Event Orchestration](https://support.pagerduty.com/docs/migrate-to-event-orchestration) as soon as possible so you can take advantage of the new functionality, such as improved UI, rule creation, APIs and Terraform support, advanced conditions, and rule nesting.

Scoped OAuth requires: `services.write`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The Event Orchestration Rules were successfully created |
| 400 | Could not create equivalent Event Orchestration Rules based on the Service's current Event Rules |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |
| 409 | (reference) |

