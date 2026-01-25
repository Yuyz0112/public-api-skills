# GET /2010-04-01/Accounts/{AccountSid}/Queues/{QueueSid}/Members/{CallSid}.json

**Resource:** [Api20100401Member](../resources/Api20100401Member.md)
**Fetch a specific member from the queue**
**Operation ID:** `FetchMember`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Member resource(s) to fetch. |
| `QueueSid` | path | string | Yes | The SID of the Queue in which to find the members to fetch. |
| `CallSid` | path | string | Yes | The [Call](https://www.twilio.com/docs/voice/api/call-resource) SID of the resource(s) to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.queue.member](../schemas/api-v2010-account-queue-member/api-v2010-account-queue-member.md)

## Security

- **accountSid_authToken**
