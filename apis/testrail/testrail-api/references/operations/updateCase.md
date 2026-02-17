# POST /index.php?/api/v2/update_case/{case_id}

**Resource:** [cases](../resources/cases.md)
**Update case**
**Operation ID:** `updateCase`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateCaseRequest](../schemas/Update/UpdateCaseRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Updated case |
| default | (reference) |

**Success Response Schema:**

[Case](../schemas/Case/Case.md)

## Security

- **basicAuth**
