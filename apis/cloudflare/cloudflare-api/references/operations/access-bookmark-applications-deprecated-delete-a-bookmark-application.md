# DELETE /accounts/{account_id}/access/bookmarks/{bookmark_id}

**Resource:** [Access Bookmark applications (Deprecated)](../resources/Access-Bookmark-applications-Deprecated.md)
**Delete a Bookmark application**
**Operation ID:** `access-bookmark-applications-(-deprecated)-delete-a-bookmark-application`
⚠️ **Deprecated**

Deletes a Bookmark application.

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
| 200 | Delete a Bookmark application response |
| 4XX | Delete a Bookmark application response failure |

**Success Response Schema:**

[access_id_response](../schemas/access/access-id-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
