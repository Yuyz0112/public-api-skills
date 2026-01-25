# payment_intent_next_action_pix_display_qr_code

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | string | No | The raw data string used to generate QR code, it should be used together with QR code library. |
| `expires_at` | integer | No | The date (unix timestamp) when the PIX expires. |
| `hosted_instructions_url` | string | No | The URL to the hosted pix instructions page, which allows customers to view the pix QR code. |
| `image_url_png` | string | No | The image_url_png string used to render png QR code |
| `image_url_svg` | string | No | The image_url_svg string used to render svg QR code |

