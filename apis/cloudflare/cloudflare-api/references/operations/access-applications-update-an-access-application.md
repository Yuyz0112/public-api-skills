# PUT /accounts/{account_id}/access/apps/{app_id}

**Resource:** [Access applications](../resources/Access-applications.md)
**Update an Access application**
**Operation ID:** `access-applications-update-an-access-application`

Updates an Access application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_app_id | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_app_request](../schemas/access/access-app-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an Access application response |
| 4XX | Update an Access application response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
