# accounts

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/v1/accounts` | List all connected accounts | [View](../operations/GetAccounts.md) |
| POST | `/v1/accounts` |  | [View](../operations/PostAccounts.md) |
| GET | `/v1/accounts/{account}` | Retrieve account | [View](../operations/GetAccountsAccount.md) |
| POST | `/v1/accounts/{account}` | Update an account | [View](../operations/PostAccountsAccount.md) |
| DELETE | `/v1/accounts/{account}` | Delete an account | [View](../operations/DeleteAccountsAccount.md) |
| POST | `/v1/accounts/{account}/bank_accounts` | Create an external account | [View](../operations/PostAccountsAccountBankAccounts.md) |
| GET | `/v1/accounts/{account}/bank_accounts/{id}` | Retrieve an external account | [View](../operations/GetAccountsAccountBankAccountsId.md) |
| POST | `/v1/accounts/{account}/bank_accounts/{id}` |  | [View](../operations/PostAccountsAccountBankAccountsId.md) |
| DELETE | `/v1/accounts/{account}/bank_accounts/{id}` | Delete an external account | [View](../operations/DeleteAccountsAccountBankAccountsId.md) |
| GET | `/v1/accounts/{account}/capabilities` | List all account capabilities | [View](../operations/GetAccountsAccountCapabilities.md) |
| GET | `/v1/accounts/{account}/capabilities/{capability}` | Retrieve an Account Capability | [View](../operations/GetAccountsAccountCapabilitiesCapability.md) |
| POST | `/v1/accounts/{account}/capabilities/{capability}` | Update an Account Capability | [View](../operations/PostAccountsAccountCapabilitiesCapability.md) |
| GET | `/v1/accounts/{account}/external_accounts` | List all external accounts | [View](../operations/GetAccountsAccountExternalAccounts.md) |
| POST | `/v1/accounts/{account}/external_accounts` | Create an external account | [View](../operations/PostAccountsAccountExternalAccounts.md) |
| GET | `/v1/accounts/{account}/external_accounts/{id}` | Retrieve an external account | [View](../operations/GetAccountsAccountExternalAccountsId.md) |
| POST | `/v1/accounts/{account}/external_accounts/{id}` |  | [View](../operations/PostAccountsAccountExternalAccountsId.md) |
| DELETE | `/v1/accounts/{account}/external_accounts/{id}` | Delete an external account | [View](../operations/DeleteAccountsAccountExternalAccountsId.md) |
| POST | `/v1/accounts/{account}/login_links` | Create a login link | [View](../operations/PostAccountsAccountLoginLinks.md) |
| GET | `/v1/accounts/{account}/people` | List all persons | [View](../operations/GetAccountsAccountPeople.md) |
| POST | `/v1/accounts/{account}/people` | Create a person | [View](../operations/PostAccountsAccountPeople.md) |
| GET | `/v1/accounts/{account}/people/{person}` | Retrieve a person | [View](../operations/GetAccountsAccountPeoplePerson.md) |
| POST | `/v1/accounts/{account}/people/{person}` | Update a person | [View](../operations/PostAccountsAccountPeoplePerson.md) |
| DELETE | `/v1/accounts/{account}/people/{person}` | Delete a person | [View](../operations/DeleteAccountsAccountPeoplePerson.md) |
| GET | `/v1/accounts/{account}/persons` | List all persons | [View](../operations/GetAccountsAccountPersons.md) |
| POST | `/v1/accounts/{account}/persons` | Create a person | [View](../operations/PostAccountsAccountPersons.md) |
| GET | `/v1/accounts/{account}/persons/{person}` | Retrieve a person | [View](../operations/GetAccountsAccountPersonsPerson.md) |
| POST | `/v1/accounts/{account}/persons/{person}` | Update a person | [View](../operations/PostAccountsAccountPersonsPerson.md) |
| DELETE | `/v1/accounts/{account}/persons/{person}` | Delete a person | [View](../operations/DeleteAccountsAccountPersonsPerson.md) |
| POST | `/v1/accounts/{account}/reject` | Reject an account | [View](../operations/PostAccountsAccountReject.md) |
