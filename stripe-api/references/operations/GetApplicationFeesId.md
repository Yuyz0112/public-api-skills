# GET /v1/application_fees/{id}

**Resource:** [application_fees](../resources/application-fees.md)
**Retrieve an application fee**
**Operation ID:** `GetApplicationFeesId`

<p>Retrieves the details of an application fee that your account has collected. The same information is returned when refunding the application fee.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[application_fee](../schemas/application/application-fee.md)

