# GET /2010-04-01/Accounts/{AccountSid}/IncomingPhoneNumbers/{ResourceSid}/AssignedAddOns/{Sid}.json

**Resource:** [Api20100401AssignedAddOn](../resources/Api20100401AssignedAddOn.md)
**Fetch an instance of an Add-on installation currently assigned to this Number.**
**Operation ID:** `FetchIncomingPhoneNumberAssignedAddOn`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the resource to fetch. |
| `ResourceSid` | path | string | Yes | The SID of the Phone Number to which the Add-on is assigned. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the resource to fetch. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[api.v2010.account.incoming_phone_number.incoming_phone_number_assigned_add_on](../schemas/api-v2010-account-incoming/api-v2010-account-incoming-phone-number-incoming-phone-number-assigned-add-on.md)

## Security

- **accountSid_authToken**
