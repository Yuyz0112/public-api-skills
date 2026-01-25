# GET /ips

**Resource:** [Cloudflare IPs](../resources/Cloudflare-IPs.md)
**Cloudflare/JD Cloud IP Details**
**Operation ID:** `cloudflare-ips-cloudflare-ip-details`

Get IPs used on the Cloudflare/JD Cloud network, see https://www.cloudflare.com/ips for Cloudflare IPs or https://developers.cloudflare.com/china-network/reference/infrastructure/ for JD Cloud IPs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `networks` | query | string | No | Specified as `jdcloud` to list IPs used by JD Cloud data centers. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Cloudflare IP Details response |
| 4XX | Cloudflare IP Details response failure |

