# POST /v1/tax/settings

**Resource:** [tax](../resources/tax.md)
**Update settings**
**Operation ID:** `PostTaxSettings`

<p>Updates Tax <code>Settings</code> parameters used in tax calculations. All parameters are editable but none can be removed once set.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[tax.settings](../schemas/tax-settings/tax-settings.md)

