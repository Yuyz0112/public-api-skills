# GET /accounts/{account_identifier}/custom_pages

**Resource:** [Custom pages for an account](../resources/Custom-pages-for-an-account.md)
**List custom pages**
**Operation ID:** `custom-pages-for-an-account-list-custom-pages`

Fetches all the custom pages at the account level.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_identifier` | path | custom-pages_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List custom pages response |
| 4xx | List custom pages response failure |

**Success Response Schema:**

[custom-pages_custom_page_result_list](../schemas/custom-pages/custom-pages-custom-page-result-list.md)

## Security

- **api_email**
- **api_key**
