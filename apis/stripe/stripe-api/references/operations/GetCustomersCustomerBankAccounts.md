# GET /v1/customers/{customer}/bank_accounts

**Resource:** [customers](../resources/customers.md)
**List all bank accounts**
**Operation ID:** `GetCustomersCustomerBankAccounts`
⚠️ **Deprecated**

<p>You can see a list of the bank accounts belonging to a Customer. Note that the 10 most recent sources are always available by default on the Customer. If you need more than those 10, you can use this API method and the <code>limit</code> and <code>starting_after</code> parameters to page through additional bank accounts.</p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `customer` | path | string | Yes |  |
| `ending_before` | query | string | No | A cursor for use in pagination. `ending_before` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, starting with `obj_bar`, your subsequent call can include `ending_before=obj_bar` in order to fetch the previous page of the list. |
| `expand` | query | string[] | No | Specifies which fields in the response should be expanded. |
| `limit` | query | integer | No | A limit on the number of objects to be returned. Limit can range between 1 and 100, and the default is 10. |
| `starting_after` | query | string | No | A cursor for use in pagination. `starting_after` is an object ID that defines your place in the list. For instance, if you make a list request and receive 100 objects, ending with `obj_foo`, your subsequent call can include `starting_after=obj_foo` in order to fetch the next page of the list. |

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

