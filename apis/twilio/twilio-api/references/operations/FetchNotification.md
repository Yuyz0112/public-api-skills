# GET /2010-04-01/Accounts/{AccountSid}/Notifications/{Sid}.json

**Resource:** [Api20100401Notification](../resources/Api20100401Notification.md)
**Fetch a notification belonging to the account used to make the request**
**Operation ID:** `FetchNotification`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Notification resource to fetch. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the Notification resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.notification-instance](../schemas/api-v2010-account-notification-instance/api-v2010-account-notification-instance.md)

## Security

- **accountSid_authToken**
