# DELETE /escalation_policies/{id}

**Resource:** [Escalation Policies](../resources/Escalation-Policies.md)
**Delete an escalation policy**
**Operation ID:** `deleteEscalationPolicy`

Deletes an existing escalation policy and rules. The escalation policy must not be in use by any services.

Escalation policies define which user should be alerted at which time.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#escalation-policies)

Scoped OAuth requires: `escalation_policies.write`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The escalation policy was deleted successfully. |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

