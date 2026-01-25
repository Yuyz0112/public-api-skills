# GET /v1/tax/settings

**Resource:** [tax](../resources/tax.md)
**Retrieve settings**
**Operation ID:** `GetTaxSettings`

<p>Retrieves Tax <code>Settings</code> for a merchant.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax.settings](../schemas/tax-settings/tax-settings.md)

