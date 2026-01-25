# POST /2010-04-01/Accounts/{AccountSid}/Usage/Triggers.json

**Resource:** [Api20100401Trigger](../resources/Api20100401Trigger.md)
**Create a new UsageTrigger**
**Operation ID:** `CreateUsageTrigger`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that will create the resource. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[api.v2010.account.usage.usage_trigger](../schemas/api-v2010-account-usage-usage/api-v2010-account-usage-usage-trigger.md)

## Security

- **accountSid_authToken**
