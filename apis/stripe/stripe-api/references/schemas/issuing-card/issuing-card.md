# issuing.card

You can [create physical or virtual cards](https://docs.stripe.com/issuing) that are issued to cardholders.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `brand` | string | Yes | The brand of the card. |
| `cancellation_reason` | enum: design_rejected, lost, stolen | No | The reason why the card was canceled. |
| `cardholder` | [issuing.cardholder](issuing-cardholder.md) | Yes |  |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Supported currencies are `usd` in the US, `eur` in the EU, and `gbp` in the UK. |
| `cvc` | string | No | The card's CVC. For security reasons, this is only available for virtual cards, and will be omitted unless you explicitly request it with [the `expand` parameter](https://docs.stripe.com/api/expanding_objects). Additionally, it's only available via the ["Retrieve a card" endpoint](https://docs.stripe.com/api/issuing/cards/retrieve), not via "List all cards" or any other endpoint. |
| `exp_month` | integer | Yes | The expiration month of the card. |
| `exp_year` | integer | Yes | The expiration year of the card. |
| `financial_account` | string | No | The financial account this card is attached to. |
| `id` | string | Yes | Unique identifier for the object. |
| `last4` | string | Yes | The last 4 digits of the card number. |
| `latest_fraud_warning` | any | No | Stripe’s assessment of whether this card’s details have been compromised. If this property isn't null, cancel and reissue the card to prevent fraudulent activity risk. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `number` | string | No | The full unredacted card number. For security reasons, this is only available for virtual cards, and will be omitted unless you explicitly request it with [the `expand` parameter](https://docs.stripe.com/api/expanding_objects). Additionally, it's only available via the ["Retrieve a card" endpoint](https://docs.stripe.com/api/issuing/cards/retrieve), not via "List all cards" or any other endpoint. |
| `object` | enum: issuing.card | Yes | String representing the object's type. Objects of the same type share the same value. |
| `personalization_design` | any | No | The personalization design object belonging to this card. |
| `replaced_by` | any | No | The latest card that replaces this card, if any. |
| `replacement_for` | any | No | The card this card replaces, if any. |
| `replacement_reason` | enum: damaged, expired, lost... | No | The reason why the previous card needed to be replaced. |
| `second_line` | string | No | Text separate from cardholder name, printed on the card. |
| `shipping` | any | No | Where and how the card will be shipped. |
| `spending_controls` | [issuing_card_authorization_controls](issuing-card-authorization-controls.md) | Yes |  |
| `status` | enum: active, canceled, inactive | Yes | Whether authorizations can be approved on this card. May be blocked from activating cards depending on past-due Cardholder requirements. Defaults to `inactive`. |
| `type` | enum: physical, virtual | Yes | The type of the card. |
| `wallets` | any | No | Information relating to digital wallets (like Apple Pay and Google Pay). |

