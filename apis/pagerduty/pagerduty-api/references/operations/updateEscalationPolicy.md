# PUT /escalation_policies/{id}

**Resource:** [Escalation Policies](../resources/Escalation-Policies.md)
**Update an escalation policy**
**Operation ID:** `updateEscalationPolicy`

Updates an existing escalation policy and rules.

Escalation policies define which user should be alerted at which time.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#escalation-policies)

Scoped OAuth requires: `escalation_policies.write`


## Request Body

The escalation policy to be updated.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The escalation policy that was updated. |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

