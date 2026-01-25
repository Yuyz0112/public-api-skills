# PUT /services/{id}/rules/{rule_id}

**Resource:** [Services](../resources/Services.md)
**Update an Event Rule on a Service**
**Operation ID:** `updateServiceEventRule`

Update an Event Rule on a Service. Note that the endpoint supports partial updates, so any number of the writable fields can be provided.
<!-- theme: warning -->
> ### End-of-life
> Rulesets and Event Rules will end-of-life soon. We highly recommend that you [migrate to Event Orchestration](https://support.pagerduty.com/docs/migrate-to-event-orchestration) as soon as possible so you can take advantage of the new functionality, such as improved UI, rule creation, APIs and Terraform support, advanced conditions, and rule nesting.

Scoped OAuth requires: `services.write`


## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The Event Rule that was updated. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 405 | (reference) |
| 409 | (reference) |

