# GET /escalation_policies

**Resource:** [Escalation Policies](../resources/Escalation-Policies.md)
**List escalation policies**
**Operation ID:** `listEscalationPolicies`

List all of the existing escalation policies.

Escalation policies define which user should be alerted at which time.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#escalation-policies)

Scoped OAuth requires: `escalation_policies.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | A paginated array of escalation policy objects. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

