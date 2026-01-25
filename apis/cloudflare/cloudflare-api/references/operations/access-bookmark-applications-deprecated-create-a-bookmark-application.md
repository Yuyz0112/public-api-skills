# POST /accounts/{account_id}/access/bookmarks/{bookmark_id}

**Resource:** [Access Bookmark applications (Deprecated)](../resources/Access-Bookmark-applications-Deprecated.md)
**Create a Bookmark application**
**Operation ID:** `access-bookmark-applications-(-deprecated)-create-a-bookmark-application`
⚠️ **Deprecated**

Create a new Bookmark application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `bookmark_id` | path | access_uuid | Yes |  |
| `account_id` | path | access_components-schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a Bookmark application response |
| 4XX | Create a Bookmark application response failure |

**Success Response Schema:**

[access_bookmarks_components-schemas-single_response](../schemas/access/access-bookmarks-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
