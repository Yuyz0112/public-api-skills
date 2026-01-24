# DELETE /v1/accounts/{account}/external_accounts/{id}

**Resource:** [accounts](../resources/accounts.md)
**Delete an external account**
**Operation ID:** `DeleteAccountsAccountExternalAccountsId`

<p>Delete a specified external account for a given account.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account` | path | string | Yes |  |
| `id` | path | string | Yes | Unique identifier for the external account to be deleted. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[deleted_external_account](../schemas/deleted/deleted-external-account.md)

