# POST /index.php?/api/v2/add_case/{section_id}

**Resource:** [cases](../resources/cases.md)
**Add case**
**Operation ID:** `addCase`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [AddCaseRequest](../schemas/Add/AddCaseRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Created case |
| default | (reference) |

**Success Response Schema:**

[Case](../schemas/Case/Case.md)

## Security

- **basicAuth**
