# DELETE /services/{id}/rules/{rule_id}

**Resource:** [Services](../resources/Services.md)
**Delete an Event Rule from a Service**
**Operation ID:** `deleteServiceEventRule`

Delete an Event Rule from a Service.
<!-- theme: warning -->
> ### End-of-life
> Rulesets and Event Rules will end-of-life soon. We highly recommend that you [migrate to Event Orchestration](https://support.pagerduty.com/docs/migrate-to-event-orchestration) as soon as possible so you can take advantage of the new functionality, such as improved UI, rule creation, APIs and Terraform support, advanced conditions, and rule nesting.

Scoped OAuth requires: `services.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The Event Rule was deleted successfully. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |
| 409 | (reference) |

