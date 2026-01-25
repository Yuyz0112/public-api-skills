# GET /escalation_policies/{id}

**Resource:** [Escalation Policies](../resources/Escalation-Policies.md)
**Get an escalation policy**
**Operation ID:** `getEscalationPolicy`

Get information about an existing escalation policy and its rules.

Escalation policies define which user should be alerted at which time.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#escalation-policies)

Scoped OAuth requires: `escalation_policies.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | The escalation policy object. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

