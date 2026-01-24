# payment_method_details_p24

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bank` | enum: alior_bank, bank_millennium, bank_nowy_bfg_sa... | No | The customer's bank. Can be one of `ing`, `citi_handlowy`, `tmobile_usbugi_bankowe`, `plus_bank`, `etransfer_pocztowy24`, `banki_spbdzielcze`, `bank_nowy_bfg_sa`, `getin_bank`, `velobank`, `blik`, `noble_pay`, `ideabank`, `envelobank`, `santander_przelew24`, `nest_przelew`, `mbank_mtransfer`, `inteligo`, `pbac_z_ipko`, `bnp_paribas`, `credit_agricole`, `toyota_bank`, `bank_pekao_sa`, `volkswagen_bank`, `bank_millennium`, `alior_bank`, or `boz`. |
| `reference` | string | No | Unique reference for this Przelewy24 payment. |
| `verified_name` | string | No | Owner's verified full name. Values are verified or provided by Przelewy24 directly
(if supported) at the time of authorization or settlement. They cannot be set or mutated.
Przelewy24 rarely provides this information so the attribute is usually empty. |

