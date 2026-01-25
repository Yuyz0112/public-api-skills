# POST /rule_triggers/{rule_trigger_gid}/run

**Resource:** [Rules](../resources/Rules.md)
**Trigger a rule**
**Operation ID:** `triggerRule`

Trigger a rule which uses an ["incoming web request"](/docs/incoming-web-requests) trigger.

## Request Body

A dictionary of variables accessible from within the rule.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully triggered a rule. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
