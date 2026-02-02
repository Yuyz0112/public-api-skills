# GET /auditing/record

**Resource:** [auditing](../resources/auditing.md)
**Operation ID:** `getRecords`

Returns auditing records filtered using provided parameters

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `offset` | query | integer (int32) | No | - the number of record from which search starts |
| `limit` | query | integer (int32) | No | - maximum number of returned results (if is limit is <= 0 or > 1000, it will be set do default value: 1000) |
| `filter` | query | string | No | - text query; each record that will be returned must contain the provided text in one of its fields |
| `from` | query | string | No | - timestamp in past; 'from' must be less or equal 'to', otherwise the result set will be empty
               only records that where created in the same moment or after the 'from' timestamp will be provided in response |
| `to` | query | string | No | - timestamp in past; 'from' must be less or equal 'to', otherwise the result set will be empty
               only records that where created in the same moment or earlier than the 'to' timestamp will be provided in response |
| `projectIds` | query | string | No | - list of project ids to look for |
| `userIds` | query | string | No | - list of user ids to look for |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

