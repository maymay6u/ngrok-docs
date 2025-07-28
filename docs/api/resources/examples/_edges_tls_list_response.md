<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-07-28T10:08:26Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_30V0Ch1fxaXLOlETKOhbHnZEzf8",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30V0Ch1fxaXLOlETKOhbHnZEzf8"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_30V0BSIDxdn708WIisEBlx4cbLs",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_30V0BSIDxdn708WIisEBlx4cbLs"
        },
        "enabled": true
      },
      "created_at": "2025-07-28T10:08:16Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_30V0BSoyUYQPpdUjNN1qSVqrSE7",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_30V0BSoyUYQPpdUjNN1qSVqrSE7"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
