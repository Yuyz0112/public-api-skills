# GET /v1/sources/{source}/mandate_notifications/{mandate_notification}

**Resource:** [sources](../resources/sources.md)
**Retrieve a Source MandateNotification**
**Operation ID:** `GetSourcesSourceMandateNotificationsMandateNotification`

<p>Retrieves a new Source MandateNotification.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `mandate_notification` | path | string | Yes |  |
| `source` | path | string | Yes |  |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[source_mandate_notification](../schemas/source/source-mandate-notification.md)

