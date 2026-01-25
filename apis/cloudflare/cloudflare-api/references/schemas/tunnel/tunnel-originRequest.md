# tunnel_originRequest

Configuration parameters for the public hostname specific connection settings between cloudflared and origin server.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `access` | object | No | For all L7 requests to this hostname, cloudflared will validate each request's Cf-Access-Jwt-Assertion request header. |
| `caPool` | string | No | Path to the certificate authority (CA) for the certificate of your origin. This option should be used only if your certificate is not signed by Cloudflare. |
| `connectTimeout` | integer | No | Timeout for establishing a new TCP connection to your origin server. This excludes the time taken to establish TLS, which is controlled by tlsTimeout. |
| `disableChunkedEncoding` | boolean | No | Disables chunked transfer encoding. Useful if you are running a WSGI server. |
| `http2Origin` | boolean | No | Attempt to connect to origin using HTTP2. Origin must be configured as https. |
| `httpHostHeader` | string | No | Sets the HTTP Host header on requests sent to the local service. |
| `keepAliveConnections` | integer | No | Maximum number of idle keepalive connections between Tunnel and your origin. This does not restrict the total number of concurrent connections. |
| `keepAliveTimeout` | integer | No | Timeout after which an idle keepalive connection can be discarded. |
| `matchSNItoHost` | boolean | No | Auto configure the Hostname on the origin server certificate. |
| `noHappyEyeballs` | boolean | No | Disable the “happy eyeballs” algorithm for IPv4/IPv6 fallback if your local network has misconfigured one of the protocols. |
| `noTLSVerify` | boolean | No | Disables TLS verification of the certificate presented by your origin. Will allow any certificate from the origin to be accepted. |
| `originServerName` | string | No | Hostname that cloudflared should expect from your origin server certificate. |
| `proxyType` | string | No | cloudflared starts a proxy server to translate HTTP traffic into TCP when proxying, for example, SSH or RDP. This configures what type of proxy will be started. Valid options are: "" for the regular proxy and "socks" for a SOCKS5 proxy.
 |
| `tcpKeepAlive` | integer | No | The timeout after which a TCP keepalive packet is sent on a connection between Tunnel and the origin server. |
| `tlsTimeout` | integer | No | Timeout for completing a TLS handshake to your origin server, if you have chosen to connect Tunnel to an HTTPS server. |

## Nested Fields

### `access`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `audTag` | string[] | Yes | Access applications that are allowed to reach this hostname for this Tunnel. Audience tags can be identified in the dashboard or via the List Access policies API. |
| `required` | boolean | No | Deny traffic that has not fulfilled Access authorization. |
| `teamName` | string | Yes |  |

