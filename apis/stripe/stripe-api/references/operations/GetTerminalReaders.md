# GET /v1/terminal/readers

**Resource:** [terminal](../resources/terminal.md)
**List all Readers**
**Operation ID:** `GetTerminalReaders`

<p>Returns a list of <code>Reader</code> objects.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `device_type` | query | enum: bbpos_chipper2x, bbpos_wisepad3, bbpos_wisepos_e... | No | Filters readers by device type |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `location` | query | string | No | A location ID to filter the response list to only readers at the specific location |
| `serial_number` | query | string | No | Filters readers by serial number |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |
| `status` | query | enum: offline, online | No | A status filter to filter readers to only offline or online readers |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

