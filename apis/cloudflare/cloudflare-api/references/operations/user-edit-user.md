# PATCH /user

**Resource:** [User](../resources/User.md)
**Edit User**
**Operation ID:** `user-edit-user`

Edit part of your user details.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Edit User response |
| 4XX | Edit User response failure |

**Success Response Schema:**

[iam_single_user_response](../schemas/iam/iam-single-user-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
