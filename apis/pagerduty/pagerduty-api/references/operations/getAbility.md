# GET /abilities/{id}

**Resource:** [Abilities](../resources/Abilities.md)
**Test an ability**
**Operation ID:** `getAbility`

Test whether your account has a given ability.

"Abilities" describes your account's capabilities by feature name. For example `"teams"`.

An ability may be available to your account based on things like your pricing plan or account state.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#abilities)

Scoped OAuth requires: `abilities.read`


## Responses

| Status | Description |
|--------|-------------|
| 204 | The account has the requested ability. |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 429 | (reference) |

