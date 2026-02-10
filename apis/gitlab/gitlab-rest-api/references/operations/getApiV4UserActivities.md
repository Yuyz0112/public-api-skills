# GET /api/v4/user/activities

**Resource:** [Users](../resources/Users.md)
**Get a list of user activities**
**Operation ID:** `getApiV4UserActivities`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `from` | query | string (date-time) | No | Date string in the format YEAR-MONTH-DAY |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

