# GET /services/{id}/rules

**Resource:** [Services](../resources/Services.md)
**List Service's Event Rules**
**Operation ID:** `listServiceEventRules`

List Event Rules on a Service.
<!-- theme: warning -->
> ### End-of-life
> Rulesets and Event Rules will end-of-life soon. We highly recommend that you [migrate to Event Orchestration](https://support.pagerduty.com/docs/migrate-to-event-orchestration) as soon as possible so you can take advantage of the new functionality, such as improved UI, rule creation, APIs and Terraform support, advanced conditions, and rule nesting.

Scoped OAuth requires: `services.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of Event Rule objects. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

