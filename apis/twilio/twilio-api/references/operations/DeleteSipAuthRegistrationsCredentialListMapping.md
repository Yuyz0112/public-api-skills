# DELETE /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{DomainSid}/Auth/Registrations/CredentialListMappings/{Sid}.json

**Resource:** [Api20100401AuthRegistrationsCredentialListMapping](../resources/Api20100401AuthRegistrationsCredentialListMapping.md)
**Delete a credential list mapping from the requested domain**
**Operation ID:** `DeleteSipAuthRegistrationsCredentialListMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the CredentialListMapping resources to delete. |
| `DomainSid` | path | string | Yes | The SID of the SIP domain that contains the resources to delete. |
| `Sid` | path | string | Yes | The Twilio-provided string that uniquely identifies the CredentialListMapping resource to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
