# POST /escalation_policies

**Resource:** [Escalation Policies](../resources/Escalation-Policies.md)
**Create an escalation policy**
**Operation ID:** `createEscalationPolicy`

Creates a new escalation policy. At least one escalation rule must be provided.

Escalation policies define which user should be alerted at which time.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#escalation-policies)

Scoped OAuth requires: `escalation_policies.write`


## Request Body

The escalation policy to be created.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | The escalation policy that was created. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

