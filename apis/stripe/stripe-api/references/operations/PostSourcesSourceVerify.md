# POST /v1/sources/{source}/verify

**Resource:** [sources](../resources/sources.md)
**Operation ID:** `PostSourcesSourceVerify`

<p>Verify a given source.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `source` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[source](../schemas/source/source.md)

