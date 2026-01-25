# GET /2010-04-01/Accounts/{AccountSid}/SIP/Domains/{DomainSid}/Auth/Registrations/CredentialListMappings.json

**Resource:** [Api20100401AuthRegistrationsCredentialListMapping](../resources/Api20100401AuthRegistrationsCredentialListMapping.md)
**Retrieve a list of credential list mappings belonging to the domain used in the request**
**Operation ID:** `ListSipAuthRegistrationsCredentialListMapping`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the CredentialListMapping resources to read. |
| `DomainSid` | path | string | Yes | The SID of the SIP domain that contains the resources to read. |
| `PageSize` | query | integer (int64) | No | How many resources to return in each list page. The default is 50, and the maximum is 1000. |
| `Page` | query | integer | No | The page index. This value is simply for client state. |
| `PageToken` | query | string | No | The page token. This is provided by the API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **accountSid_authToken**
