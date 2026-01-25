# POST /2010-04-01/Accounts/{AccountSid}/Usage/Triggers/{Sid}.json

**Resource:** [Api20100401Trigger](../resources/Api20100401Trigger.md)
**Update an instance of a usage trigger**
**Operation ID:** `UpdateUsageTrigger`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the UsageTrigger resources to update. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the UsageTrigger resource to update. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.usage.usage_trigger](../schemas/api-v2010-account-usage-usage/api-v2010-account-usage-usage-trigger.md)

## Security

- **accountSid_authToken**
