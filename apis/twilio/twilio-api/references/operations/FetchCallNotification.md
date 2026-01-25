# GET /2010-04-01/Accounts/{AccountSid}/Calls/{CallSid}/Notifications/{Sid}.json

**Resource:** [Api20100401CallNotification](../resources/Api20100401CallNotification.md)
**Operation ID:** `FetchCallNotification`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Call Notification resource to fetch. |
| `CallSid` | path | string | Yes | The [Call](https://www.twilio.com/docs/voice/api/call-resource) SID of the Call Notification resource to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Call Notification resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.call.call_notification-instance](../schemas/api-v2010-account-call-call/api-v2010-account-call-call-notification-instance.md)

## Security

- **accountSid_authToken**
