# DELETE /2010-04-01/Accounts/{AccountSid}/Usage/Triggers/{Sid}.json

**Resource:** [Api20100401Trigger](../resources/Api20100401Trigger.md)
**Operation ID:** `DeleteUsageTrigger`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the UsageTrigger resources to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the UsageTrigger resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
