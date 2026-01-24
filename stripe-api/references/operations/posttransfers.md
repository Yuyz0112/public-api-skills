# POST /v1/transfers

**Resource:** [transfers](../resources/transfers.md)
**Create a transfer**
**Operation ID:** `PostTransfers`

<p>To send funds from your Stripe account to a connected account, you create a new transfer object. Your <a href="#balance">Stripe balance</a> must be able to cover the transfer amount, or you’ll receive an “Insufficient Funds” error.</p>

## Request Body

**Required:** Yes

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[transfer](../schemas/transfer/transfer.md)

