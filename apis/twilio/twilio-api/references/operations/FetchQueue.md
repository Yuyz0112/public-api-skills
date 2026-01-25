# GET /2010-04-01/Accounts/{AccountSid}/Queues/{Sid}.json

**Resource:** [Api20100401Queue](../resources/Api20100401Queue.md)
**Fetch an instance of a queue identified by the QueueSid**
**Operation ID:** `FetchQueue`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Queue resource to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Queue resource to fetch |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.queue](../schemas/api-v2010-account-queue/api-v2010-account-queue.md)

## Security

- **accountSid_authToken**
