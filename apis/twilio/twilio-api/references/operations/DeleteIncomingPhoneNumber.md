# DELETE /2010-04-01/Accounts/{AccountSid}/IncomingPhoneNumbers/{Sid}.json

**Resource:** [Api20100401IncomingPhoneNumber](../resources/Api20100401IncomingPhoneNumber.md)
**Delete a phone-numbers belonging to the account used to make the request.**
**Operation ID:** `DeleteIncomingPhoneNumber`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the IncomingPhoneNumber resources to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the IncomingPhoneNumber resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
