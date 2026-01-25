# POST /2010-04-01/Accounts/{AccountSid}/Keys/{Sid}.json

**Resource:** [Api20100401Key](../resources/Api20100401Key.md)
**Operation ID:** `UpdateKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Key resources to update. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Key resource to update. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.key](../schemas/api-v2010-account-key/api-v2010-account-key.md)

## Security

- **accountSid_authToken**
