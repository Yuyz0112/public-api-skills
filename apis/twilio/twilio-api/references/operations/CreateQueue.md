# POST /2010-04-01/Accounts/{AccountSid}/Queues.json

**Resource:** [Api20100401Queue](../resources/Api20100401Queue.md)
**Create a queue**
**Operation ID:** `CreateQueue`

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

[api.v2010.account.queue](../schemas/api-v2010-account-queue/api-v2010-account-queue.md)

## Security

- **accountSid_authToken**
