# GET /accounts/{account_id}/access/bookmarks

**Resource:** [Access Bookmark applications (Deprecated)](../resources/Access-Bookmark-applications-Deprecated.md)
**List Bookmark applications**
**Operation ID:** `access-bookmark-applications-(-deprecated)-list-bookmark-applications`
⚠️ **Deprecated**

Lists Bookmark applications.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_components-schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Bookmark applications response |
| 4XX | List Bookmark applications response failure |

**Success Response Schema:**

[access_bookmarks_components-schemas-response_collection](../schemas/access/access-bookmarks-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
