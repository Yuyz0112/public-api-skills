# payment_method_ideal

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bank` | enum: abn_amro, adyen, asn_bank... | No | The customer's bank, if provided. Can be one of `abn_amro`, `adyen`, `asn_bank`, `bunq`, `buut`, `finom`, `handelsbanken`, `ing`, `knab`, `mollie`, `moneyou`, `n26`, `nn`, `rabobank`, `regiobank`, `revolut`, `sns_bank`, `triodos_bank`, `van_lanschot`, or `yoursafe`. |
| `bic` | enum: ABNANL2A, ADYBNL2A, ASNBNL21... | No | The Bank Identifier Code of the customer's bank, if the bank was provided. |

