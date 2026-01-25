# GET /abilities

**Resource:** [Abilities](../resources/Abilities.md)
**List abilities**
**Operation ID:** `listAbilities`

List all of your account's abilities, by name.

"Abilities" describes your account's capabilities by feature name. For example `"teams"`.

An ability may be available to your account based on things like your pricing plan or account state.

For more information see the [API Concepts Document](../../api-reference/a47605517c19a-api-concepts#abilities)

Scoped OAuth requires: `abilities.read`


## Responses

| Status | Description |
|--------|-------------|
| 200 | An array of ability names. |
| 401 | (reference) |
| 403 | (reference) |
| 429 | (reference) |

