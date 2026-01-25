# POST /accounts/{account_id}/access/apps

**Resource:** [Access applications](../resources/Access-applications.md)
**Add an Access application**
**Operation ID:** `access-applications-add-an-application`

Adds a new application to Access.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_app_request](../schemas/access/access-app-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Add an Access application response |
| 4XX | Add an Access application response failure |

## Security

- **api_email**
- **api_key**
- **api_token**
