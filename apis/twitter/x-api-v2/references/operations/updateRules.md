# POST /2/tweets/search/stream/rules

**Resource:** [Stream](../resources/Stream.md)
**Update stream rules**
**Operation ID:** `updateRules`

Adds or deletes rules from the active rule set for the filtered stream.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dry_run` | query | boolean | No | Dry Run can be used with both the add and delete action, with the expected result given, but without actually taking any action in the system (meaning the end state will always be as it was when the request was submitted). This is particularly useful to validate rule changes. |
| `delete_all` | query | boolean | No | Delete All can be used to delete all of the rules associated this client app, it should be specified with no other parameters. Once deleted, rules cannot be recovered. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AddOrDeleteRulesRequest](../schemas/Add/AddOrDeleteRulesRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[AddOrDeleteRulesResponse](../schemas/Add/AddOrDeleteRulesResponse.md)

## Security

- **BearerToken**
